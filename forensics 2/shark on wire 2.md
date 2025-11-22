## Descripción.
We found this [packet capture](https://challenge-files.picoctf.net/c_fickle_tempest/f208f7c58d3703ed5fe0a78f707f011fcbb8c0b210b35247762c7ccacb49fe46/capture.pcap). Recover the flag.

## Solución.

- Verificamos el archivo, vemos que es un archivo `.pcap` de captura de paquetes

`wireshark capture.pcap &`  

- Establecemos un filtro en el stream 32 y 60 y vemos marcas de `begin` y `end`

`udp.stream eq 32 udp.stream eq 60`

- Ahora observamos que el puerto destino udp es 22, establecemos fitro

`udp.dstport == 22`

- El puerto origen, si le quitas - 5000, iba formando las caracteres ascii en decimal y obtienes la flag

`>>> chr(112) 'p' >>> chr(105) 'i' >>> chr(99) 'c' >>> chr(111) 'o' >>>` 

- Otra forma es con `scapy` en python, primero instalamos `scapy`

`sudo apt install python3-scapy` 

- luego programamos el exploit que nos de la flag

`from scapy.all import *  packets = rdpcap('capture.pcap')  flag=''  for p in packets:     if UDP in p and p[UDP].dport == 22:         if p[UDP].sport > 5000:             flag+=chr(p[UDP].sport - 5000)  print(flag)`

## Notas.

## Referencias.
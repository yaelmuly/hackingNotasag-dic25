## Descripción.

Can you look at the data in this binary: static? This [
BASH script might help!

## Solución.

```
yael242-picoctf@webshell:~$ bash ltdis.sh static 
Attempting disassembly of static ...
Disassembly successful! Available at: static.ltdis.x86_64.txt
Ripping strings from binary with file offsets...
Any strings found in static have been written to static.ltdis.strings.txt with file offset
yael242-picoctf@webshell:~$ cat static.ltdis.strings.txt | grep pico
   1020 picoCTF{d15a5m_t34s3r_1e6a7731}
```

## Notas.

## Referencias.
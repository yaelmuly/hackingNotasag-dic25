## Descripción.

This file has a flag in plain sight (aka "in-the-clear").

## Solución.

`picoCTF{s4n1ty_v3r1f13d_b5aeb3dd}

 ```wget https://mercury.picoctf.net/static/217686fc11d733b80be62dcfcfca6c75/flag
--2025-09-01 17:16:24--  https://mercury.picoctf.net/static/217686fc11d733b80be62dcfcfca6c75/flag
Resolving mercury.picoctf.net (mercury.picoctf.net)... 18.189.209.142
Connecting to mercury.picoctf.net (mercury.picoctf.net)|18.189.209.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34 [application/octet-stream]
Saving to: 'flag'

flag                                                     100%[=================================================================================================================================>]      34  --.-KB/s    in 0s      

2025-09-01 17:16:24 (11.1 MB/s) - 'flag' saved [34/34]

yael242-picoctf@webshell:~$ cat flag
picoCTF{s4n1ty_v3r1f13d_b5aeb3dd}
 ``` 

## Notas.
- wget - para decargar archivos en terminal
-  cat - mostrar archivo

## Referencias.
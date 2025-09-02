## Descripción.

Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.

## Solución.

```
yael242-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 4427 | grep picoCTF
picoCTF{digital_plumb3r_5ea1fbd7}
```

## Notas.

## Referencias.

http://www.linfo.org/pipes.html
## Descripción.

To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 15130`.
## Solución.

- me conecte al puerto y use cyberchef para ir decodificando las actividades

```
yael242-picoctf@webshell:~$ nc jupiter.challenges.picoctf.org 15130
Let us see how data is stored
computer
Please give the 01100011 01101111 01101101 01110000 01110101 01110100 01100101 01110010 as a word.
...
you have 45 seconds.....

Input:
computer
Please give me the  143 150 141 151 162 as a word.
Input:
chair
Please give me the 737472656574 as a word.
Input:
street
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_02167de8}
```

## Notas.

## Referencias.

https://gchq.github.io/CyberChef/#recipe=From_Hex('None')&input=NzM3NDcyNjU2NTc0
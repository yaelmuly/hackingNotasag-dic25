## Descripción.
Decode this [message](https://challenge-files.picoctf.net/c_fickle_tempest/816c75fc4b45dfc4ab4c4caad4ac738a3e0cfb3825fedda2a753eb5360c477bb/message.wav) from the moon.

## Solución.
-Verificamos el tipo de archivo con file

`file message.wav` 

- Descargamos decodificador STTV de github y lo instalamos

> [https://github.com/colaclanth/sstv](https://github.com/colaclanth/sstv "https://github.com/colaclanth/sstv")

`cd /opt sudo git clone https://github.com/colaclanth/sstv cd sstv https://github.com/colaclanth/sstv`

- Decodificamos el mensaje oculto en el .wav y lo guardamos en flag.png

`sstv -d message.wav -o flag.png`

- Abrimos el archivo y copiamos la flag

`open flag.png`

## Notas.

## Referencias.
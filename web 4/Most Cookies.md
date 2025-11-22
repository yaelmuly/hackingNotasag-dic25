## Descripción.
Alright, enough of using my own encryption. Flask session cookies should be plenty secure! [server.py](https://mercury.picoctf.net/static/99a50920a248ec37c39b8e3ab0af8789/server.py) [http://mercury.picoctf.net:18835/](http://mercury.picoctf.net:18835/)

## Solución.
- **Copiar tu cookie actual** del sitio web cuando lo visitas normalmente.
- **Probar todas las claves secretas posibles** (los 28 nombres de galletas) hasta encontrar cuál funciona para descifrar tu cookie.
- **Crear una nueva cookie** que diga que eres "admin" en lugar de tu usuario normal, usando la clave secreta que encontraste.
- **Reemplazar tu cookie** en el navegador con la nueva cookie de administrador.
- **Actualizar la página** y verás la flag.

## Notas.

## Referencias.
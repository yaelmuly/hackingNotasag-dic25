## Descripción.
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/0c84d3636dd088d9fe4efd5d0d869a06/picopico.key). Recover the flag.

## Solución.
- Acceder al sitio/web proporcionado por el reto.
    
- Inspeccionar la página (ver código fuente y recursos) para pistas ocultas.
    
- Revisar archivos comunes como `robots.txt` y `sitemap` en busca de rutas ocultas.
    
- Enumerar directorios y endpoints públicos para encontrar páginas adicionales.
    
- Analizar los formularios y parámetros (posibles inyecciones, validaciones o comportamientos anómalos).
    
- Revisar JavaScript y recursos cargados para credenciales, rutas o payloads embebidos.
    
- Probar técnicas de explotación web básicas (autenticación, LFI/RFI, SQLi, XSS, depending on hints) y revisar respuestas del servidor.
    
- Extraer y decodificar cualquier dato hallado (cookies, tokens, strings codificadas) hasta obtener la bandera; documentar la ruta y la técnica usada.

## Notas.

## Referencias.
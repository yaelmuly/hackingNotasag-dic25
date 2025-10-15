## Descripción.
We found this [packet capture](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/capture.pcap) and [key](https://jupiter.challenges.picoctf.org/static/fbf98e695555a2a48fe42c9a245de376/picopico.key). Recover the flag.

## Solución.

1. Acceder al objetivo web proporcionado por el reto.
    
2. Inspeccionar el código fuente y los recursos cargados (HTML, JS, CSS) en busca de pistas.
    
3. Comprobar `robots.txt`, `sitemap` y rutas comunes para localizar páginas ocultas.
    
4. Enumerar directorios y endpoints adicionales (incluyendo archivos estáticos y APIs).
    
5. Analizar formularios, parámetros y cabeceras para identificar entradas manipulables.
    
6. Revisar y probar lógica del lado cliente (JavaScript) para funcionalidades ocultas o credenciales embebidas.
    
7. Intentar técnicas de explotación web básicas y específicas según las pistas (autenticación rota, fuerza/brute-force, parámetros no validados, bypasses).
    
8. Extraer, decodificar y verificar cualquier dato sensible o pista obtenida hasta revelar la bandera; documentar la ruta exacta y la técnica utilizada.

## Notas.

## Referencias.
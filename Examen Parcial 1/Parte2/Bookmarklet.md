## Descripción.

Why search for the flag when I can make a bookmarklet to print it for me?

Additional details will be available after launching your challenge instance.

## Solución.

- Use la funcion que me dio la misma pagina
- La guarde en un marcador de mi navegador
- La ejecute en la pagina del reto
funcion
`javascript:(function() {            var encryptedFlag = "àÒÆÞ¦È¬ëÙ£ÖÓÚåÛÑ¢ÕÓÓÇ¡¥Ìí";            var key = "picoctf";            var decryptedFlag = "";            for (var i = 0; i < encryptedFlag.length; i++) {                decryptedFlag += String.fromCharCode((encryptedFlag.charCodeAt(i) - key.charCodeAt(i % key.length) + 256) % 256);            }            alert(decryptedFlag);        })();`

flag
 `picoCTF{p@g3_turn3r_0c0d211f}`
## Notas.
- se puede guardar codigo en los marcadores

## Referencias.
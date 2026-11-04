# Canales

Grilla de señales oficiales para TizenBrew. La lista está en `canales.json`.

## Agregar desde la tele

Entrá a **+ Agregar**, poné un nombre y el enlace. Queda guardado en esa tele. Para borrarlo, marcalo y tocá el botón rojo.

## Agregar para todas las pantallas

1. Abrí `canales.json` en GitHub y tocá el lápiz.
2. Copiá una línea y cambiá sus datos. Todas las líneas llevan coma, menos la última.
3. Tocá **Commit changes** y volvé a abrir Canales en la tele.

Canal de YouTube (el `id` empieza con `UC`):

    { "name": "Nombre", "kind": "Noticias", "id": "UC..." },

Señal directa de video (`.m3u8`):

    { "name": "Nombre", "kind": "Noticias", "url": "https://sitio/señal.m3u8" },

Reproductor web que permita abrirse dentro de otra app:

    { "name": "Nombre", "kind": "Noticias", "url": "https://sitio/reproductor" },

Usá solo señales oficiales o con permiso para emitir.

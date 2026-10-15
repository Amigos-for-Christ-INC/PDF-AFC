# Editor de PDF · Amigos for Christ

Editor de PDF gratuito que funciona en el navegador y se puede instalar como app en el celular o la computadora. Los archivos se procesan en el dispositivo y no se suben a ningún servidor.

**Abrir la app:** https://amigos-for-christ-inc.github.io/PDF-AFC/

## Herramientas

- **Editar**: agregar texto, firma dibujada, imágenes, recuadros para tapar y resaltado.
- **Unir**: combinar varios PDF en uno.
- **Organizar**: reordenar, rotar, eliminar y extraer páginas.
- **Dividir**: por página, por rangos o cada N páginas (descarga en .zip).
- **Comprimir**: tres niveles de compresión.
- **Imágenes a PDF**: JPG, PNG o WEBP a PDF (Carta, A4 o tamaño de la imagen).
- **Marca de agua**: logo de Amigos for Christ o texto, y números de página, con vista previa.

## Instalar en el celular

- **Android (Chrome):** abrí la app y tocá **Instalar app**, o en el menú ⋮ elegí *Instalar aplicación*.
- **iPhone / iPad (Safari):** tocá **Compartir** → *Agregar a pantalla de inicio*.

Después de abrirla una vez, también funciona sin internet.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa |
| `manifest.webmanifest` | Nombre, colores e íconos para instalarla |
| `sw.js` | Permite instalarla y usarla sin conexión |
| `icons/` | Íconos de la app |

Al publicar cambios en `index.html`, cambiá `CACHE = 'pdf-amigos-v1'` en `sw.js` a `v2`, `v3`, etc., para que los teléfonos descarguen la versión nueva.

## Librerías

[pdf-lib](https://pdf-lib.js.org/) 1.17.1 · [PDF.js](https://mozilla.github.io/pdf.js/) 3.11.174 · [JSZip](https://stuk.github.io/jszip/) 3.10.1, cargadas desde cdnjs.

TU BELLEZA — TABLET ANDROID 10

Versión preparada para tablets Android 10.
- PWA con display fullscreen.
- Orientación horizontal para aprovechar la pantalla de tablet.
- ID de aplicación diferente para evitar conflictos con la instalación anterior.
- Service Worker v4.

PARA GITHUB PAGES:
Reemplaza en tu repositorio: index.html, manifest.webmanifest y sw.js.
Conserva icon-192.png e icon-512.png.
Después de publicar, desinstala el Tu Belleza anterior de la tablet y vuelve a instalar esta versión.

Si la tablet no admite fullscreen PWA, Chrome hará fallback a standalone.


CAMBIOS DE ESTA VERSION
- La pestaña "Administrar" es el único lugar desde donde se modifican los datos.
- Servicios, inventario, clientes, citas, ventas y galería se consultan desde sus pestañas normales sin botones de edición.
- La Galería permite seleccionar imágenes directamente desde la galería/archivos del teléfono, tablet o computadora.
- Las imágenes seleccionadas se guardan localmente en el dispositivo mediante el almacenamiento del navegador.
- Para GitHub Pages, reemplaza index.html, manifest.webmanifest y sw.js; conserva icon-192.png e icon-512.png.


VERSIÓN 7
- Cada apartado de consulta tiene el botón ✎ Editar en la esquina derecha.
- Servicios y Galería permiten elegir una imagen directamente desde la galería del teléfono/tablet/computadora.
- Las imágenes se reducen automáticamente para poder guardarlas localmente.
- Se actualizó el Service Worker para evitar que siga cargando la versión anterior.

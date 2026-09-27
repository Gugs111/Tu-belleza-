TU BELLEZA — V5

Cambios principales:
- La pestaña Inventario es solo de consulta y descuento de productos vendidos.
- En Inventario no se puede agregar, editar ni eliminar productos.
- Cada producto muestra únicamente el botón “− Quitar vendido”.
- Al tocarlo se indica cuántas unidades vendidas se quieren descontar.
- No permite descontar más unidades de las disponibles.
- Agregar/editar/eliminar productos sigue estando en Administrar.
- Se mantiene la protección contra selección accidental de texto en la interfaz.

Para actualizar GitHub Pages:
1. Reemplaza index.html, sw.js, manifest.webmanifest y README.txt.
2. Conserva icon-192.png e icon-512.png.
3. Guarda/Commit los cambios.
4. Recarga la página. Si sigue apareciendo la versión anterior, borra los datos/caché del sitio y vuelve a abrirlo.


V6: los servicios permiten varias fotos desde la galería. Al tocar un servicio se abre su detalle y las imágenes; se puede tocar cada imagen para verla grande. El selector de fotos usa multiple.

ACCESO DIRECTO SIN INSTALAR

Se agregó acceso.html. Esta página NO tiene manifest PWA, por lo que sirve para crear un acceso directo de Chrome que abre Tu Belleza dentro de Chrome.

Para crear el acceso directo en una tablet donde Chrome solo muestra “Instalar aplicación”:
1. Abre: TU-DOMINIO/acceso.html
2. En Chrome toca ⋮.
3. Busca “Instalar y crear acceso directo” > “Crear acceso directo”. Si tu versión usa otro nombre, elige la opción equivalente para crear un acceso directo.
4. Ponle “Tu Belleza” y toca Añadir.

La página principal index.html conserva el manifest, así que en teléfonos compatibles seguirá apareciendo la opción de instalar Tu Belleza como aplicación PWA.

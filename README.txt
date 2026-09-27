TU BELLEZA - VERSION CUENTA + INVENTARIO

Esta versión agrega:
- Cuenta con Supabase para compartir datos entre dispositivos.
- Inicio de sesión y creación de cuenta.
- Datos separados por usuario mediante RLS.
- Sincronización de servicios, inventario, clientes, citas, ventas, galería y configuración.
- Inventario: solo permite descontar productos vendidos desde la pestaña Inventario.
- Alta/edición/eliminación de productos queda en Administrar.
- Mantiene la selección de imágenes desde la galería.

IMPORTANTE:
1. Conserva icon-192.png e icon-512.png en GitHub.
2. Configura supabase-config.js con Project URL y Publishable/anon key.
3. Ejecuta el SQL de SUPABASE_SETUP.txt en Supabase.
4. Sube index.html, sw.js, manifest.webmanifest, supabase-config.js y README/SUPABASE_SETUP.
5. Actualiza la página después de publicar.

No uses service_role key en la página.

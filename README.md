# Menú semanal de casa

App web instalable (PWA) para planificar el menú semanal de Héctor y Yasmin, con raciones ajustadas a cada uno, lista de la compra y seguimiento de peso y cintura.

## Publicar en GitHub Pages
1. Sube todos los archivos a la raíz del repositorio (rama `main`).
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En un par de minutos estará en `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`.

## Instalar en el móvil
- **Android (Chrome):** abre la URL → menú ⋮ → *Instalar aplicación*.
- **iPhone (Safari):** abre la URL → botón Compartir → *Añadir a pantalla de inicio*.

## Actualizar
Cuando cambies `index.html`, sube también `sw.js` con el número de `VERSION` aumentado (`menu-v2`, `menu-v3`…). Cierra y abre la app para ver la versión nueva.

## Datos
Se guardan en el navegador de cada móvil (`localStorage`). Usa **Ajustes → Descargar copia** para hacer copias de seguridad o pasar los datos a otro dispositivo.

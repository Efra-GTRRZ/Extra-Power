# EFRA EXTRA POWER

Proyecto web estático preparado para GitHub y Cloudflare Pages.

## Estructura
- `index.html`: página completa. El CSS está dentro de `<style>` y el icono de WhatsApp está en SVG inline.
- `assets/images/efra-retrato.jpg`: fotografía que antes estaba incrustada en el HTML.

## Recursos externos
La página carga las fuentes Anton y Work Sans desde Google Fonts. Si no hay conexión, se mostrarán las fuentes de respaldo definidas en el CSS.

## Publicación en Cloudflare Pages
- Framework preset: None
- Build command: dejar vacío
- Build output directory: `/` o `.` (raíz del repositorio)
- Root directory: dejar el valor predeterminado (raíz)

`index.html` debe quedar directamente en la raíz del repositorio.

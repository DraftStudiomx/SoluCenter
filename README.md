# Solucenter

Sitio web de Solucenter — pinturería y soluciones de construcción en León, Guanajuato.

Catálogo de productos, visualizador de colores e igualación de tonos, con contacto
directo por WhatsApp. Optimizado para SEO local (Google y Maps).

## Stack
Sitio estático de un solo archivo (`index.html`), JavaScript vanilla, sin dependencias
de build. Únicas cargas externas: Google Fonts y el mapa embebido de Google Maps.

## Estructura
- `index.html` — el sitio completo (estilos y scripts incluidos).
- `assets/` — logos de marca, fotos de categoría e imagen Open Graph.

## Desarrollo local
Servir la carpeta con cualquier servidor estático, por ejemplo:

    python -m http.server 4173

y abrir http://localhost:4173

## Despliegue
Hosting estático (Cloudflare Pages / GitHub Pages). El dominio de producción es
solucenter.com.mx.

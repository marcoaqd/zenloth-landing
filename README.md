# Zenloth — Landing Page

Sitio web estático y cinemático de Zenloth (fintech con calma, Costa Rica 🌿).
Listo para publicar. Funciona en computadora, iPad y celular automáticamente.

## Estructura

| Archivo / carpeta | Qué es |
|---|---|
| `index.html` | Página principal (cinemática con scroll) |
| `info.html` | Centro de información (lista de espera, seguridad, sobre nosotros…) |
| `404.html` | Página de "no encontrado" con Zenny |
| `src/` | Imágenes y videos (no separar de los `.html`) |
| `.nojekyll` | Hace que GitHub Pages sirva todos los archivos tal cual |
| `LEEME-DEPLOY.txt` | Instrucciones detipo paso a paso para publicar |

## Publicar en un dominio propio

Es un sitio 100% estático (solo archivos, sin base de datos). Subir el **contenido**
de este repo a la raíz del hosting, dejando `index.html` en la raíz.

- **Fácil (gratis):** arrastrar la carpeta a https://app.netlify.com/drop o Cloudflare Pages.
- **Hosting tradicional:** subir por FTP/cPanel a `public_html`.

Ver `LEEME-DEPLOY.txt` para el detalle completo.

## Nota para compartir en redes

Para que la miniatura aparezca al pegar el link en WhatsApp/redes, poner la URL
absoluta del dominio en las etiquetas `og:image` y `twitter:image` de `index.html`.

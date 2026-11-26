# Piano Marietta

Sitio web público del videojuego Piano Marietta. La página principal presenta el proyecto y el botón **JUGAR AHORA** abre el videojuego en una pestaña independiente.

## Estructura

- `index.html`: página web principal.
- `styles.css`: estilos de la página principal.
- `script.js`: interacciones y apertura del juego.
- `juego/index.html`: videojuego.
- `juego/styles.css`: estilos del videojuego.
- `juego/script.js`: lógica del videojuego y recursos de audio integrados.

## Publicar gratis con GitHub Pages

1. Crea un repositorio público en GitHub.
2. Sube **todo el contenido** de esta carpeta, manteniendo la carpeta `juego`.
3. En el repositorio entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`; guarda.
6. Espera la publicación. GitHub mostrará la dirección pública del sitio.

Abre la dirección pública y pulsa **JUGAR AHORA**. El juego se abrirá desde `juego/index.html` en otra pestaña.

> Importante: no subas solamente `index.html`; debes subir también los archivos CSS, JS y la carpeta `juego`.

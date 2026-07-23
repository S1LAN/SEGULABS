# SEGULAB — Dashboard estático

Página única (`index.html`), sin dependencias externas de archivos: CSS, JS
e imágenes (logo, favicon, mascota) van incrustados en el propio HTML.
Solo requiere internet para cargar Google Fonts y los íconos de lucide (CDN).

## Publicar con GitHub Pages

1. Sube este repositorio a GitHub (o arrastra `index.html` a uno ya creado).
2. Ve a **Settings → Pages**.
3. En "Source", elige la rama (normalmente `main`) y la carpeta `/ (root)`.
4. Guarda. GitHub te da una URL tipo:
   `https://tu-usuario.github.io/nombre-del-repo/`

No hace falta build ni configuración adicional: al estar todo en `index.html`,
GitHub Pages lo sirve tal cual.

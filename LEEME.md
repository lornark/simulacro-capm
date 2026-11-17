# Simulacro CAPM para iPhone

Esta carpeta contiene una versión instalable como app web (PWA) del simulador. No requiere Mac ni App Store. Conserva el progreso en el almacenamiento local del navegador del iPhone.

## Publicación necesaria

Para instalarla desde Safari, los archivos deben estar publicados en una dirección HTTPS. Puedes subir el contenido de esta carpeta a un hosting estático, por ejemplo GitHub Pages, Netlify o Cloudflare Pages. El servicio worker no funciona al abrir `index.html` directamente desde el disco.

## Instalar en iPhone 11

1. Abre en Safari la dirección HTTPS publicada.
2. Toca Compartir.
3. Elige **Añadir a pantalla de inicio** y confirma.
4. Abre **Simulacro CAPM** desde el nuevo ícono.

Después de la primera carga completa, la app puede abrirse sin conexión. Para recibir una versión nueva, abre la web con conexión una vez para que se actualice.

La carpeta incluye `index.html`, `manifest.webmanifest`, `sw.js` y los íconos requeridos. Esto es una app web instalable, no un archivo nativo `.ipa` de App Store.

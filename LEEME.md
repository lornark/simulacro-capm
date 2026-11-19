# Simulacro CAPM para iPhone

Simulador de práctica como aplicación web instalable (PWA). No requiere Mac ni App Store y guarda el progreso en el almacenamiento local del navegador.

El banco contiene **452 preguntas de práctica**: incluye 50 preguntas aportadas para el simulador y 100 casos nuevos alineados con los cuatro dominios del ECO. Puedes elegir exámenes de 10, 20, 150 o 160 preguntas. El examen CAPM real tiene 150 preguntas en 180 minutos; 15 son de preprueba sin calificar. La opción de 150 reproduce el tamaño total, pero el simulador califica todas las preguntas. La opción de 160 es práctica extendida. Las preguntas no son oficiales. Las referencias del banco y las tareas del ECO sirven para orientar el repaso; consulta también el ECO y los materiales actuales de PMI.

## Publicar con GitHub Pages

1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/(root)`.
4. Guarda los cambios y abre la dirección HTTPS que muestra GitHub Pages.

No requiere instalación de dependencias ni proceso de compilación. La app usa `index.html`, `manifest.webmanifest`, `sw.js` y los íconos de `icons/`.

## Instalar en iPhone

1. Abre la dirección HTTPS publicada en Safari.
2. Toca **Compartir**.
3. Elige **Añadir a pantalla de inicio** y confirma.
4. Abre **Simulacro CAPM** desde el ícono.

Después de la primera carga completa, la app puede abrirse sin conexión. Para recibir una versión nueva, vuelve a abrirla con conexión para que actualice el caché.

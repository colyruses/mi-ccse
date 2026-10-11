# Mi CCSE — versión inicial

Aplicación web progresiva para practicar preguntas CCSE en español.

## Incluye
- Simulacro de 25 preguntas y test rápido de 10.
- Práctica por temas.
- Corrección y explicación de respuestas.
- Historial y estadísticas guardados en el dispositivo.
- Archivos PWA básicos para añadir a la pantalla de inicio y caché.

## Cómo publicarla gratis con GitHub Pages
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio nuevo llamado `mi-ccse`.
3. Sube los cuatro archivos de esta carpeta: `index.html`, `manifest.json`, `sw.js`, `icon.svg`.
4. En el repositorio, abre **Settings → Pages**.
5. En “Build and deployment”, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
6. Cuando GitHub Pages publique la web, abre la URL que te proporcione en Chrome en Android.
7. En Chrome, abre el menú ⋮ y toca **Añadir a pantalla de inicio** o **Instalar aplicación** (la opción puede variar).

## Notas
- Esta es una versión de demostración con un banco inicial de preguntas redactadas para practicar; no es una aplicación oficial y no reproduce el banco oficial completo del Instituto Cervantes.
- Los resultados se guardan en el almacenamiento local del navegador/dispositivo. Si borras los datos del navegador, pueden perderse.
- El service worker permite guardar los archivos principales en caché tras la primera visita servida por HTTPS.
- El icono SVG puede no mostrarse como icono instalable en todos los navegadores; se puede añadir un icono PNG más adelante.

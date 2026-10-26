# Espejos Digitales — «Lo que ves ≠ Lo que es»

Página web estática funcional y lista para abrir.

## Cómo usarla

1. Descomprime este ZIP.
2. Abre directamente `index.html` en el navegador, o abre la carpeta en Visual Studio/Visual Studio Code.
3. Para una prueba completa con audio y descargas, ejecuta `python3 -m http.server 8000` desde esta carpeta y visita `http://localhost:8000`.

## Archivos principales

- `index.html`: estructura, contenido y controles de audio/video.
- `pagina.css`: estilos personalizados y animaciones.
- `tailwind.local.css`: estilos Tailwind incluidos localmente para que la página conserve su diseño sin depender de Internet.
- `pagina.js`: menú, paneles, podcast, parallax y resultados del test.
- `IMAGENES/` y `AUDIOS/`: recursos locales con rutas corregidas.
- `vendor/`: Chart.js y Font Awesome incluidos localmente.

Los videos de los relatos usan YouTube, por lo que esos videos sí requieren conexión a Internet. Las imágenes, estilos, JavaScript, íconos, gráfico del test y audios están incluidos en el proyecto.

MAGIC LIFE COUNTER — PRIMERA VERSIÓN PWA

ARCHIVOS: index.html, styles.css, app.js, manifest.webmanifest, sw.js, icon.svg

PARA PROBAR EN UN ORDENADOR:
1. Descomprime el ZIP.
2. En esa carpeta, abre una terminal y ejecuta: python -m http.server 8000
3. Abre http://localhost:8000 en el navegador.

PARA INSTALAR EN UN MÓVIL:
1. Publica el contenido de esta carpeta en un alojamiento HTTPS estático (por ejemplo GitHub Pages o Netlify).
2. Abre la dirección HTTPS desde Chrome en Android.
3. Usa el menú de Chrome > Añadir a pantalla de inicio / Instalar aplicación.
4. Tras la primera carga, los archivos esenciales quedan disponibles sin conexión.

NOTAS:
- El navegador solo permite instalar PWA y mantener la pantalla encendida en contextos seguros (HTTPS o localhost).
- El estado de la partida se guarda en el almacenamiento local del navegador.
- Los fondos se reducen de tamaño para ahorrar espacio, pero muchos fondos pueden agotar la cuota de almacenamiento del navegador.
- El daño de comandante se registra por cada comandante rival y modifica las vidas a la vez.
- La orientación se adapta a 2-6 jugadores. Los paneles de la fila superior giran 180 grados.
- Para probar en el móvil sin publicar, se necesita un servidor HTTPS o un entorno local configurado para ello.

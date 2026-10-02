Школа русского · 俄语心流 · Russian in Flow — versión web v0.3
================================================================

Contenido de la carpeta
- index.html   La web completa (juego, lecciones, diccionario). Todo el código y los datos van dentro.
- audio.mp3    Los 1.032 audios en ruso en un solo archivo. index.html lo descarga y lo trocea.
- favicon.svg  Icono de la pestaña.

Cómo publicarla
Sube los TRES archivos juntos a la misma carpeta de cualquier hosting de archivos estáticos.
Ejemplos: Netlify (arrastra la carpeta a app.netlify.com/drop), Vercel, Cloudflare Pages,
GitHub Pages, o tu propio servidor (Nginx/Apache).
No necesita base de datos ni servidor de aplicaciones.

Importante
- No funciona el audio si abres index.html con doble clic (file://): el navegador bloquea
  la descarga de audio.mp3. Para probar en tu Mac:  cd a esta carpeta y ejecuta
      python3 -m http.server 8000
  y abre http://localhost:8000
- Si publicas en China continental: las fuentes se cargan de Google Fonts, que allí está
  bloqueado. La web funciona igual (usa las fuentes del sistema), pero si quieres el diseño
  exacto, descarga las fuentes Inter y Rubik y sírvelas desde tu propio dominio.
- El progreso de cada usuario se guarda solo en su navegador (localStorage).
- Audio: voz sintética (Piper, ru_RU-irina-medium). Revisa su licencia o sustitúyela por
  grabaciones nativas antes de un uso comercial.

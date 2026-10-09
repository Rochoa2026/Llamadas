REGISTRO INTELIGENTE DE LLAMADAS — VERSIÓN 1

ARCHIVOS
index.html, styles.css, app.js, sw.js, manifest.webmanifest, icons/icon.svg

PUBLICAR EN GITHUB PAGES
1. Crea un repositorio público de GitHub.
2. Sube TODOS los archivos, conservando la carpeta icons y colocando index.html en la raíz.
3. En Settings > Pages > Build and deployment, selecciona Deploy from a branch, main y /(root).
4. Abre la dirección https://USUARIO.github.io/REPOSITORIO/ desde Chrome.
5. En Android utiliza el menú del navegador > Añadir a pantalla principal / Instalar aplicación.

OPERACIÓN
- Crear llamadas con fecha, horas, tipo, nombre y número.
- Adjuntar audios de llamadas que ya haya grabado el teléfono.
- Opcionalmente grabar sonido del micrófono; NO el audio interno de una llamada telefónica.
- Pegar o dictar transcripción (dictado experimental; depende del navegador).
- Crear un resumen extractivo sencillo revisable, sin IA.
- Buscar por datos, editar, eliminar, exportar CSV, TXT, JSON con audio y generar PDF mediante Imprimir.
- Almacenamiento local IndexedDB; no hay sincronización entre equipos ni cifrado en la app.
- Descargar respaldo JSON y guardarlo en lugar seguro. No borrar datos del sitio.
- Para transcribir audios adjuntos automáticamente se requiere un servicio de reconocimiento de voz adicional.

PRIVACIDAD Y CONSENTIMIENTO
Pedir consentimiento para grabar según las leyes que correspondan. Los archivos no se transmiten a un servidor por esta aplicación; el dictado de voz del navegador puede usar un servicio de terceros.

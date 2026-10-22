# WebPoints: datos y descargas

Aplicación personal de consulta de pádel FPPA y SNP. El código se mantiene en privado.

## Datos
La aplicación consulta `data/latest.json` y descarga el paquete de la release indicada.
Las actualizaciones se publican manualmente, como máximo semanalmente; la fecha de
publicación no garantiza que todas las fuentes se hayan consultado ese día.

## Android
Descarga la APK de una release `app-v…`, ábrela en Android y permite la instalación
desde el navegador cuando el sistema lo solicite. Conserva la misma instalación
para mantener favoritos. Desde un ordenador: `adb install -r webpoints-vVERSION.apk`.
Si no hay APK publicada, la versión móvil aún está en preparación.

## iPhone
Las APK no funcionan en iOS. La distribución para iPhone se realizará mediante los
canales de Apple cuando esté disponible. Expo Go se utiliza durante el desarrollo.

Los datos proceden de sus respectivas fuentes; no se concede una licencia sobre
contenido de terceros. No se publican contraseñas ni sesiones del scraper.

## Primera versión de prueba

[Descargar WebPoints 0.1.0 para Android](https://github.com/dgmdani02/WebPoints_updates/releases/download/app-v0.1.0/webpoints-v0.1.0.apk).

APK independiente de Expo Go. Pendiente de validación en dispositivos reales.
La publicación actualizada de Android se describe en [`app/android.json`](app/android.json).

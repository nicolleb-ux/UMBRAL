# UMBRAL

Experiencia audiovisual interactiva sobre la identidad digital.

## Ejecutar en local

Abre la carpeta en Visual Studio Code y usa Live Server. La cámara requiere `localhost` o HTTPS.

## Publicar con GitHub Pages

1. Crea un repositorio público nuevo en GitHub (por ejemplo, `umbral`).
2. Sube `index.html` a la raíz del repositorio.
3. En Settings > Pages elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
4. Abre la URL de Pages que te muestre GitHub, normalmente `https://TU-USUARIO.github.io/umbral/`.

## Interacciones

- Voz y barra espaciadora: notificaciones y glitch.
- Boca: transformación ocular.
- Movimiento de cabeza: ecos del rostro.
- Palma: maquillaje y retoque facial.
- Puño cerrado: pixelación y copias alteradas.

Los permisos de cámara y micrófono son opcionales y los solicita el navegador. El modelo de MediaPipe y la tipografía se descargan desde servicios externos; se necesita conexión a internet al menos al cargarlos. No se envían fotogramas a un servidor del proyecto. El botón DETENER apaga las pistas activas. No se garantiza funcionamiento idéntico en todos los dispositivos: depende de cámara, navegador y potencia.

## Para editar

- **Diseño:** bloque `<style>`.
- **Efectos:** primer bloque `<script>`.
- **Detección facial y de manos:** bloque `<script type="module">`.

No incluyas en un repositorio público material que quieras mantener privado.

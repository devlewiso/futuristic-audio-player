# Futuristic Player

Reproductor de música **sin anuncios** que corre en el navegador. Abrí canciones de tu compu o de tu celular Android
y escuchalas con visualizador, lista y controles en la pantalla de bloqueo. Nada se sube a ningún servidor.

## Qué hace

- **Abrir música**: botón «Agregar canciones» (en Android abre tus archivos o la carpeta Música), «Carpeta completa»
  en la compu, o arrastrar y soltar archivos o carpetas.
- **Formatos**: MP3, M4A/AAC, FLAC, OGG/Opus, WAV (lo que soporte el navegador).
- **Etiquetas ID3**: toma título, artista y portada del archivo.
- **Lista**: buscar, quitar, aleatorio, repetir lista o canción. Queda **guardada en el navegador** (IndexedDB),
  así que al volver a abrir la app tus canciones siguen ahí.
- **Visualizador** en tiempo real (Web Audio): anillo, barras u onda.
- **Pantalla de bloqueo y audífonos**: play/pausa, siguiente y anterior con Media Session.
- **App instalable (PWA)**: en Android, menú de Chrome → «Instalar app». Abre sin internet.
- **Teclado**: espacio play/pausa · ← → ±10 s · N/P siguiente/anterior · S aleatorio · R repetir · M silencio.
- Responsive, modo oscuro OLED, respeta «reducir movimiento».

## Usar

Es estático: `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`. Servilo con cualquier servidor
(`python3 -m http.server 3402`) o publicalo en cualquier hosting con HTTPS (el service worker y la instalación
necesitan HTTPS o `localhost`).

## Licencia

MIT

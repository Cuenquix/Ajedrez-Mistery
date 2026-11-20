# Cuenquix Juegos

Portal oficial de juegos originales creados por **Cuenquix**. Ajedrez Mistery y Parking Genius son dos juegos independientes bajo la misma marca.

## Juegos

- **Ajedrez Mistery** — variante de ajedrez con preparación personalizada de ejércitos, partidas contra bots y modo local para dos jugadores.
- **Parking Genius** — juego independiente de lógica y aparcamiento, con niveles, progreso y estrellas.

## Estructura

- `index.html` — portada y acceso a los juegos.
- `juegos/ajedrez-mistery.html` — Ajedrez Mistery.
- `juegos/parking-genius.html` — Parking Genius.
- `manifest.webmanifest` y `sw.js` — instalación como aplicación web (PWA) y caché básica.
- `icons/` — iconos de la aplicación.

## Jugar y compartir

**Web pública:** https://cuenquix.github.io/Ajedrez-Mistery/

Puedes compartir ese enlace con cualquier persona. No hace falta que tenga una cuenta de GitHub ni que instale nada. Los juegos se ejecutan en el navegador.

Enlaces directos:
- [Ajedrez Mistery](https://cuenquix.github.io/Ajedrez-Mistery/juegos/ajedrez-mistery.html)
- [Parking Genius](https://cuenquix.github.io/Ajedrez-Mistery/juegos/parking-genius.html)

## Instalar en el móvil

La web incluye una configuración inicial de **PWA**. En un navegador compatible, se puede añadir a la pantalla de inicio y abrir en una ventana propia:

- **iPhone/iPad:** abre la web en Safari, pulsa Compartir y elige «Añadir a pantalla de inicio».
- **Android:** abre la web en Chrome y usa «Instalar aplicación» o «Añadir a pantalla de inicio», según el dispositivo.

No es todavía una aplicación nativa publicada en App Store o Google Play. Es la misma web preparada para una experiencia instalable. La instalación no convierte el modo online en multijugador real.

## Publicación

GitHub Pages publica los archivos de la rama `main`. Los cambios subidos al repositorio se reflejan en la web cuando termina el despliegue.

## Datos y modos

- Las estadísticas de Ajedrez Mistery se guardan en el almacenamiento local del navegador.
- El modo local permite jugar en el mismo dispositivo.
- Los rivales del modo online son simulados; todavía no existe un servidor de multijugador en tiempo real.
- Parking Genius guarda el progreso localmente en el dispositivo.
- Los datos locales no se sincronizan automáticamente entre distintos móviles u ordenadores.

## Mantenimiento

El portal se presenta como `Cuenquix Juegos`. El repositorio conserva el nombre técnico `Ajedrez-Mistery` para no cambiar la dirección pública de GitHub Pages. Los nombres visibles de los juegos son **Ajedrez Mistery** y **Parking Genius**, sin el sufijo «Pro».

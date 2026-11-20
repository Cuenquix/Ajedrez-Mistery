# Cuenquix

Portal de juegos originales creados por **Cuenquix**. La marca reúne proyectos independientes: cada juego tiene su propia identidad y puede crecer por separado.

## Juegos
- **Ajedrez Mistery** — proyecto principal: una variante de ajedrez con preparación personalizada de ejércitos, partidas contra bots y modo local para dos jugadores.
- **Parking Genius** — proyecto independiente de lógica y aparcamiento, con niveles, progreso y estrellas.

La portada da protagonismo a Ajedrez Mistery sin limitar Cuenquix a un único juego. Si aparecen nuevas ideas, podrán incorporarse como proyectos independientes.

## Estructura
- `index.html` — portada Cuenquix y acceso a los juegos.
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
La web incluye una configuración inicial de **PWA**. En un navegador compatible, se puede añadir a la pantalla de inicio:
- **iPhone/iPad:** abre la web en Safari, pulsa Compartir y elige «Añadir a pantalla de inicio».
- **Android:** abre la web en Chrome y usa «Instalar aplicación» o «Añadir a pantalla de inicio», según el dispositivo.

No es todavía una aplicación nativa publicada en App Store o Google Play. La instalación no convierte el modo online en multijugador real.

## Publicación y nombre del repositorio
GitHub Pages publica los archivos de la rama `main`. Los cambios subidos al repositorio se reflejan en la web cuando termina el despliegue.

El repositorio conserva técnicamente el nombre `Ajedrez-Mistery` para proteger la dirección pública actual. **No lo renombramos todavía**: GitHub advierte que la URL de un sitio de proyecto de GitHub Pages no se redirige automáticamente al cambiar el nombre. Para no romper el enlace que ya se comparte, la marca visible y el nombre del portal son Cuenquix. [Documentación oficial de GitHub](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository).

## Datos y modos
- Las estadísticas de Ajedrez Mistery se guardan en el almacenamiento local del navegador.
- El modo local permite jugar en el mismo dispositivo.
- Los rivales del modo online son simulados; todavía no existe un servidor de multijugador en tiempo real.
- Parking Genius guarda el progreso localmente en el dispositivo.
- Los datos locales no se sincronizan automáticamente entre distintos móviles u ordenadores.

Los nombres visibles de los juegos son **Ajedrez Mistery** y **Parking Genius**, sin el sufijo «Pro».

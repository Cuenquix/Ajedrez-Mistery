# Ajedrez Mistery — Cuenquix

Portal oficial de juegos web de Ajedrez Mistery. Proyecto de **Cuenquix**.

## Juegos
- **Ajedrez Mistery Pro** — variante de ajedrez con preparación personalizada de ejércitos, partidas contra bots y modo local para dos jugadores.
- **Parking Genius Pro** — juego independiente de lógica y aparcamiento.

## Estructura
- `index.html` — portada y acceso a los juegos.
- `juegos/ajedrez-mistery.html` — Ajedrez Mistery Pro.
- `juegos/parking-genius.html` — Parking Genius Pro.

## Publicación
Este proyecto está preparado para GitHub Pages:
1. Abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige `main` y la carpeta `/(root)`.
4. Guarda y espera a que termine el despliegue.

Web: https://cuenquix.github.io/Ajedrez-Mistery/

## Datos y modos
- Las estadísticas de Ajedrez Mistery se guardan en el almacenamiento local del navegador.
- El modo local permite jugar en el mismo dispositivo.
- Los rivales del modo online son simulados; no existe todavía un servidor de multijugador en tiempo real.
- Parking Genius guarda el progreso localmente en el dispositivo.

## Mantenimiento
Los juegos son páginas estáticas y no requieren instalación ni servidor propio. Los cambios se publican al actualizar la rama `main`.

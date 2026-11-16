# barra

Mi cuaderno de entreno. Una app web personal para registrar series entre serie y serie, con el móvil en una mano.

**Úsala aquí:** https://macarenavega.github.io/barra/

## Qué hace

- **Hoy:** la semana tipo v4 (Día 1 Piernas, Día 2 Dominadas, Día 3 Movilidad con fuerza, Día 4 Full body). Propone la sesión que toca o la siguiente por prioridad, la separa por bloques y, en el Día 3, el modo "Escalo hoy" deja solo los bloques B y D. Arriba, el check diario de hipopresivos con racha. Al completar todas las series en el tope del rango, avisa de subir carga. Añadir una serie cuesta dos toques y sugiere lo que hiciste la última vez.
- **Ejercicios:** los de la semana tipo v4. La rutina del mes 2 queda archivada con su historial.
- **Progreso:** la gráfica de la mejor serie de cada entreno; en los ejercicios con peso, sigue los kilos.
- **Historial:** los entrenos por semana, con notas breves.

Series por repeticiones, por tiempo (con cronómetro para la plancha) o en minutos, con peso en kg y esfuerzo del 1 al 10 opcionales.

## Cómo está hecha

Un solo `index.html`, sin dependencias ni servidor. Los datos se guardan en el navegador (`localStorage`). La primera vez carga las últimas marcas del mes 1 como punto de partida; se borran desde el final del Historial.

## Créditos

- Ilustraciones de ejercicios, personajes y logo clay: propios.
- Iconos 3D: [3dicons](https://3dicons.co) (CC0), recortados y teñidos.
- Tipografías: Fredoka y Nunito (Google Fonts).

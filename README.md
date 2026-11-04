# barra

Mi cuaderno de entreno. Una app web personal para registrar series entre serie y serie, con el móvil en una mano.

**Úsala aquí:** https://macarenavega.github.io/barra/

## Qué hace

- **Hoy:** eliges qué sesión entrenas (tren superior A/B, tren inferior A/B), sin días fijos. Ves cada ejercicio con su objetivo y cuántas series llevas. Añadir una serie cuesta dos toques y sugiere lo que hiciste la última vez.
- **Ejercicios:** los 19 ejercicios de la rutina del mes 2, con su progresión (por ejemplo, push up inclinado de 50 a 20 cm).
- **Progreso:** la gráfica de la mejor serie de cada entreno; en los ejercicios con peso, sigue los kilos.
- **Historial:** los entrenos por semana, con notas breves.

Series por repeticiones, por tiempo (con cronómetro para la plancha) o en minutos, con peso en kg y esfuerzo del 1 al 10 opcionales.

## Cómo está hecha

Un solo `index.html`, sin dependencias ni servidor. Los datos se guardan en el navegador (`localStorage`). La primera vez carga las últimas marcas del mes 1 como punto de partida; se borran desde el final del Historial.

## Créditos

- Ilustraciones de ejercicios, personajes y logo clay: propios.
- Iconos 3D: [3dicons](https://3dicons.co) (CC0), recortados y teñidos.
- Tipografías: Fredoka y Nunito (Google Fonts).

# barra

Mi cuaderno de calistenia. Una app web personal para registrar series entre serie y serie, con el móvil en una mano.

**Úsala aquí:** https://macarenavega.github.io/barra/

## Qué hace

- **Hoy:** el entreno en curso. Añadir una serie cuesta dos toques y sugiere lo que hiciste la última vez.
- **Ejercicios:** ocho ejercicios de calistenia con su progresión, de la variante más fácil a la más difícil.
- **Progreso:** la gráfica de la mejor serie de cada entreno, coloreada por variante.
- **Historial:** los entrenos por semana, con notas breves.

Ejercicios por repeticiones y por tiempo (con cronómetro para los isométricos) y esfuerzo opcional del 1 al 10.

## Cómo está hecha

Un solo `index.html`, sin dependencias ni servidor. Los datos se guardan en el navegador (`localStorage`). La primera vez carga siete semanas de datos de ejemplo; se borran desde el final del Historial.

## Créditos

- Ilustraciones y personajes clay: propios.
- Iconos 3D: [3dicons](https://3dicons.co) (CC0), recortados y teñidos.
- Tipografías: Fredoka y Nunito (Google Fonts).

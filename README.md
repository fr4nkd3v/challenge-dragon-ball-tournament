# Torneo Dragon Ball: Sparking! ZERO

<div>
<img
  width="100%"
  src="https://www.mundodeportivo.com/alfabeta/hero/2024/10/dragon-ball-sparking-zero-mecanica.jpg?width=768&aspect_ratio=16:9&format=nowebp"
  alt="hero"
>
<div>

¡El último videojuego de **Dragon Ball** ya está aquí! Se llama **Dragon Ball:
Sparking! ZERO**.

Este programa simula un **Torneo de Artes Marciales** al más puro estilo de la
saga, donde luchadores con diferentes habilidades competirán y el sistema
decidirá quién es el ganador.

## Reglas del Torneo

### Luchadores

Cada luchador tiene los siguientes atributos:

- **Nombre**: Un nombre que identifique al luchador.
- **Atributos**:
  - **Velocidad**: Un valor entre 0 y 100.
  - **Ataque**: Un valor entre 0 y 100.
  - **Defensa**: Un valor entre 0 y 100.
- Cada luchador comienza la batalla con **100 puntos de salud**.

### Batalla

- En cada batalla se enfrentan **2 luchadores**.
- El luchador con mayor **velocidad** comienza atacando.
- El daño infligido se calcula restando la **defensa** del oponente al
  **ataque** del atacante.
- El oponente tiene un **20% de probabilidad de esquivar** el ataque.
- Si la **defensa** es mayor que el **ataque**, se recibe un **10% del daño de
  ataque**.
- Después de cada turno de ataque, el oponente pierde salud.
- La batalla finaliza cuando uno de los luchadores pierde toda su salud.

### Torneo

- El torneo solo es válido con un número de luchadores **potencia de 2**.
- Se crea un torneo por **parejas al azar** en cada ronda.
- Los luchadores se enfrentan en rondas eliminatorias.
- El **ganador** de cada batalla avanza a la siguiente ronda hasta que solo
  quede **uno**.
- El programa debe mostrar por consola todo lo que sucede en el torneo,
  incluyendo el **ganador final**.

## Ejecución

Para correr el programa, asegúrate de que los luchadores están configurados con
sus respectivos nombres y atributos, y que el número de luchadores es una
potencia de 2.

## Mi versión de la aplicación

Como parte de una primera versión, la aplicación calculará los resultados del
torneo mostrándolos por la consola del navegador.

Para desplegar la aplicación en local ejecute los comandos:

1. Instalar dependencias

   With npm: `npm install`

   Or yarn: `yarn install`

   Or pnpm: `pnpm install`

2. Levantar el proyecto en local

   With npm: `npm run start`

   Or yarn: `yarn run start`

   Or pnpm: `pnpm run start`

Con ello se abrirá su navegador por defecto y a continuación deberá abrir las
devtools para leer los resultados.

# Centro de control de Marte

Web didáctica e interactiva para explorar una misión simulada a Marte. Combina un panel de control con explicaciones sencillas sobre sus indicadores, información científica básica del planeta y una introducción al trabajo de los rovers.

## Qué encontrarás

- Indicadores de oxígeno, energía, temperatura y progreso, con explicaciones desplegables.
- Datos introductorios sobre Marte y una curiosidad sobre su cielo.
- Un recorrido por las etapas de trabajo de un rover y por qué no se conduce en tiempo real desde la Tierra.
- Diseño adaptable a móvil y escritorio, elaborado con HTML y CSS, sin dependencias ni JavaScript.
- Los indicadores de la misión están identificados expresamente como **simulados**. Los datos del planeta son aproximados y divulgativos.

## Ver la web

https://victoreuniv.github.io/centro-control-marte/

## Ejecutar localmente

Abre `index.html` directamente en un navegador o inicia un servidor local desde la raíz:

```bash
python3 -m http.server 8080
```

Visita `http://localhost:8080`.

## Tecnologías y accesibilidad

HTML5 semántico, CSS Grid, Flexbox, unidades relativas y media queries. Las explicaciones se despliegan con el elemento nativo `<details>`, compatible con teclado y ratón. Se respeta la preferencia del sistema para reducir movimiento.

## Fuentes científicas de referencia

- NASA Solar System Exploration, [Mars Facts](https://science.nasa.gov/mars/facts/).
- NASA Mars Exploration Program, [Mars Exploration Rovers](https://science.nasa.gov/mission/mars-exploration-rovers-spirit-and-opportunity/) y [Mars 2020: Perseverance](https://science.nasa.gov/mission/mars-2020-perseverance/).
- NASA, información sobre [la atmósfera de Marte](https://mars.nasa.gov/all-about-mars/facts/).

El panel no presenta telemetría en directo. Los datos de oxígeno, energía y progreso son ficticios para fines educativos; la temperatura mostrada es una referencia redondeada, no una lectura actual de Marte.

# Centro de control de Marte

Web educativa e interactiva sobre Marte que combina un centro de misión con contenidos sobre el planeta, los rovers y el diseño responsive.

## Incluye

- Explicaciones desplegables de oxígeno, energía, temperatura y progreso.
- Datos divulgativos sobre Marte y su exploración robótica.
- Diferenciación clara entre valores simulados y datos científicos aproximados.
- **Laboratorio Responsive** con medición en tiempo real del ancho del viewport y número de columnas CSS Grid.
- Justificación de HCI sobre adaptación, consistencia, carga cognitiva, legibilidad y diseño centrado en el usuario.

## Diseño responsive

El Grid principal usa `repeat(4, minmax(0, 1fr))`, pasa a dos columnas por debajo de `900px` y a una columna por debajo de `650px`. Las propiedades usan contenedores relativos y unidades como `rem`, `%`, `vw` y `clamp()`.

Al cambiar el tamaño del navegador, el script observa el grid real y actualiza:

- el número de columnas calculado por el navegador;
- el ancho actual del viewport;
- la reorganización visible de las tarjetas.

No utiliza simulaciones ni controles artificiales de tamaño.

## Uso local

```bash
python3 -m http.server 8080
```

Abre `http://localhost:8080`.

## Publicación

https://victoreuniv.github.io/centro-control-marte/

## Referencias científicas

- NASA, [Mars Facts](https://science.nasa.gov/mars/facts/).
- NASA, [Mars 2020 Perseverance](https://science.nasa.gov/mission/mars-2020-perseverance/).
- NASA, [All About Mars](https://mars.nasa.gov/all-about-mars/facts/).

Los porcentajes de oxígeno, energía y progreso son ficticios. La temperatura es una referencia aproximada y no una lectura real actual.

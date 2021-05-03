Creá 6 botones con texto y agregarles los siguientes estilos:

```css
button {
  height: 2.5rem;
  min-width: 2.5rem;
  font-weight: 600;
  font-size: 1rem;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial,
    sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';
  line-height: 1.2;
  padding: 0 1rem;
  border: 0;
  border-radius: 0.25rem;
  outline: none;
  transition: all 250ms ease 0s;
  user-select: none;
  cursor: pointer;
}
```
:warning: Consideraciones:

* todos los botones al hacer `hover` sobre ellos deben tener un contorno, utilizá `box-shadow`;
* los tres primeros botones:
  * deben tener como color de fondo `#FFCCCC` y color de texto `#D609E6`;
  * al hacer `hover` sobre ellos el color de fondo deberá cambiar a `#D609E6` y el texto a `#FFCCCC`;
  * cuando tengan un estado `active` el color de fondo deberá ser `#960FE6` y el texto a `#FFFFFF`;
* los tres últimos botones:
  * deben tener como color de fondo `#D609E6` y color de texto `#FFCCCC`;
  * al hacer `hover` sobre ellos el color de fondo deberá cambiar a `#FFCCCC` y el texto a `#D609E6`;
  * cuando tengan un estado `active` el color de fondo deberá ser `#960FE6` y el texto a `#FFFFFF`.
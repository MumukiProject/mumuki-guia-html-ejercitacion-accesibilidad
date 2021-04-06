
Crear 6 botones con texto y agregarles los siguientes estilos:

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

<br>

- Cambiarles el color de fondo y el color de texto a cada botón, de modo que haya 3 botones con color de fondo claro y texto oscuro, y 3 con color de fondo oscuro y color de texto claro. La relación de contraste entre el color de texto y el de fondo _debe ser_ de 4.5 o mayor.
- Agregarles un contorno al hacer foco con `box-shadow`.
- Diferenciar los estados `:hover` y `:active` haciendo que el color de fondo se aclare o oscurezca, manteniendo una relación de contraste accesible.

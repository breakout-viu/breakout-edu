# Breakout EDU · Minijuegos

Minijuegos educativos para un Breakout EDU de 5.º de Primaria, pensados para insertarse con un `iframe` en Genially.

## Juegos

| Carpeta | Juego | Temática |
|---|---|---|
| `juego1/` | Rescate submarino | ODS 14 · Vida submarina |

## Juego 1 · Rescate submarino

- El alumnado maneja un submarino (flechas, WASD, clic o toque) y limpia 5 residuos del fondo del mar.
- Cada residuo abre una pregunta de 3 opciones. Si acierta, el residuo se recicla y el arrecife recupera color. Si falla, pierde oxígeno (25 % por fallo).
- Al limpiar los 5 residuos aparece una adivinanza. Su solución es la contraseña que se escribe en Genially.
- Las preguntas, posiciones, adivinanza y pista están en el objeto `CONFIG`, al principio del `<script>` de `juego1/index.html`.

## Insertar en Genially

```html
<iframe src="https://USUARIO.github.io/breakout-edu/juego1/" width="1280" height="720" style="border:0" allowfullscreen></iframe>
```

El juego mantiene la proporción 16:9 y se adapta a cualquier tamaño de iframe.

## Requisitos técnicos

Cada juego es un único `index.html` (HTML, CSS y JS juntos), sin librerías externas ni imágenes. Para probarlo en local basta con abrirlo en el navegador.

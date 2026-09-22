# Diseño en bloques

## Una sección debajo de otra

**Tagline:** Diseñar en bloques permite construir rápido sin perder estructura.

**Descriptor:** En esta etapa se trabaja con secciones verticales. El objetivo es entender cómo se organiza un sitio usando contenedores, márgenes, padding, jerarquía y ritmo, sin depender todavía de `flex`, `grid`, tablas o JavaScript.

## Objetivo

Construir una página clara usando una lógica de bloques. Cada sección debe tener una función y una estructura interna entendible.

## Cómo se consigue

Se consigue pensando cada sección como un módulo vertical.

Ejemplo:

```html
<section class="block">
  <div class="container">
    <h2>Nombre de la sección</h2>
    <p>Contenido principal de la sección.</p>
  </div>
</section>
```

## Subtemas

### Display block

Los elementos de bloque ocupan el ancho disponible y aparecen uno debajo de otro.

Ejemplos:

- `header`;
- `main`;
- `section`;
- `article`;
- `footer`;
- `div`;
- `h1`;
- `p`.

### Display inline

Los elementos en línea se acomodan dentro del flujo del texto mientras haya espacio.

Ejemplos:

- `a`;
- `span`;
- `strong`;
- `em`.

### Contenedores

El contenedor ayuda a controlar el ancho y evitar que el texto se extienda demasiado.

Ejemplo:

```css
.container {
  width: min(100% - 2rem, 72rem);
  margin: 0 auto;
}
```

### Espacio interno y externo

El diseño en bloques depende de:

- `margin`;
- `padding`;
- `border`;
- `box-sizing`;
- ancho máximo;
- alto mínimo;
- separación entre secciones.

### Secciones repetibles

Una estructura puede repetirse con contenido distinto.

Ejemplo:

```text
[ Sección: título + descriptor ]
[ Sección: título + lista ]
[ Sección: título + imagen ]
```

## Evidencia esperada

El sitio debe mostrar:

- secciones verticales claras;
- contenedores consistentes;
- jerarquía entre títulos y texto;
- ritmo entre bloques;
- adaptación básica a mobile.

## Errores comunes

- Poner todo dentro de un solo `div`.
- No usar contenedores.
- No controlar el ancho del texto.
- Usar márgenes inconsistentes.
- Confundir bloque con decoración visual.
- Crear secciones que no tienen función.

## Preguntas de revisión

- ¿Cada sección tiene una función?
- ¿El contenido se puede leer de arriba hacia abajo?
- ¿Los contenedores son consistentes?
- ¿Los espacios ayudan a entender la jerarquía?
- ¿El sitio funciona sin `flex` ni `grid`?

## Referencias

- [MDN: Block and inline layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flow_layout/Block_and_inline_layout_in_normal_flow)
- [MDN: The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- [MDN: box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
- [Every Layout: Boxes](https://every-layout.dev/rudiments/boxes/)


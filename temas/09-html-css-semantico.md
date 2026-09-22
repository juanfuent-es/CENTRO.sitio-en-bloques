# HTML y CSS semántico

## Estructura y presentación

**Tagline:** HTML organiza el contenido; CSS define cómo se ve.

**Descriptor:** El HTML debe reflejar la jerarquía del contenido. El CSS debe aplicar el sistema visual sin romper la lectura ni la estructura. Aunque la página sea sencilla, debe estar ordenada.

## Objetivo

Construir una página clara, legible y coherente con la estructura definida en Markdown, el mapa de sitio y los wireframes.

## Cómo se consigue

Se consigue usando etiquetas semánticas y clases simples.

Ejemplo:

```html
<header class="hero">
  <div class="container">
    <h1>Título del sitio</h1>
    <p class="tagline">Frase breve del proyecto.</p>
    <p class="descriptor">Contexto de la página.</p>
    <a href="#contenido">Explorar</a>
  </div>
</header>

<main id="contenido">
  <section class="block">
    <div class="container">
      <h2>Sección principal</h2>
      <p>Contenido de la sección.</p>
    </div>
  </section>
</main>
```

## Subtemas

### HTML semántico

Las etiquetas deben ayudar a entender el contenido.

Usar:

- `header`;
- `nav`;
- `main`;
- `section`;
- `article`;
- `footer`;
- `h1` a `h3`;
- `p`;
- `ul` / `ol`;
- `a`;
- `img`.

### Jerarquía de títulos

Debe existir un solo `h1` principal. Los `h2` y `h3` organizan secciones internas.

### CSS base

El CSS debe definir:

- variables;
- tipografías;
- colores;
- contenedores;
- márgenes;
- padding;
- links;
- botones;
- imágenes.

### Imágenes

Las imágenes deben tener:

- formato adecuado;
- peso razonable;
- dimensión controlada;
- texto alternativo;
- relación con el contenido.

### Estados

Los enlaces y botones deben tener estados básicos:

- normal;
- hover;
- focus.

## Evidencia esperada

El sitio debe incluir:

- `index.html`;
- archivo CSS separado;
- estructura semántica;
- clases claras;
- imágenes optimizadas cuando aplique;
- relación con el wireframe.

## Errores comunes

- Usar solo `div`.
- Saltar de `h1` a `h4` sin lógica.
- Poner estilos inline sin criterio.
- No vincular correctamente el CSS.
- Usar imágenes enormes.
- No poner `alt` en imágenes importantes.

## Preguntas de revisión

- ¿El HTML se entiende sin ver el CSS?
- ¿La jerarquía de títulos es clara?
- ¿Las clases nombran funciones reales?
- ¿El CSS aplica el sistema visual definido?
- ¿Las imágenes aportan al contenido?

## Referencias

- [MDN: HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)
- [MDN: HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [MDN: CSS basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
- [The A11Y Project: Alt text](https://www.a11yproject.com/posts/alt-text/)


# Sistema visual mínimo

## Colores, tipografía, escala y ritmo

**Tagline:** Un sistema visual mínimo permite que el sitio se vea coherente sin volverse complejo.

**Descriptor:** El sistema visual reúne las decisiones básicas de apariencia: color, tipografía, tamaños, espaciado, contraste, enlaces, botones y estados. Sirve para que las secciones del sitio parezcan parte del mismo proyecto.

## Objetivo

Definir reglas visuales suficientes para construir el sitio. No se necesita un sistema de diseño completo, pero sí una base clara y repetible.

## Cómo se consigue

Se consigue tomando decisiones a partir de la intención, el tono y las referencias visuales.

Un sistema visual mínimo puede incluir:

```css
:root {
  --color-background: #f4f4f0;
  --color-text: #171717;
  --color-accent: #5b3df5;

  --font-title: "Roboto", sans-serif;
  --font-base: system-ui, sans-serif;

  --space-section: 6rem;
  --space-container: 1.25rem;
}
```

## Subtemas

### Color

Una paleta mínima puede tener:

- fondo;
- texto;
- acento.

El color debe responder al tono, pero también debe permitir leer.

### Tipografía

Conviene distinguir entre:

- tipografía display para títulos o momentos expresivos;
- tipografía de lectura para párrafos y contenido largo.

Una tipografía display no siempre funciona para cuerpo de texto.

### Escala tipográfica

La escala define tamaños relativos entre textos.

Ejemplo:

```css
h1 {
  font-size: clamp(3rem, 8vw, 8rem);
}

h2 {
  font-size: clamp(2rem, 5vw, 4rem);
}

p {
  font-size: 1rem;
  line-height: 1.6;
}
```

### Espaciado

El espaciado define ritmo:

- margen entre secciones;
- padding interno;
- ancho de contenedor;
- separación entre títulos y párrafos.

### Contraste

El contraste permite leer. Un color puede verse bien en una paleta, pero fallar cuando se usa como texto sobre fondo.

## Evidencia esperada

El proyecto debe incluir:

- paleta de color;
- tipografías seleccionadas;
- screenshots de exploración tipográfica;
- prueba de contraste;
- reglas base de tamaño y espaciado;
- estilo de enlaces o botones.

## Errores comunes

- Elegir colores sin probar contraste.
- Usar demasiadas tipografías.
- Usar tipografía display en textos largos.
- Cambiar tamaños sin sistema.
- No definir estados para links o botones.
- No conectar el sistema visual con referencias.

## Preguntas de revisión

- ¿La paleta permite leer?
- ¿La tipografía de cuerpo es legible?
- ¿La tipografía display aporta al tono?
- ¿Los tamaños tienen jerarquía?
- ¿El sistema se puede repetir en varias secciones?

## Referencias

- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Google Fonts](https://fonts.google.com/)
- [Material Design: Color](https://m3.material.io/styles/color/overview)
- [The A11Y Project: Color Contrast](https://www.a11yproject.com/posts/what-is-color-contrast/)
- [MDN: Using CSS custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)


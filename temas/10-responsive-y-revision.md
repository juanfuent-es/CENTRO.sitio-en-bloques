# Responsive y revisión

## Probar antes de entregar

**Tagline:** Un sitio no está terminado hasta que se revisa en desktop y mobile.

**Descriptor:** La revisión responsive permite comprobar que el contenido se lee, que los bloques se adaptan y que las decisiones visuales funcionan en distintos tamaños de pantalla.

## Objetivo

Comprobar que el sitio se puede usar y leer en desktop y mobile. La revisión no es un paso decorativo: es parte de la entrega.

## Cómo se consigue

Se consigue probando el sitio en diferentes anchos y tomando capturas de evidencia.

Se debe revisar:

- legibilidad;
- contraste;
- jerarquía;
- espacios;
- imágenes;
- navegación;
- botones;
- orden de secciones.

## Subtemas

### Tamaños relativos

Usar medidas relativas ayuda a que el sitio se adapte.

Ejemplos:

- `%`;
- `rem`;
- `em`;
- `vw`;
- `clamp()`;
- `min()`;
- `max()`.

### Contenedores fluidos

Un contenedor puede tener un ancho flexible y un máximo.

```css
.container {
  width: min(100% - 2rem, 72rem);
  margin: 0 auto;
}
```

### Tipografía adaptable

Los títulos pueden ajustar su tamaño sin romper el layout.

```css
h1 {
  font-size: clamp(3rem, 10vw, 8rem);
}
```

### Screenshots

Los screenshots sirven como evidencia de revisión.

Se recomienda entregar:

- hero desktop;
- hero mobile;
- sección interior desktop;
- sección interior mobile.

### Checklist final

Antes de entregar:

- revisar ortografía;
- revisar enlaces;
- revisar contraste;
- revisar imágenes;
- revisar mobile;
- revisar jerarquía de títulos;
- revisar que los archivos estén ordenados.

## Evidencia esperada

El proyecto debe incluir capturas de revisión y una nota breve con ajustes realizados.

Ejemplo:

```md
## Revisión responsive

- Ajusté tamaño del `h1` con `clamp()`.
- Reduje el padding del hero en mobile.
- Cambié contraste del botón principal.
- Optimicé imágenes a máximo 1920 x 1080 px.
```

## Errores comunes

- Diseñar solo para desktop.
- No probar en una pantalla angosta.
- Usar textos que se desbordan.
- Usar imágenes demasiado pesadas.
- No revisar contraste.
- No entregar screenshots.

## Preguntas de revisión

- ¿El sitio se lee en mobile?
- ¿El hero funciona en desktop y mobile?
- ¿Los textos caben en sus contenedores?
- ¿Las imágenes se ajustan?
- ¿La navegación sigue siendo clara?

## Referencias

- [MDN: Responsive design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
- [MDN: clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp)
- [web.dev: Responsive images](https://web.dev/learn/images/)
- [PageSpeed Insights](https://pagespeed.web.dev/)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)


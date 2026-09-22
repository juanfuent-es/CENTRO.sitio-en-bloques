# Ejemplo: John Frusciante

## Discografía solista estructurada

**Tagline:** Una discografía como registro de transformación.

**Descriptor:** Este ejemplo muestra cómo organizar una colección amplia de álbumes en una estructura consistente antes de convertirla en una página web. La clave está en definir qué información se repite en cada elemento y mantener una jerarquía clara.

## Objetivo

Construir un documento digital sobre la discografía solista de John Frusciante a partir de contenido investigado, ordenado en Markdown y preparado para transformarse después en HTML y CSS.

## Información inicial

Entidades posibles:

- álbum;
- portada;
- fecha de publicación;
- track;
- duración;
- enlace de escucha;
- reseña contextual;
- fuente de consulta.

Atributos por álbum:

| Atributo | Función |
|---|---|
| Portada | Identifica visualmente el álbum |
| Título | Nombra cada elemento de la colección |
| Recomendación de escucha | Propone una entrada al disco |
| Fecha de publicación | Ubica el álbum cronológicamente |
| Tracklist | Muestra la estructura interna del álbum |
| Enlace | Conecta con la escucha |
| Reseña | Da contexto físico, emocional o creativo |

## Intención comunicativa

Presentar la discografía solista de John Frusciante como una colección organizada y navegable.

El sitio no busca contar todo sobre John Frusciante, sino mostrar cómo su obra solista puede entenderse como una serie de etapas: grabación doméstica, deterioro, recuperación, producción expansiva, intimidad acústica y exploración electrónica.

Ejemplo de enfoque:

> Una discografía que no funciona sólo como lista de discos, sino como archivo de cambios físicos, emocionales y creativos.

## Mapa de sitio

```text
Inicio
  Hero / Introducción
  Contexto del artista
  Discografía
    Álbum
    Álbum
    Álbum
  Fuentes
```

Ejemplo aplicado:

```text
Inicio
  John Frusciante
  Discografía solista
  Introducción breve

Contexto
  Quién es
  Por qué importa su obra solista
  Qué tipo de recorrido propone el sitio

Discografía
  2023 · : I I .
  2023 · . I :
  2020 · Maya
  2014 · Enclosure
  2012 · PBX Funicular Intaglio Zone
  2009 · The Empyrean
  2005 · Curtains
  2004 · Inside of Emptiness
  2004 · The Will to Death
  2004 · Shadows Collide with People
  2001 · To Record Only Water for Ten Days
  1997 · Smile from the Streets You Hold
  1994 · Niandra LaDes and Usually Just a T-Shirt

Fuentes
  Referencias consultadas
  Criterios de selección
```

## Tono verbal

- Claro.
- Contextual.
- Documental.
- Preciso.
- No especulativo.
- Sensible con temas de deterioro físico, adicción o salud emocional.

Ejemplos de frases:

- "Cada álbum registra un momento distinto de búsqueda."
- "Una discografía organizada como archivo sonoro y visual."
- "Contenido estructurado antes de convertirse en interfaz."
- "La obra solista permite leer cambios de sonido, cuerpo y contexto."
- "No se romantiza el deterioro: se documenta el contexto."

Ejemplo de tono aplicado:

> Fuera de las estructuras de una banda y de las expectativas comerciales, la obra solista de John Frusciante funciona como un espacio de exploración personal. Cada álbum registra una forma distinta de relacionarse con la música, el cuerpo, la tecnología y la idea de transformación.

## Tono visual

- Paleta reducida.
- Jerarquía editorial.
- Portadas como elemento visual principal.
- Bloques repetibles por álbum.
- Lectura clara antes que decoración.
- Sensación de archivo musical, no de cartel promocional.
- Contraste entre intimidad, ruido, fragilidad y estructura.

Ejemplo visual:

- Fondo claro o ligeramente cálido.
- Texto oscuro para lectura larga.
- Color acento para enlaces, fechas o navegación.
- Portadas en formato consistente.
- Mucho espacio entre álbumes para evitar saturación.
- Cada álbum como una unidad independiente.

Referencias visuales posibles:

- Archivo musical.
- Fanzine editorial.
- Discografía comentada.
- Timeline visual.
- Libreto de álbum.
- Catálogo de colección.

## Sistema visual posible

```css
:root {
  --color-background: #f4f4f0;
  --color-text: #171717;
  --color-accent: #5b3df5;

  --font-title: "Roboto", sans-serif;
  --font-base: system-ui, sans-serif;
}
```

Ejemplo de aplicación:

- `--color-background` para dar sensación de papel o archivo.
- `--color-text` para mantener lectura clara.
- `--color-accent` para links de Spotify, fechas o navegación.
- `--font-title` para títulos de álbumes.
- `--font-base` para reseñas, tracklists y fuentes.

## Wireframe sugerido

```text
[ HERO ]
  Título
  Tagline
  Descriptor
  Navegación principal

[ CONTEXTO ]
  Breve introducción sobre el artista y su obra solista

[ DISCOGRAFÍA ]
  Álbum
    Portada
    Título
    Fecha
    Recomendación
    Tracklist
    Reseña

  Álbum
    misma estructura

[ FUENTES ]
  Lista de referencias consultadas
```

Ejemplo aplicado:

```text
[ HERO ]
  John Frusciante
  Discografía solista
  Una discografía como registro de transformación
  CTA: Explorar álbumes

[ CONTEXTO ]
  Texto breve sobre su obra fuera de Red Hot Chili Peppers

[ ÁLBUM ]
  Portada
  2009 · The Empyrean
  Recomendación de escucha
  Fecha de publicación
  Tracklist con enlaces
  Reseña contextual

[ ÁLBUM ]
  Misma estructura repetida

[ FUENTES ]
  Lista de fuentes y criterios de consulta
```

## Aprendizaje del ejemplo

Un sitio web no empieza con diseño visual. Empieza con una estructura clara de información.

Este ejemplo muestra cómo una colección extensa puede organizarse en Markdown mediante reglas consistentes. Después, esa estructura puede convertirse en HTML y recibir estilos sin perder orden, jerarquía ni sentido.

La estructura repetible permite que cada álbum tenga el mismo tipo de información, pero que conserve su propio contexto.

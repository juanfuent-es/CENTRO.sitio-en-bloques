# Ejemplo: John Frusciante

## Discografía solista estructurada

**Tagline:** Un recorrido por el lado más íntimo del artista.

**Descriptor:** Este ejemplo organiza la discografía solista de John Frusciante como una colección de álbumes con información consistente y contexto editorial. La estructura permite recorrer su obra en orden cronológico inverso y observar distintas etapas de búsqueda musical sin convertir la experiencia en una lista plana.

## Objetivo

Construir un documento digital sobre la discografía solista de John Frusciante a partir de contenido investigado, ordenado en Markdown y preparado para transformarse después en HTML y CSS.

El proyecto reúne 13 álbumes de estudio publicados bajo el nombre John Frusciante. Cada álbum comparte una estructura de datos y una reseña contextual sobre su proceso creativo y, cuando existe información documentada, su estado físico y emocional durante la grabación o publicación.

## Información inicial

Entidades posibles:

- álbum;
- portada;
- fecha de publicación;
- formato o disponibilidad;
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
| Fecha de publicación | Ubica el álbum cronológicamente |
| Formato y disponibilidad | Aclara ediciones o límites de escucha |
| Tracklist | Muestra la estructura interna del álbum |
| Duración | Complementa la información de cada track |
| Enlace | Facilita encontrar la grabación correcta |
| Reseña contextual | Sitúa el proceso creativo y el contexto documentado |

## Intención comunicativa

Presentar la discografía solista de John Frusciante como una colección organizada y navegable, capaz de mostrar cambios de sonido, métodos de producción y contextos personales a lo largo del tiempo.

El sitio no busca contar todo sobre John Frusciante. Propone un recorrido por su obra solista, desde *Niandra LaDes and Usually Just a T-Shirt* hasta *: I I .* y *. I :*, atendiendo a transformaciones como la experimentación doméstica, la recuperación, la producción expansiva, la intimidad acústica y la exploración electrónica.

> Una discografía que no funciona sólo como lista de discos, sino como archivo de cambios físicos, emocionales y creativos.

El contenido delimita su alcance: incluye 13 álbumes de estudio y excluye EP, sencillos, álbumes de descarga informal, colaboraciones acreditadas a dos artistas y publicaciones bajo los alias Trickfinger y Speed Dealer Moms.

## Mapa de sitio

```text
Inicio
  Hero / Introducción
  Contexto del artista
  Discografía
    Álbum
    Álbum
    Álbum
  Fuentes y criterios
```

Ejemplo aplicado:

```text
Inicio
  John Frusciante
  Discografía solista
  Un recorrido por el lado más íntimo del artista
  Introducción breve

Contexto
  Alcance de la selección
  Criterios de inclusión
  Cómo leer las reseñas

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
  Criterios de selección y verificación
  Última fecha de consulta
```

## Tono verbal

- Claro.
- Contextual.
- Documental.
- Preciso.
- No especulativo.
- Sensible al hablar de deterioro físico, adicción o salud emocional.
- Cuidadoso al distinguir la fecha de grabación de la fecha de publicación.

Ejemplos de frases:

- “Cada álbum registra un momento distinto de búsqueda.”
- “Una discografía organizada como archivo sonoro y visual.”
- “La obra solista permite leer cambios de sonido, cuerpo y contexto.”
- “El contexto de grabación se describe sólo cuando existen fuentes fiables.”
- “No se romantiza el deterioro: se documenta el contexto.”

Ejemplo de tono aplicado:

> Fuera de las estructuras de una banda y de las expectativas comerciales, la obra solista de John Frusciante funciona como un espacio de exploración e introspección. Cada álbum registra un momento distinto de su búsqueda y revela cambios en su relación con la música, la tecnología y la creación. Las reseñas distinguen entre lo que está documentado y lo que no puede afirmarse a partir del sonido.

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
- Color de acento para enlaces, fechas y navegación.
- Portadas en un formato consistente.
- Espacio suficiente entre álbumes para evitar saturación.
- Cada álbum presentado como una unidad independiente.
- Tracklists con enlaces de búsqueda precisos cuando no hay una edición oficial disponible en la plataforma.

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

- `--color-background` aporta una sensación de papel o archivo.
- `--color-text` mantiene una lectura clara.
- `--color-accent` distingue enlaces, fechas y navegación.
- `--font-title` identifica los títulos de álbumes.
- `--font-base` facilita la lectura de reseñas, tracklists y fuentes.

## Wireframe sugerido

```text
[ HERO ]
  Título
  Tagline
  Descriptor
  Navegación principal

[ CONTEXTO ]
  Introducción breve
  Alcance editorial
  Criterios para las reseñas

[ DISCOGRAFÍA ]
  Álbum
    Portada
    Título
    Fecha y formato
    Tracklist con duración y enlaces
    Reseña contextual

  Álbum
    Misma estructura repetida

[ FUENTES ]
  Referencias consultadas
  Criterios de verificación
  Última fecha de consulta
```

Ejemplo aplicado:

```text
[ HERO ]
  John Frusciante
  Discografía solista
  Un recorrido por el lado más íntimo del artista
  CTA: Explorar álbumes

[ CONTEXTO ]
  Presentación de la obra solista
  Alcance: 13 álbumes de estudio
  Nota sobre fuentes y reseñas contextuales

[ ÁLBUM ]
  Portada
  2009 · The Empyrean
  Fecha de publicación
  Tracklist con enlaces y duración
  Reseña sobre concepto y contexto documentado

[ ÁLBUM ]
  Misma estructura para cada álbum

[ FUENTES ]
  Referencias consultadas
  Criterios de selección y verificación
```

## Criterios de contenido

- Los álbumes aparecen del más reciente al más antiguo.
- Las duraciones corresponden a la edición estándar indicada.
- Los enlaces de cada track abren búsquedas precisas en Spotify para evitar grabaciones incorrectas entre reediciones regionales.
- *Smile from the Streets You Hold* no tiene una edición oficial disponible en Spotify.
- *. I :* fue publicado solamente en vinilo y no cuenta con una edición oficial completa en Spotify.
- Las portadas se guardan localmente en la carpeta `portadas/` y tienen un ancho mínimo de 1024 px.
- “Estado físico y emocional” se limita al contexto documentado de grabación o publicación.
- Cuando no existe información fiable sobre una condición física, se indica expresamente.
- No se diagnostica al artista a partir del sonido.
- En álbumes con grabaciones de varios años, se distingue el periodo de grabación del momento de publicación.

## Aprendizaje del ejemplo

Un sitio web no empieza con diseño visual. Empieza con una estructura clara de información.

Este ejemplo muestra cómo una colección extensa puede organizarse en Markdown mediante reglas consistentes. La información compartida por cada álbum permite convertir el contenido en bloques HTML repetibles; las diferencias de contexto conservan la singularidad de cada disco.

La estructura ayuda a separar datos, interpretación y fuentes. También hace visibles los límites de lo que se sabe: las reseñas pueden describir el contexto documentado, pero no deben inferir diagnósticos ni romantizar experiencias de deterioro.

## Fuentes y criterios de consulta

Las fuentes combinan catálogos discográficos, páginas de álbumes y reseñas contextuales. Se usan para verificar fechas, formatos, tracklists, disponibilidad y declaraciones del artista.

- [Discografía solista de John Frusciante](https://en.wikipedia.org/wiki/John_Frusciante_discography)
- [Catálogo de lanzamientos solistas · Invisible Movement](https://invisible-movement.net/discography/solo-releases)
- [I and II · información y tracklists](https://en.wikipedia.org/wiki/I_and_II)
- [Maya · Bandcamp oficial](https://johnfrusciante.bandcamp.com/album/maya)
- [Enclosure](https://en.wikipedia.org/wiki/Enclosure_(John_Frusciante_album))
- [PBX Funicular Intaglio Zone](https://en.wikipedia.org/wiki/PBX_Funicular_Intaglio_Zone)
- [The Empyrean](https://en.wikipedia.org/wiki/The_Empyrean)
- [Curtains](https://en.wikipedia.org/wiki/Curtains_(John_Frusciante_album))
- [Inside of Emptiness](https://en.wikipedia.org/wiki/Inside_of_Emptiness)
- [The Will to Death](https://en.wikipedia.org/wiki/The_Will_to_Death)
- [Shadows Collide with People](https://en.wikipedia.org/wiki/Shadows_Collide_with_People)
- [To Record Only Water for Ten Days](https://en.wikipedia.org/wiki/To_Record_Only_Water_for_Ten_Days)
- [Smile from the Streets You Hold](https://en.wikipedia.org/wiki/Smile_from_the_Streets_You_Hold)
- [Niandra LaDes and Usually Just a T-Shirt](https://en.wikipedia.org/wiki/Niandra_LaDes_and_Usually_Just_a_T-Shirt)
- [Maya · reseña contextual](https://pitchfork.com/reviews/albums/john-frusciante-maya/)
- [To Record Only Water for Ten Days · reseña retrospectiva](https://pitchfork.com/reviews/albums/john-frusciante-to-record-only-water-for-ten-days/)

**Última verificación indicada en el documento fuente:** 8 de septiembre de 2026.

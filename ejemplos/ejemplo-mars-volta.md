# Ejemplo: universo de The Mars Volta

## Música como mapa

**Tagline:** Nueve discos, nueve transformaciones, infinitas entradas.

**Descriptor:** Este ejemplo muestra cómo convertir una discografía compleja en una estructura navegable para fans y personas que entran por primera vez al universo de una banda.

## Objetivo

Construir una puerta de entrada al universo de The Mars Volta. El sitio debe presentar los álbumes de estudio en orden cronológico, pero sin convertirse en una lista plana.

## Información inicial

Entidades posibles:

- álbum;
- canción;
- etapa;
- personaje;
- concepto;
- género;
- setlist posible.

Atributos por álbum:

| Atributo | Función |
|---|---|
| Título | Identifica el álbum |
| Tagline | Sintetiza el carácter del disco |
| Historia / temática | Da contexto |
| Géneros | Ubica el sonido |
| Canciones posibles | Conecta con un setlist |
| Año | Orden cronológico |

## Intención comunicativa

Crear una entrada clara e intensa al universo de The Mars Volta, útil para quien no conoce la banda y atractiva para fans que reconocen referencias.

## Mapa de sitio

```text
Inicio
  Hero
  Qué es este universo
  Álbumes de estudio
  Canciones posibles en vivo
  Cierre / playlist
```

## Tono verbal

- Intenso.
- Críptico.
- Narrativo.
- Musical.
- Accesible para nuevos usuarios.

Ejemplos de frases:

- "Una guía para entrar sin perderse."
- "Cada disco abre una puerta distinta."
- "Del delirio narrativo al regreso expansivo."

## Tono visual

- Rojo, verde y negro.
- Alto contraste.
- Tipografía display para títulos.
- Cuerpo legible para descripciones.
- Bloques densos, pero navegables.

## Sistema visual posible

```css
:root {
  --color-background: #090909;
  --color-text: #f4f0e8;
  --color-accent: #d71920;
  --color-secondary: #1f6f43;

  --font-title: "Pirata One", serif;
  --font-base: system-ui, sans-serif;
}
```

## Wireframe sugerido

```text
[ HERO ]
  Título
  Tagline
  Descriptor
  CTA: Explorar álbumes

[ CONTEXTO ]
  Qué es este sitio

[ ÁLBUMES ]
  Álbum 1
  Álbum 2
  Álbum 3
  ...

[ SETLIST ]
  Canciones posibles

[ CIERRE ]
  Playlist / QR / actualización futura
```

## Aprendizaje del ejemplo

La discografía puede organizarse como recorrido. No todo debe estar en el hero. El sitio puede funcionar como mapa: una estructura que permite entrar, reconocer patrones y seguir explorando.


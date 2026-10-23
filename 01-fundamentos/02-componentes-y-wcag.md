# Componentes de la accesibilidad web y WCAG

**Origen:** presentaciones "1.2 Componentes de la accesibilidad web" y "4 Introducción a WCAG 2.0" (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0.

La accesibilidad web no depende solo de quien programa. Depende de varias piezas que tienen que funcionar juntas, y si una falla, las otras no alcanzan.

## Las piezas

- **Contenido.** Lo que se publica: texto, imágenes, sonido, código. Lo producen personas que redactan, diseñan y programan, incluidas personas con discapacidad y usuarios que aportan contenido.
- **Herramientas de autoría.** El software y los servicios con los que se crea ese contenido: editores, sistemas de gestión de contenidos, sitios donde las personas publican.
- **Herramientas de evaluación.** Los evaluadores de accesibilidad y los validadores de HTML y CSS.
- **Agentes de usuario.** Navegadores, reproductores de multimedia y otros programas que muestran el contenido.
- **Tecnologías de apoyo.** Lectores de pantalla, teclados alternativos, pulsadores, reconocimiento de voz.
- **Las personas usuarias**, con su conocimiento, su experiencia y, a veces, sus estrategias propias para usar la web.

Las piezas se necesitan entre sí. Si las herramientas de autoría no facilitan una función de accesibilidad y los navegadores no la soportan bien, es poco probable que alguien la implemente. Cuando los navegadores y las tecnologías de apoyo la soportan, la gente la pide y quienes desarrollan la implementan. Y cuando está en la mayoría del contenido, se exige todavía más soporte. El círculo puede ser virtuoso o vicioso (W3C, s. f.-b).

Cada pieza tiene su pauta del W3C. WCAG se ocupa del contenido y la usan quienes desarrollan, las herramientas de autoría y las de evaluación. ATAG se ocupa de las herramientas de autoría. UAAG, de los navegadores y reproductores, incluidos algunos aspectos de las tecnologías de apoyo. Para las aplicaciones con mucha interacción existe también WAI-ARIA (W3C, s. f.-b).

## Por qué existe WCAG

En la web básica, la accesibilidad es relativamente fácil de garantizar con estándares web: HTML y CSS. La web social trajo interfaces más ricas, con colaboración, redes sociales, actualizaciones en tiempo real y controles más complejos. Eso complicó los requisitos.

Los objetivos de WCAG 2.0 fueron durar en el tiempo, ser más fáciles de probar con precisión, más fáciles de usar y de entender, y servir para tecnologías más avanzadas y para distintas situaciones.

## Cómo está organizada

- **Cuatro principios:** perceptible, operable, comprensible y robusto. Están en `02-principios/`.
- **Pautas:** los objetivos básicos. WCAG 2.0 tiene 12. WCAG 2.1 sumó una pauta nueva, la 2.5 (entradas distintas del teclado), y llegó a 13.
- **Criterios de conformidad:** los requisitos concretos y verificables, cada uno con un nivel. A es el nivel mínimo, AA el intermedio y AAA el más exigente. Las normas suelen pedir A y AA; el decreto uruguayo, por ejemplo. Los nombres de los criterios en español de este repo son traducción propia, con el original en inglés entre paréntesis. La traducción al español de WCAG 2.0 es la de la Fundación Sidar.

| Versión | Pautas | Criterios | Qué cambió |
|---|---|---|---|
| WCAG 2.0 | 12 | 61 | Base de las presentaciones originales |
| WCAG 2.1 (junio de 2018) | 13 | 78 | Agregó 17 criterios: móvil, baja visión y accesibilidad cognitiva |
| WCAG 2.2 (octubre de 2023) | 13 | 86 | Agregó 9 criterios y eliminó el 4.1.1 |

Los totales de 2.1 y 2.2 se calcularon con los criterios que cada versión sumó y quitó (W3C, s. f.-d; s. f.-e). WCAG 3.0 sigue en borrador.

La ISO adoptó WCAG como norma ISO/IEC 40500. La edición de 2012 corresponde a WCAG 2.0 y, según el W3C, hoy la norma ISO/IEC 40500 es también WCAG 2.2 (W3C, s. f.-c).

## Un vistazo

| Principio | La idea en una línea |
|---|---|
| Perceptible | La información se puede percibir por más de un sentido: alternativas textuales, subtítulos, contenido adaptable, color y contraste. |
| Operable | Todo se maneja con teclado, hay tiempo suficiente, nada provoca convulsiones y hay ayudas para navegar. |
| Comprensible | El texto es legible, la página es predecible y se ayuda a evitar y corregir errores. |
| Robusto | El contenido funciona con navegadores y tecnologías de apoyo, actuales y futuros. |

## Actividad: ¿cómo usa la web una persona ciega?

La actividad original funcionaba en parejas. Una persona usa un lector de pantalla gratuito, NVDA, y solo el teclado (Tab y las flechas) para resolver una tarea concreta en un sitio: por ejemplo, averiguar a qué hora y a qué precio es una película mañana a la noche, y si se puede comprar en línea. La otra persona observa.

Tres ajustes para hoy:

1. **Elegí un sitio de demostración**, no el de una empresa real. Así no terminás evaluando a un tercero. El W3C ofrece una demostración con versiones accesibles e inaccesibles de las mismas páginas (W3C, s. f.-a).
2. **No uses vendas.** Estas técnicas no son simulaciones de discapacidad: no se puede recrear la situación exacta de una persona.
3. **Sumá a una persona usuaria real** de lector de pantalla, en vivo o en video.

## Nota sobre el original (2017)

La presentación 1.2 tenía un encabezado traducido del workshop del W3C WAI, una lista de componentes que sigue el documento "Essential Components of Web Accessibility", y un resumen de WCAG 2.0 que traducía el material del W3C. Lo propio era la actividad con el lector de pantalla. Lo que envejeció: los totales de pautas y criterios, que eran los de WCAG 2.0, y el nombre de la norma ISO, que figuraba como borrador ("DIS"). En el resumen del principio Operable se repetía por error el punto de los textos alternativos, que es de Perceptible. Esta versión conserva la actividad, explica las piezas con sus palabras y actualiza las cifras.

## Referencias

World Wide Web Consortium. (s. f.-a). *Before and after demonstration*. https://www.w3.org/WAI/demos/bad/

World Wide Web Consortium. (s. f.-b). *Essential components of web accessibility*. https://www.w3.org/WAI/fundamentals/components/

World Wide Web Consortium. (s. f.-c). *Introduction to web accessibility*. https://www.w3.org/WAI/fundamentals/accessibility-intro/

World Wide Web Consortium. (s. f.-d). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

World Wide Web Consortium. (s. f.-e). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

---

← [Introducción a la accesibilidad web](01-introduccion.md) · [Índice](../README.md) · [Siguiente: Diseño universal y accesibilidad web](03-diseno-universal.md) →

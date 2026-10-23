# Principio 2: Operable

**Origen:** presentación "Accesibilidad web por principios, Principio 2: Operable" (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que sumaron WCAG 2.1 y 2.2 está en la última sección.

Si la interfaz te exige algo que no podés hacer, no la podés usar. Operable quiere decir que los controles y la navegación se pueden manejar con las capacidades y las herramientas que cada persona tiene. El texto oficial de cada criterio no está copiado acá: está en las páginas del W3C que se citan al final.

## Pauta 2.1: accesible por teclado

Todo lo que se hace con el mouse tiene que poder hacerse con el teclado. No es un detalle: si algo funciona con teclado, funciona también con teclados adaptados, con comandos de voz y con otras tecnologías de apoyo. Lo necesitan las personas ciegas, quienes tienen baja visión y pierden el puntero en la pantalla, quienes tienen dificultades motrices y cualquiera que no tenga un mouse a mano.

- Usá enlaces y controles de formulario estándar de HTML. Traen el comportamiento de teclado resuelto.
- Sin trampas: si el foco entra a un componente con el teclado, tiene que poder salir con el teclado.

Una prueba simple: dejá el mouse a un costado y recorré tu sitio con Tab, Mayús+Tab, Enter y las flechas. ¿Llegás a todo? ¿Se ve dónde estás?

## Pauta 2.2: tiempo suficiente

La gente necesita tiempo para reaccionar, leer, completar un formulario y encontrar lo que busca. Cuando hay un límite de tiempo, la persona tiene que poder apagarlo, ajustarlo o extenderlo. Hay excepciones: los eventos en tiempo real, como una subasta, y los casos en que el tiempo es esencial.

Lo que se mueve, parpadea, se desplaza o se actualiza solo, y acompaña a otro contenido, tiene que poder pausarse, detenerse u ocultarse. Un carrusel que no para es el ejemplo de manual.

Y si una sesión autenticada vence, la persona tiene que poder volver a ingresar y seguir sin perder lo que había hecho.

## Pauta 2.3: convulsiones

No se diseña contenido que se sepa que puede provocar convulsiones. La regla central es que nada destelle más de tres veces por segundo, salvo por debajo de los umbrales de destello general y de destello rojo. Las advertencias no alcanzan: pueden no verse, sobre todo en el caso de los niños.

A partir de WCAG 2.1 esta pauta se llama "Seizures and Physical Reactions" (convulsiones y reacciones físicas), porque se sumó un criterio sobre animaciones que mareen o produzcan malestar.

## Pauta 2.4: navegable

Ayudar a encontrar el contenido, a saber dónde se está y a moverse.

- Un enlace "saltar al contenido principal" al comienzo evita recorrer el menú entero en cada página.
- El título de la página dice de qué trata.
- El orden en que el teclado recorre los elementos respeta el sentido de la página.
- "Click aquí" y "leer más" no dicen nada si se leen sueltos. Un enlace tiene que decir adónde lleva.
- Hay más de una forma de llegar a una página: buscador, mapa del sitio, enlaces relacionados.
- Los encabezados y las etiquetas describen el tema.
- El foco del teclado se ve.
- En el nivel AAA: indicar dónde estás, con migas de pan y destacando la sección actual en el menú.

## Qué sumaron WCAG 2.1 y 2.2 en este principio

**WCAG 2.1** agregó una pauta nueva, la 2.5 (Input Modalities, entradas distintas del teclado), y estos criterios:

| Criterio | Nivel | En pocas palabras |
|---|---|---|
| 2.1.4 Atajos con teclas de caracteres | A | Si hay atajos de una sola tecla, que se puedan desactivar, reasignar o que solo funcionen con el foco en el componente |
| 2.2.6 Tiempos de espera (Timeouts) | AAA | Avisar cuánta inactividad puede hacer perder datos |
| 2.3.3 Animación a partir de interacciones | AAA | Que la animación de movimiento disparada por una interacción se pueda desactivar |
| 2.5.1 Gestos con el puntero | A | Los gestos de varios puntos o de trayectoria, como pellizcar o deslizar, tienen una alternativa con un solo toque |
| 2.5.2 Cancelación del puntero | A | No ejecutar una acción al apretar; permitir cancelarla o deshacerla |
| 2.5.3 Etiqueta en el nombre | A | El nombre accesible incluye el texto visible, para que funcionen los comandos de voz |
| 2.5.4 Activación por movimiento | A | Lo que se activa sacudiendo o moviendo el dispositivo tiene una alternativa y se puede desactivar |
| 2.5.5 Tamaño del objetivo | AAA | Objetivos de al menos 44 por 44 píxeles CSS |
| 2.5.6 Mecanismos de entrada concurrentes | AAA | No restringir las formas de entrada disponibles en la plataforma |

**WCAG 2.2** sumó estos cinco:

| Criterio | Nivel | En pocas palabras |
|---|---|---|
| 2.4.11 Foco no oculto, mínimo (Focus Not Obscured, Minimum) | AA | El elemento con foco no queda totalmente tapado por contenido del autor, como un banner fijo |
| 2.4.12 Foco no oculto, mejorado (Enhanced) | AAA | Ninguna parte del elemento con foco queda tapada |
| 2.4.13 Apariencia del foco (Focus Appearance) | AAA | Indicador de foco con tamaño y contraste suficientes (al menos 3:1) |
| 2.5.7 Movimientos de arrastre (Dragging Movements) | AA | Lo que se hace arrastrando se puede hacer también con un solo toque, sin arrastrar |
| 2.5.8 Tamaño del objetivo, mínimo (Target Size, Minimum) | AA | Objetivos de al menos 24 por 24 píxeles CSS, con excepciones (espaciado, equivalente, en línea, controlado por el navegador, esencial) |

## Para seguir

- Qué cambió en WCAG 2.1, con enlaces a la explicación de cada criterio: página "What's New in WCAG 2.1" del W3C (con versión en español).
- Qué cambió en WCAG 2.2: página "What's New in WCAG 2.2" del W3C (ver referencias).

## Nota sobre el original (2017)

La presentación reproducía en español el texto de cada criterio de WCAG 2.0 y sus beneficios, con consejos propios sobre teclado y navegación. Lo que envejeció: no incluye la pauta 2.5 de WCAG 2.1 ni los criterios de 2.2, y su guía de eventos de mouse y teclado quedó vieja. También tenía errores de copia: repetía como primer punto de Operable el de textos alternativos, que pertenece a Perceptible, y varias diapositivas llevaban en el encabezado la pauta 1.1 en lugar de la 2.x.

## Referencias

World Wide Web Consortium. (s. f.-a). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

World Wide Web Consortium. (s. f.-b). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

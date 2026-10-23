# Principio 1: Perceptible

**Origen:** presentación "Accesibilidad web por principios, Principio 1: Perceptible" (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que sumaron WCAG 2.1 y 2.2 está en la última sección.

Si una persona no puede percibir la información, para ella no existe. De eso se trata este principio: lo que mostramos tiene que poder percibirse por más de un sentido, para que nadie quede afuera porque no ve, no oye o no distingue lo que le presentamos.

Abajo, para cada pauta: la idea, un ejemplo y dónde seguir. El texto oficial de cada criterio no está copiado acá. Está en las páginas "Understanding" del W3C, que se enlazan desde las páginas "What's New" citadas al final, y conviene leerlo allá.

## Pauta 1.1: alternativas textuales

Todo lo que no es texto y tiene un propósito necesita un equivalente en texto. Así lo puede leer un lector de pantalla, ampliar, traducir, pasar a braille o simplificar. Un buen texto alternativo dice qué función cumple la imagen. No la describe como un catálogo.

Probá con este ejercicio. Tenés la foto de una niña escuchando música en una radio, ilustrando una nota sobre radios comunitarias. ¿Cuál de estos textos alternativos elegís?

- "Niña escuchando música en una radio": dice qué hay y alcanza en este contexto.
- "Imagen 344": no dice nada.
- "Ingrese el texto alternativo aquí": es el texto de la plantilla, que nadie cambió. Es un error real y se puede evitar.

Si la misma foto fuera un adorno, no llevaría texto alternativo. Cada caso depende de qué hace la imagen en la página.

Casos que conviene tener presentes:

- **Decoración** (viñetas, adornos): no aporta información. Lo mejor es ponerla desde la hoja de estilos; si no se puede, con alt vacío (`alt=""`).
- **Gráficos con datos:** un texto alternativo corto y una descripción larga cerca de la imagen, o en un enlace inmediato.
- **Controles y campos de formulario:** tienen un nombre que dice para qué sirven, por ejemplo con una etiqueta (`label`).
- **Pruebas y experiencias sensoriales** (un test de audición, un concierto, una obra de arte): al menos una identificación que diga de qué se trata.
- **CAPTCHA:** ofrecé más de una forma de resolverlo y una vía con atención humana. Y mejor todavía: no se lo pidas a usuarios ya autorizados. WCAG 2.2 sumó criterios de autenticación accesible (3.3.8 y 3.3.9).

## Pauta 1.2: medios que dependen del tiempo

Audio, video, o ambos. Cada alternativa sirve a personas distintas:

- **Transcripción:** todo el contenido sonoro y visual relevante, en texto.
- **Subtítulos:** el sonido que hace falta para entender, no solo el diálogo. Incluye música, risas, efectos y quién habla. Sirven a personas sordas o con dificultades para oír.
- **Audiodescripción:** una narración que cuenta lo que se ve y no se entiende solo escuchando. Sirve a personas ciegas o con baja visión.
- **Lengua de señas.**

Los subtítulos pueden ser ocultos (se prenden y apagan) o abiertos (siempre visibles).

Qué pide cada nivel (A, AA, AAA), en grabado y en directo, es fácil de perder. Olga Carreras tiene una tabla resumen muy clara de los requisitos de accesibilidad para los medios tempodependientes, a la que remitía la presentación original (Carreras Montoto, 2012).

## Pauta 1.3: adaptable

La información tiene que poder presentarse de otras formas sin perder estructura: por voz, en braille, sin estilos, solo texto. Para eso hay que marcar el contenido por lo que significa y no por cómo se ve.

Una receta, por ejemplo:

```html
<h1>Recetas de cocina</h1>
  <h2>Pascualina</h2>
    <h3>Ingredientes</h3>
      <ul>
        <li>Masa</li>
        <li>Acelga</li>
      </ul>
    <h3>Preparación</h3>
      <ol>
        <li>Poner la masa en la asadera.</li>
        <li>Poner la acelga.</li>
        <li>Llevar al horno.</li>
      </ol>
```

Los títulos son títulos, las listas son listas, las tablas de datos tienen celdas de encabezado. Y no se usa una etiqueta solo porque "se ve así".

Dos cosas más:

- **Orden de lectura.** Lo que se lee en el código es lo que escucha una persona con lector de pantalla. No reordenes con CSS algo que cambie el sentido.
- **Características sensoriales.** "Presioná el botón de la derecha" o "el botón redondo" no le sirve a quien no ve la pantalla. Mejor nombrá el botón: "Siguiente".

Para entender la idea de separar contenido y presentación, el CSS Zen Garden es un buen ejercicio: el mismo contenido con distintos diseños.

## Pauta 1.4: distinguible

Que lo que se muestra se pueda ver y oír, y que el primer plano se separe del fondo.

- **Color.** "Los campos marcados en rojo son obligatorios" no alcanza. Sumá texto o un símbolo. Hay personas con dificultades para distinguir colores, pantallas monocromo y usuarios de braille.
- **Contraste.** El texto normal necesita una relación de contraste de al menos 4,5:1 con el fondo; el texto grande, 3:1. Hay excepciones: decoración, logos, componentes inactivos.
- **Tamaño del texto.** Tiene que poder agrandarse hasta un 200% sin perder contenido ni funciones.
- **Imágenes de texto.** Siempre que se pueda, usá texto real.
- **Audio automático.** Si suena solo más de 3 segundos, tiene que poder pausarse o detenerse.

El nivel AAA pide más: contraste de 7:1 y reglas de presentación del texto (ancho de línea, interlineado).

## Qué sumaron WCAG 2.1 y 2.2 en este principio

**WCAG 2.1** agregó estos criterios en el principio Perceptible:

| Criterio | Nivel | En pocas palabras |
|---|---|---|
| 1.3.4 Orientación (Orientation) | AA | El contenido no se limita a una sola orientación de pantalla (vertical u horizontal), salvo que sea esencial |
| 1.3.5 Identificar el propósito de los campos (Identify Input Purpose) | AA | El propósito de los campos que piden datos de la persona, como nombre o dirección, se puede determinar por software, así el navegador los completa solo |
| 1.3.6 Identificar el propósito (Identify Purpose) | AAA | El propósito de los componentes de interfaz, los íconos y las regiones se puede determinar por software |
| 1.4.10 Reajuste de elementos (reflow) | AA | El contenido se adapta sin perder información ni exigir scroll en dos dimensiones, a un ancho equivalente a 320 píxeles CSS (contenido de desplazamiento vertical) |
| 1.4.11 Contraste de elementos no textuales (Non-Text Contrast) | AA | Contraste de al menos 3:1 en los componentes de interfaz y en las partes de un gráfico necesarias para entenderlo |
| 1.4.12 Espaciado del texto (Text Spacing) | AA | El contenido aguanta que la persona aumente interlineado (1,5 veces la fuente), espacio entre párrafos (2 veces), entre letras (0,12) y entre palabras (0,16) |
| 1.4.13 Contenido al pasar el cursor o al enfocar (Content on Hover or Focus) | AA | Lo que aparece al pasar o enfocar se puede cerrar sin mover el foco ni el cursor, no desaparece si se mueve el cursor sobre ese contenido y permanece hasta que se lo descarta |

**WCAG 2.2** no agregó criterios en este principio. Los nueve nuevos están en Operable y Comprensible (W3C, s. f.-b).

## Para seguir

- Texto oficial y explicación de cada criterio: Understanding WCAG 2.2 (W3C).
- Qué cambió entre versiones: las páginas "What's New" de W3C, con enlaces a la explicación de cada criterio (ver referencias). La de WCAG 2.1 tiene versión en español.
- Olga Carreras: tabla resumen de requisitos de accesibilidad para los medios tempodependientes (ver referencias).

## Nota sobre el original (2017)

La presentación seguía el texto de WCAG 2.0 criterio por criterio, con beneficios y ejemplos tomados de los documentos "Understanding" del W3C, y sumaba ejercicios propios: elegir el texto alternativo de una imagen y el CSS Zen Garden. Lo que envejeció: no cubre los criterios de WCAG 2.1, usaba el atributo `longdesc` y sus herramientas de contraste eran de 2017. Esta versión conserva los ejercicios, reescribe los ejemplos y no copia el texto oficial.

## Referencias

Carreras Montoto, O. (2012, 28 de agosto). *Tabla resumen de los requisitos de accesibilidad para los medios tempodependientes según las WCAG 2.1* [Entrada de blog]. Usable y accesible. https://olgacarreras.blogspot.com/2012/08/tabla-resumen-de-los-requisitos-de.html

World Wide Web Consortium. (s. f.-a). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

World Wide Web Consortium. (s. f.-b). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

---

← [Costos y beneficios de la accesibilidad](../01-fundamentos/05-costos-y-beneficios.md) · [Índice](../README.md) · [Siguiente: Principio 2: Operable](02-operable.md) →

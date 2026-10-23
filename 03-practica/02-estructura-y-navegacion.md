# Estructura de página y navegación

**Origen:** presentaciones "2.5 Estructura de página accesible" y "2.6 Navegación y orientación de sitios accesibles" (2017), de Silvia Da Rosa, unidas en un solo archivo porque se superponían entre sí y con los principios Perceptible y Operable.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que sumaron WCAG 2.1 y 2.2 está más abajo.

Una página bien estructurada se recorre y se entiende más rápido, con lector de pantalla, con teclado o con el modo lectura del celular. Según el W3C, eso ayuda a personas con discapacidades cognitivas y de aprendizaje a encontrar y priorizar el contenido, a quienes usan lector de pantalla a saltar al contenido principal, y a quienes tienen baja visión les da pistas de orientación. También a los buscadores (W3C, s. f.-a).

## Estructura de la página

- **Regiones.** Marcá las zonas de la página por lo que son: cabecera, navegación, contenido principal, pie. Con eso, la tecnología de apoyo puede listar las regiones y llevar a cada una. Si hay dos del mismo tipo, por ejemplo dos menús, ponele a cada una una etiqueta que las distinga (W3C, s. f.-a).
- **Encabezados.** Reflejan cómo está organizada la página y se anidan con lógica: un encabezado principal y debajo los de segundo nivel, y así. No se eligen por el tamaño que tienen en pantalla.
- **Estructura del contenido.** Párrafos, listas, tablas con celdas de encabezado, énfasis y citas, cada uno con su elemento. Los ejemplos están en la pauta 1.3 de `02-principios/01-perceptible.md`.
- **Orden de lectura y del foco.** Lo que se lee en el código es lo que escucha una persona con lector de pantalla, y es el orden en que el teclado recorre la página. No lo cambies con CSS si altera el sentido.
- **Saltar bloques repetidos.** Un enlace al comienzo que lleve al contenido principal evita que quien navega con teclado atraviese todo el menú en cada página.
- **Tabla de contenidos.** En una página larga, ayuda a moverse entre secciones.

## Navegación y orientación

- **Títulos de página** que digan de qué trata.
- **Enlaces que se entienden solos.** "Click aquí" y "leer más" no dicen nada si se leen sueltos, como los lee un lector de pantalla cuando lista los enlaces. Mejor: "Leer más sobre los costos de la accesibilidad".
- **Más de una vía** para llegar a una página: buscador, mapa del sitio, enlaces relacionados.
- **Navegación consistente.** Los menús y los componentes con la misma función aparecen siempre igual.
- **Orientación.** Migas de pan y destacar la sección actual en el menú le dicen a la persona dónde está.

## Menús y enlaces hechos con scripts

Los problemas más comunes aparecen cuando un menú o un enlace se arma con scripts en lugar de con elementos estándar. El W3C documenta como fallos de WCAG los scripts que emulan enlaces sin que se puedan determinar por software (F42) y los formularios que se envían solos y cargan contenido nuevo sin avisar (F36). Para menús, el tutorial de WAI explica cómo armarlos con una estructura sencilla, con estilos y con desplegables (W3C, s. f.-b).

## Ejercicio

Elegí un sitio que uses seguido y respondé: ¿se puede llegar a todo con el teclado? ¿Se ve dónde está el foco? ¿Hay un enlace para saltar el menú? ¿El título de la pestaña dice de qué trata la página? ¿Sabés en qué sección estás?

## Qué cambió desde 2017

- Los criterios de navegación de WCAG 2.0 siguen casi iguales en WCAG 2.2 (W3C, s. f.-c).
- WCAG 2.2 sumó el 2.4.11 (Focus Not Obscured, Minimum): el elemento con foco no puede quedar totalmente tapado por contenido del autor. Un encabezado o un banner fijo que tapa lo que el teclado está enfocando es el caso típico.
- WCAG 2.2 sumó el 3.2.6 (Consistent Help): si la ayuda aparece en varias páginas, está siempre en el mismo orden relativo.
- WCAG 2.2 sumó el 2.5.8 (Target Size, Minimum): los enlaces y botones del menú no pueden ser demasiado chicos.

## Nota sobre el original (2017)

Las dos presentaciones reproducían el texto de WCAG 2.0 en español y seguían la agenda de las sesiones de estructura de página y de navegación del workshop de WAI. Lo propio eran los ejemplos de enlaces ("click aquí", "leer más"), el ejemplo de la receta y los ejercicios. Esta versión conserva eso, no copia el texto oficial y suma lo que agregó WCAG 2.2.

## Referencias

World Wide Web Consortium. (s. f.-a). *Page structure tutorial*. https://www.w3.org/WAI/tutorials/page-structure/

World Wide Web Consortium. (s. f.-b). *Menus tutorial*. https://www.w3.org/WAI/tutorials/menus/

World Wide Web Consortium. (s. f.-c). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

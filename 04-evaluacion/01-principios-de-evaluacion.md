# Evaluación de accesibilidad

**Origen:** presentación "Evaluación de accesibilidad" (2021) y checklist de apoyo (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. La plantilla que acompaña este archivo cubre WCAG 2.2, niveles A y AA, el criterio 4.1.1 de WCAG 2.1 y siete criterios AAA que pedía el anexo de 2022 del decreto uruguayo.

Evaluar la accesibilidad no es pasar un escáner. Es combinar herramientas, revisión manual y personas. Y hay una frase que resume todo el tema: cumplir las pautas no es lo mismo que ser accesible.

## Cuatro formas de evaluar

- **Automática.** Herramientas que revisan ciertos aspectos. Es objetiva, rápida y barata, pero incompleta: hay aspectos que no se pueden automatizar, y aparecen falsos positivos y falsos negativos. Usá al menos dos herramientas.
- **Manual.** Con herramientas de apoyo y una lista de verificación. La plantilla de este repo es esa lista.
- **Técnicas de filtrado.** Limitar una habilidad o usar una tecnología de apoyo para detectar barreras: lentes, guantes gruesos, un lector de pantalla. No evalúan conformidad con las pautas, detectan barreras. Y no son simulaciones de discapacidad: no se puede recrear la situación exacta de una persona.
- **Pruebas con usuarios.** Personas con discapacidad usando el sitio. Muestran lo que ninguna lista encuentra.

## Verificaciones manuales que conviene hacer siempre

El W3C tiene una guía de revisiones sencillas que cubre buena parte de esta lista (W3C, s. f.-a).

- **Imágenes:** que los textos alternativos sean adecuados, que las decorativas estén bien resueltas, que las imágenes de texto repitan el texto y que las que son enlaces digan adónde van.
- **Multimedia:** que lo que se dice en el audio tenga subtítulos.
- **Color:** mirá la página sin estilos y fijate si toda la información se entiende sin depender del color.
- **Contraste:** que el texto se distinga del fondo según su tamaño.
- **Teclado:** recorré la página con Tab. ¿Llegás a todo? ¿Se ve dónde está el foco? ¿El orden es lógico? ¿Hay algún lugar donde te trabás?
- **Ampliar:** subí el texto hasta un 200% y comprobá que no se desarma ni obliga a hacer scroll horizontal para leer una línea.
- **Encabezados y listas:** los títulos, y solo los títulos, son encabezados; los grupos de tres o más elementos son listas.
- **Título de la página:** corto, único dentro del sitio y comprensible fuera de contexto.
- **Múltiples vías:** buscador o mapa del sitio.
- **Carruseles y deslizadores:** que se puedan parar, pausar y reiniciar.
- **Destellos y sonido de fondo:** nada que destelle de forma peligrosa, y ruido o música que no tapen la voz.
- **Legibilidad:** principalmente, sentido común.

## Probar, probar, probar

Navegá sin imágenes, sin sonido, con el texto agrandado, en escala de grises y sin CSS. Probá en distintos navegadores, sistemas operativos y dispositivos, y con una conexión lenta. Y una vez, con el monitor apagado y un lector de pantalla.

Verificá qué herramientas y qué versiones de lectores de pantalla siguen vigentes antes de recomendarlas. El W3C mantiene una lista de herramientas de evaluación y una guía para elegirlas (W3C, s. f.-b; s. f.-c).

## Cumplir las pautas no es lo mismo que ser accesible

Un contenido puede cumplir todas las pautas, pasar todos los test automáticos y parecer accesible, y seguir teniendo barreras. Entonces:

- El objetivo no es cumplir pautas. Es ser accesible.
- Las pautas son una herramienta para llegar ahí.
- Hacen falta pruebas manuales y pruebas con usuarios.
- Tiene que haber un contacto para que quien use el sitio pueda reportar las barreras que encuentre.

## Metodología oficial

El W3C publica una metodología para determinar qué tan bien un producto digital cumple con WCAG: WCAG-EM. Propone cinco pasos: definir el alcance de la evaluación, explorar el producto, elegir una muestra representativa, evaluar esa muestra e informar los resultados. También recomienda involucrar a personas usuarias con discapacidad durante la evaluación. La versión 2 se publicó el 23 de julio de 2026 y se aplica también a aplicaciones y otros productos digitales; la versión 1 era solo para sitios web (W3C, s. f.-d).

Para organismos públicos uruguayos, AGESIC publicó en septiembre de 2026 una guía para la evaluación de la accesibilidad digital con base en WCAG 2.2. Cubre la preparación de la evaluación, la muestra representativa, la evaluación automática y manual, las pruebas con personas usuarias y el registro de hallazgos (Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento [AGESIC], 2026a). También publicó una herramienta de evaluación en planilla (AGESIC, 2026b).

Antes de aplicar una metodología completa conviene hacer una revisión rápida. El W3C tiene una guía de revisiones sencillas con las verificaciones más comunes (W3C, s. f.-a).

## Qué cambió desde 2021

- **Más criterios.** La plantilla suma los criterios de WCAG 2.1 y 2.2 de nivel A y AA que el original no tenía. Para evaluar el reajuste de elementos (reflow), por ejemplo, hay que probar el contenido a un ancho de 320 píxeles CSS sin scroll en dos dimensiones, y también ampliar el texto.
- **Procesamiento (4.1.1).** WCAG 2.2 lo eliminó, así que validar el HTML y el CSS ya no es un requisito de conformidad. Sigue siendo una buena práctica de calidad del código.
- **Herramientas.** Las del original son de 2017 a 2021 y no se incluyen.

## Plantilla

`plantilla-evaluacion-wcag22.xlsx` tiene 63 filas: los 55 criterios de nivel A y AA de WCAG 2.2, el 4.1.1 (Procesamiento), que WCAG 2.2 eliminó pero que sigue vigente en WCAG 2.1, y siete criterios de nivel AAA. Una columna marca con "Sí" los 55 criterios de nivel A y AA de WCAG 2.2, que es el punto de partida que fija AGESIC desde septiembre de 2026. El 4.1.1 y los siete criterios AAA del anexo de 2022 quedan marcados con "No", pero se conservan (ver `01-fundamentos/04-marco-normativo-uruguay.md`). Trae columnas para el resultado, la evidencia, cómo se verificó y observaciones, y una hoja de resumen que cuenta los resultados para toda la lista y para los criterios del decreto. No reproduce el texto de los criterios: está en la Recomendación del W3C (W3C, 2023).

## Nota sobre el original (2021)

La presentación era tuya de punta a punta: las cuatro formas de evaluar, las verificaciones manuales y la idea de que cumplir no es ser accesible. Lo que envejeció: sus herramientas, que eran de su época; los ejemplos con un personaje de historieta y fotos de Flickr, que acá se reemplazaron por texto; y la recomendación de validar el código como parte de WCAG 2.0, que cambió con la eliminación del 4.1.1. El checklist de 2017 reproducía el texto de WCAG 2.0 y solo cubría esa versión; la plantilla nueva lo reemplaza.

## Referencias

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026a, 8 de septiembre). *Guía para la evaluación de la accesibilidad digital* (cap. 2, Marco de referencia y nivel de conformidad). https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/guia-para-evaluacion-accesibilidad-digital/guia-para-evaluacion-3

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026b, 1 de septiembre). *Herramienta para la evaluación de accesibilidad digital*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/herramienta-para-evaluacion-accesibilidad-digital

World Wide Web Consortium. (s. f.-a). *Easy checks: A first review of web accessibility*. https://www.w3.org/WAI/test-evaluate/preliminary/

World Wide Web Consortium. (s. f.-b). *List of evaluation tools*. https://www.w3.org/WAI/test-evaluate/tools/list/

World Wide Web Consortium. (s. f.-c). *Selecting evaluation tools*. https://www.w3.org/WAI/test-evaluate/tools/selecting/

World Wide Web Consortium. (s. f.-d). *WCAG-EM overview: WCAG evaluation methodology*. https://www.w3.org/WAI/test-evaluate/conformance/wcag-em/

World Wide Web Consortium. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. https://www.w3.org/TR/WCAG22/

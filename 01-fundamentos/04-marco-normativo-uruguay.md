# Marco normativo en Uruguay

**Origen:** artículo "Normas UNIT" (2019) y presentación de evaluación (2021), de Silvia Da Rosa, actualizados con fuentes oficiales.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. El anexo del decreto (2022) refería a WCAG 2.1; las publicaciones de AGESIC de septiembre de 2026 refieren a WCAG 2.2.

Esto es un mapa, no asesoramiento legal. Para una obligación concreta, leé el texto del decreto y consultá a quien corresponda.

## La ley y el decreto

- **Ley 19.924, artículo 88.** El Estado, los gobiernos departamentales, los entes autónomos, los servicios descentralizados y las personas de derecho público no estatales deben asegurar la accesibilidad de los contenidos web según las normas, requisitos y exigencias técnicas que recomiende AGESIC, tomando como referencia las recomendaciones del W3C-WAI. AGESIC asesora a los organismos y ejerce el contralor (Centro de Información Oficial [IMPO], 2020).
- **Decreto 406/022**, del 22 de diciembre de 2022, reglamenta ese artículo (IMPO, 2020). Según AGESIC, consolidó el marco nacional y estableció criterios obligatorios de accesibilidad para los sitios web, las aplicaciones móviles y los documentos digitales de los organismos públicos (Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento [AGESIC], 2026a).
- **El anexo de 2022.** El decreto incluye un anexo, "Requisitos técnicos de accesibilidad" (versión 1, abril de 2022), basado en WCAG 2.1. Pide alcanzar los niveles A y AA y cumplir siete criterios de nivel AAA: 1.4.6 (contraste aumentado), 1.4.8 (presentación visual), 2.2.6 (límites de tiempo), 2.4.8 (ubicación), 2.4.10 (encabezados de sección), 2.5.5 (tamaño del área de interacción) y 3.2.5 (cambio a petición) (Poder Ejecutivo, 2022). Los lineamientos de AGESIC para armar el plan de mejora hablan de 57 criterios requeridos, que corresponden a esa versión: 50 de A y AA y siete de AAA (AGESIC, s. f.-a).
- **Los requisitos se actualizan.** El artículo 3 del decreto encarga a AGESIC actualizar el elenco de requisitos de forma periódica (Poder Ejecutivo, 2022). En septiembre de 2026, AGESIC publicó una guía para la evaluación de la accesibilidad digital que toma WCAG 2.2 como referencia y fija como mínimo el nivel AA, sin perjuicio de que puedan sumarse criterios adicionales (AGESIC, 2026b). Publicó además una herramienta de evaluación para WCAG 2.2 (AGESIC, 2026c) y un modelo de declaración de accesibilidad que habla de los niveles A y AA de WCAG 2.2 (AGESIC, 2026d). Su libro en línea de requisitos técnicos tiene un capítulo de nivel AA con WCAG 2.2 en el título (AGESIC, s. f.-c). No pude leer un texto que derogue el anexo de 2022 ni que fije la lista completa vigente, así que conviene confirmarlo en el sitio de AGESIC.
- **Alcance del requisito.** Según el anexo de 2022, comprende sitios web, intranets, servicios y aplicaciones web y móviles, trámites, aplicaciones de uso interno y documentos en cualquier formato. El nivel se aplica a páginas y procesos completos: si un proceso tiene varias páginas, todas tienen que ser accesibles (Poder Ejecutivo, 2022).
- **Declaración de accesibilidad.** Según el modelo de AGESIC, se completa después de evaluar los requisitos y se publica en formato HTML en el pie del producto digital. Incluye el nivel de cumplimiento, la fecha y un canal de contacto para comunicar barreras, y el compromiso de revisar la accesibilidad cada seis meses (AGESIC, 2026d).
- **Rol de AGESIC.** Define los requisitos técnicos, asesora a los organismos que lo piden, ejerce el contralor y reconoce públicamente a quienes cumplen (AGESIC, s. f.-b).

## Qué significa en la práctica

- Para un organismo público, según AGESIC (septiembre de 2026), el punto de partida es WCAG 2.2, niveles A y AA: 55 criterios, 31 de nivel A y 24 de nivel AA. El criterio 4.1.1 (Procesamiento) ya no cuenta, porque WCAG 2.2 lo eliminó. La plantilla de `04-evaluacion/` marca esos 55.
- El anexo de 2022 pedía además siete criterios de nivel AAA. La plantilla los conserva, marcados como no exigidos hoy, por si tenés que evaluar contra esa versión.
- El artículo 88 alcanza a organismos públicos. Para el sector privado no encontré una obligación equivalente en lo que revisé.

## Normas UNIT sobre accesibilidad web

| Norma | De qué trata |
|---|---|
| UNIT 1215-1:2014 | Características que debe cumplir la información y otros contenidos web para que puedan usarlos la mayor cantidad de personas, incluidas las personas con discapacidad y las personas mayores (Instituto Uruguayo de Normas Técnicas [UNIT], s. f.-b) |
| UNIT 1215-2:2016 | Requisitos de un sistema de gestión de accesibilidad web, para mantener la accesibilidad de un sitio a lo largo del tiempo (UNIT, s. f.-b) |
| UNIT 1223:2015 | Accesibilidad de las herramientas de autor de contenidos web |
| UNIT 1229:2016 | Subtitulado de contenido audiovisual para personas sordas e hipoacúsicas |
| UNIT 1280:2022 | Lectura fácil: requisitos y recomendaciones para la elaboración de documentos |
| UNIT-ISO/IEC TS 20071-11:2012 | Guía sobre textos alternativos para imágenes (no es gratuita) |
| UNIT-ISO/IEC TS 20071-21:2015 | Guía sobre audiodescripciones (no es gratuita) |

Silvia Da Rosa, autora de este repo, integró, a título voluntario, el Comité Técnico de Accesibilidad Web de UNIT. Según el catálogo de UNIT, las normas 1215-1, 1215-2, 1223, 1229 y 1280 figuran como vigentes y de descarga gratuita, y las dos guías ISO/IEC TS 20071 figuran como disponibles, sin ser gratuitas (UNIT, s. f.-a). Según UNIT, las normas 1215 se basan en las pautas de WCAG 2.0, y UNIT otorgó en 2014 la primera certificación de accesibilidad web a un portal del Estado, tramites.gub.uy (UNIT, s. f.-b). Los títulos y años de la tabla se verificaron contra ese catálogo en octubre de 2026.

Las normas no se copian en este repo. Se enlazan desde el catálogo de UNIT.

## Una norma con número parecido

La norma **UNIT 200** trata de la accesibilidad de las personas al medio físico: criterios y requisitos de diseño para un entorno edificado accesible. No es una norma web. Según el catálogo de UNIT, la edición vigente es la 200:2022, de descarga gratuita (UNIT, s. f.-a). Se menciona para que no se confunda con las de contenido web.

## Normas internacionales

WCAG 2.0 se publicó también como norma ISO/IEC 40500:2012. Las normas UNIT 1215 se alinean con esa versión. Según el W3C, la norma ISO/IEC 40500 corresponde hoy a WCAG 2.2 (W3C, s. f.). En Europa rige otra norma, la EN 301 549, de requisitos de accesibilidad para productos y servicios TIC. Según Accessibilitas, en septiembre de 2026 se publicó una nueva versión que incorpora los requisitos de WCAG 2.2 y elimina el criterio 4.1.1 (Accessibilitas, 2026).

## Medios audiovisuales

La accesibilidad de la televisión tiene su propia ley. La Ley 19.307, de servicios de comunicación audiovisual, reconoce el derecho de las personas con discapacidad a la accesibilidad a esos servicios (art. 35). También obliga a la televisión abierta y a los servicios para abonados a ofrecer parte de su programación con subtitulado, lengua de señas o audiodescripción (art. 36) (IMPO, 2014). El decreto 160/019 la reglamentó, y su artículo 24 trata la accesibilidad (IMPO, 2019). Esa ley se aplica a los servicios de comunicación audiovisual y no a los sitios web. Para los videos en la web valen los criterios 1.2 de WCAG (ver `02-principios/01-perceptible.md`).

## Nota sobre el original (2019)

El artículo "Normas UNIT" era una lista de enlaces a normas gratuitas. Lo que cambió: el Decreto 406/022 (2022) convirtió la accesibilidad de los contenidos web en una obligación para los organismos públicos, con WCAG 2.1 como referencia y, en 2026, con WCAG 2.2 según las publicaciones de AGESIC. Esta versión explica ese marco y deja los enlaces a las normas en `CREDITOS.md`.

## Referencias

Accessibilitas. (2026, septiembre). *Publicada la nueva versión de la norma europea de accesibilidad EN 301 549*. https://accessibilitas.es/2026/09/publicada-la-nueva-version-de-la-norma-europea-de-accesibilidad-en-301-549/

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (s. f.-a). *Lineamientos para plan de mejora de accesibilidad digital*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/sites/agencia-gobierno-electronico-sociedad-informacion-conocimiento/files/documentos/publicaciones/Lineamientos%20para%20plan%20de%20mejoras%20de%20accesibilidad%20digital.pdf

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (s. f.-b). *Programa de Accesibilidad en Entornos Digitales*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/accesibilidad-entornos-digitales

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (s. f.-c). *Requisitos técnicos de accesibilidad digital* (cap. 7, Criterios de conformidad WCAG 2.2 Nivel AA). https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/requisitos-tecnicos-accesibilidad-digital/requisitos-tecnicos-8

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2023, 7 de septiembre). *Guía para crear documentos digitales accesibles* [Noticia]. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/noticias/guia-para-crear-documentos-digitales-accesibles

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026a, 21 de mayo). *Día Mundial de la Concientización sobre Accesibilidad Digital: avances y desafíos hacia un Estado más inclusivo* [Noticia]. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/noticias/dia-mundial-concientizacion-sobre-accesibilidad-digital-avances-desafios

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026b, 8 de septiembre). *Guía para la evaluación de la accesibilidad digital* (cap. 2, Marco de referencia y nivel de conformidad). https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/guia-para-evaluacion-accesibilidad-digital/guia-para-evaluacion-3

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026c, 1 de septiembre). *Herramienta para la evaluación de accesibilidad digital*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/herramienta-para-evaluacion-accesibilidad-digital

Agencia de Gobierno Electrónico y Sociedad de la Información y del Conocimiento. (2026d, 14 de septiembre). *Modelo de declaración de accesibilidad digital*. https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/comunicacion/publicaciones/modelo-declaracion-accesibilidad-digital

Centro de Información Oficial. (2014). *Ley N.º 19.307: Regulación de la prestación de servicios de radio, televisión y otros servicios de comunicación audiovisual* (arts. 35 y 36). https://impo.com.uy/bases/leyes/19307-2014

Centro de Información Oficial. (2019). *Decreto N.º 160/019: Reglamentación de la Ley N.º 19.307* (art. 24). https://impo.com.uy/bases/decretos/160-2019/24

Centro de Información Oficial. (2020). *Ley N.º 19.924: Presupuesto nacional de sueldos, gastos e inversiones. Ejercicio 2020-2024* (art. 88). https://www.impo.com.uy/bases/leyes/19924-2020/88

Instituto Uruguayo de Normas Técnicas. (s. f.-a). *Normas disponibles sin costo*. https://www.unit.org.uy/normalizacion/normas/acc/

Instituto Uruguayo de Normas Técnicas. (s. f.-b). *UNIT publica las normas sobre accesibilidad web*. https://www.unit.org.uy/novedades/ver/normas_accesibilidad_web

Poder Ejecutivo. (2022). *Decreto N.º 406/022: Reglamentación del artículo 88 de la Ley N.º 19.924* (con su anexo "Requisitos técnicos de accesibilidad", versión 1, abril de 2022). Centro de Información Oficial. https://www.impo.com.uy/bases/decretos-originales/406-2022

World Wide Web Consortium. (s. f.). *Introduction to web accessibility*. https://www.w3.org/WAI/fundamentals/accessibility-intro/

---

← [Diseño universal y accesibilidad web](03-diseno-universal.md) · [Índice](../README.md) · [Siguiente: Costos y beneficios de la accesibilidad](05-costos-y-beneficios.md) →

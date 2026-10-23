# 1. Introducción a la accesibilidad web

> "El poder de la Web está en su universalidad. Un acceso a la Web para todos independientemente de su discapacidad es un aspecto esencial."
> Tim Berners-Lee (traducción propia; original en W3C, s. f.-b)

**Origen:** presentación "1.1 Introducción a la accesibilidad web" (2016, editada en 2018) y artículos "Superhumanos" y "Accesibilidad en la web" (LinkedIn, 2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que cambió en 2.1 y 2.2 se indica al final.

## ¿Para quién es la web?

La web es el sueño de los idealistas: un lugar donde una estudiante de Uruguay, un campesino de India y un empresario de Estados Unidos pueden acceder a la misma información, a la misma educación, a los mismos servicios. Ese es su fundamento. Universal, para todos, como la pensó Tim Berners-Lee.

Pero la verdad es que la web, como el resto del mundo, no siempre es para todos.

Quienes la construyen no siempre tienen en cuenta que esa estudiante puede ser ciega y usar un lector de pantalla. Que puede querer estudiar desde el celular mientras viaja en el ómnibus. Que puede ser una persona mayor con dificultades de visión y audición, o simplemente poco habituada a la web. Que puede ser un niño con la computadora que le dio la escuela y una conexión pobre.

Pensá qué hace falta para entrar a un sitio. Primero, una conexión a internet. Después, un dispositivo: computadora, tablet, celular. Después, saber usarlo. Y por último, tener ganas, reconocer que ahí hay algo que vale la pena.

Ahora agreguemos una condición más: que no haya barreras de accesibilidad. Que la persona pueda entrar aunque tenga una discapacidad, sea de edad avanzada, no maneje bien el idioma, tenga una computadora vieja o un ancho de banda flaco. ¿Con cuántos nos quedamos?

Los datos de Uruguay dan una idea. Según el informe de UNICEF sobre el Censo 2023, el 29% de las personas con discapacidad no tiene internet en el hogar, y solo el 47% tiene computadora o tablet, 18 puntos menos que la población sin discapacidad (UNICEF Uruguay, 2025).

## Qué es la accesibilidad web

Accesibilidad web es lograr que la información y los servicios de la web los pueda usar, y usar bien, la mayor cantidad posible de personas, sin que importen sus limitaciones personales ni las que les impone el entorno: físicas, mentales, educativas, familiares o socioeconómicas.

Pensalo como un edificio. Una escalera sin rampa le impide la entrada a una persona en silla de ruedas. Una web que no es accesible hace lo mismo con muchos usuarios. Y en los dos casos el problema no está en la persona, está en lo que se construyó.

Una persona ciega puede trabajar en un call center usando un lector de pantalla. Si el sitio donde tiene que trabajar tiene imágenes sin texto alternativo, queda afuera. La misma persona, con el mismo lector, en un sitio bien hecho, entra y hace su trabajo. Lo que cambió no fue la persona. Lo que cambió fue el sitio.

Recuerdo una anécdota de una persona en silla de ruedas que normalmente necesita un asistente para casi todo lo cotidiano. Volvió de un viaje a Europa diciendo, entre risas, que estaba agotada: la ciudad era tan accesible que había hecho todo sola. La diferencia entre depender y no depender no era la silla. Era el medio.

Por eso lo resumo así: limitación por contexto es igual a discapacidad. La discapacidad no está en la persona, está en el medio.

## Por qué importa

La web dejó de ser un lujo. Es donde nos informamos, estudiamos, trabajamos, hacemos trámites, compramos y participamos como ciudadanos. Cuando un servicio público no es accesible, no estamos hablando de una molestia: hay gente que no puede ejercer un derecho.

Y no es una minoría chica. La OMS estima que 1.300 millones de personas en el mundo, el 16% de la población, viven con una discapacidad importante (Organización Mundial de la Salud [OMS], 2023). En Uruguay, el Censo 2023 mostró que el 23% de la población tiene al menos una discapacidad leve, el 6% al menos una moderada y el 1% al menos una grave (Banco de Previsión Social [BPS], 2025). El informe de UNICEF habla de más de 197.000 personas de 5 años y más en situación de discapacidad, el 6,6% (UNICEF Uruguay, 2025).

Ojo con comparar esas cifras entre sí: miden cosas distintas. Cambia el umbral de dificultad y cambia la franja de edad. Si vas a citar una, decí también qué mide.

La accesibilidad tampoco es solo para personas con discapacidad. Los subtítulos sirven en el ómnibus sin auriculares. El buen contraste ayuda cuando el sol pega en la pantalla. Un formulario claro evita errores a cualquiera que esté apurado o cansado. Todos, alguna vez, estamos en un contexto que no es el ideal.

## Quién construye la web

Diseñadores, programadores, periodistas, editores, quienes publican contenido, y también los lectores y los clientes, que tienen el poder de exigir una web para todos. La accesibilidad no es una tarea de un rol: es un requisito desde el inicio del proyecto, a lo largo de todo el proyecto y para todas las personas involucradas. No implica diseños feos, versiones separadas ni costos desproporcionados. Implica decisiones tempranas.

### Tecnologías de apoyo

Entre ellas están los lectores de pantalla, los magnificadores, los teclados alternativos, los pulsadores, el reconocimiento de voz y las impresoras braille. Los lectores de pantalla más conocidos son JAWS (de pago), NVDA (gratuito y de código abierto, para Windows) y Orca (para Linux). Los sistemas operativos móviles traen lectores propios.

Verificá versiones, disponibilidad y enlaces antes de recomendar una herramienta: esta sección envejece rápido.

### Diseño universal

El diseño universal propone productos y entornos que pueda usar la mayor cantidad de personas, sin adaptaciones especiales. La accesibilidad es una condición para lograrlo, no un agregado para un grupo aparte.

## Por dónde empezar

El **W3C** es el consorcio internacional que desarrolla los estándares de la web. Dentro de él, la **Web Accessibility Initiative (WAI)** publica las pautas de accesibilidad para tres componentes: el contenido (WCAG), los agentes de usuario como navegadores y reproductores (UAAG) y las herramientas de autor (ATAG) (World Wide Web Consortium [W3C], s. f.-a).

Para quien hace contenido o desarrolla, la referencia es WCAG. La versión vigente es la 2.2, y la 3.0 sigue en borrador (W3C, 2026). En Uruguay, el marco legal para organismos públicos refiere a WCAG 2.1: ver `04-marco-normativo-uruguay.md`.

## Para cerrar

La única forma de que algo sea universal es aceptar que somos distintos. Lo único universal es la diversidad.

Tenemos la oportunidad y la responsabilidad de achicar la brecha entre los que pueden y los que no pueden. Estamos construyendo la web que vamos a usar cuando seamos viejos. Conviene que sea una que podamos usar.

## Nota sobre el original (2016 a 2019)

- **Cifras:** las de 2012 (INE, CIFRA) se reemplazaron por las de la OMS y el Censo 2023 de Uruguay.
- **Versión del estándar:** el original se escribió sobre WCAG 2.0. WCAG 2.2 es Recomendación del W3C desde el 5 de octubre de 2023, agrega 9 criterios de conformidad respecto de 2.1 y elimina el 4.1.1 (Procesamiento), que quedó obsoleto (W3C, s. f.-c). Los cuatro principios no cambiaron.
- **Ejemplos:** las capturas de sitios públicos de 2010 y los datos sobre la XO se retiraron por estar desactualizados.
- **Cita de Berners-Lee:** en los textos originales aparecía con dos redacciones distintas. Se unificó en una traducción propia del original en inglés del W3C. Si se reproduce en otro contexto, rotularla como traducción.
- **Imágenes:** los íconos y fotos de terceros se retiraron hasta verificar su licencia. Ver `CREDITOS.md`.

## Referencias

Banco de Previsión Social. (2025, diciembre). *Prestaciones del BPS para personas con discapacidad para el año 2024: actualización* (Comentarios de Seguridad Social n.º 130). https://www.bps.gub.uy/23779/130--prestaciones-del-bps-para-personas-con-discapacidad-para-el-ano-2024-actualizacion.html

Organización Mundial de la Salud. (2023, 7 de marzo). *Discapacidad* [Nota descriptiva]. https://www.who.int/mediacentre/factsheets/fs352/es/

UNICEF Uruguay. (2025, 12 de noviembre). *Personas en situación de discapacidad en Uruguay: brechas en el acceso a derechos a partir del Censo 2023*. https://www.unicef.org/uruguay/infancia-en-datos/Personas-en-situacion-de-discapacidad-en-Uruguay

World Wide Web Consortium. (s. f.-a). *Essential components of web accessibility*. https://www.w3.org/WAI/fundamentals/components/

World Wide Web Consortium. (s. f.-b). *Introduction to web accessibility*. https://www.w3.org/WAI/fundamentals/accessibility-intro/

World Wide Web Consortium. (s. f.-c). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

World Wide Web Consortium. (2026). *W3C Accessibility Guidelines (WCAG) 3.0* (Working Draft). https://www.w3.org/TR/wcag-3.0/

# Diseño universal y accesibilidad web

**Origen:** presentaciones "Diseño Universal y Accesibilidad web" (Primer Seminario TICs y Discapacidad, "Barreras Virtuales = Barreras Reales", Red Especial Uruguaya, 2010) y "2 diseño universal" (2015), de Silvia Da Rosa, y presentación "Accesibilidad universal: la clave del empoderamiento y la participación de todos en el siglo XXI" (VIII Congreso Latinoamericano de Ciegos, 27 de abril de 2016), de Florencia Fascioli, Matías Dodel y Silvia Da Rosa, usada con el acuerdo de sus coautores.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que cambió se indica al final.

Te propongo empezar por una pregunta sencilla: ¿para quién estamos diseñando? De ahí sale casi todo lo demás.

## Diseñar para todos, no para el promedio

La mayoría de los productos se diseñan para un usuario promedio que no existe. Se lo imagina con dos buenas manos, buena vista, pantalla grande, banda ancha y todo el tiempo del mundo. A quien no encaja se le ofrece una solución aparte: la versión de solo texto, el enlace escondido al final de la página, el teléfono al que llamar.

El diseño universal propone lo contrario. Se trata de pensar, desde el principio, productos y entornos que pueda usar la mayor cantidad posible de personas, sin adaptarlos ni rediseñarlos después.

Pensalo con una entrada de edificio. Una escalera con una rampa lateral, al fondo y con timbre, es una adaptación. Una entrada a nivel, por la que pasa igual quien empuja un cochecito, quien usa silla de ruedas y quien lleva una valija, es diseño universal. En la web pasa lo mismo: un sitio principal más una "versión accesible" aparte es la rampa del fondo. Un único sitio que funciona para todos es la entrada a nivel.

## Accesibilidad y diseño universal

La accesibilidad pregunta si una persona concreta puede usar algo. El diseño universal pregunta por qué no lo puede usar cualquiera. La primera suele traducirse en requisitos que se verifican; el segundo es un enfoque para decidir cómo se diseña. En la web se complementan: WCAG baja el enfoque a criterios que se pueden probar, y el diseño universal recuerda para qué existen.

## Los siete principios

Los principios del diseño universal los formuló en los años noventa un grupo de trabajo del Center for Universal Design, de la Universidad Estatal de Carolina del Norte (Connell et al., 1997). Sirven para orientar un proyecto entero, desde que se concibe hasta las especificaciones. Pensalos como una brújula y no como una lista para tildar.

| Principio | La idea | En la web |
|---|---|---|
| 1. Uso equitativo | Útil para personas con distintas capacidades, sin segregar ni estigmatizar | Un solo sitio para todos; nada de "versión accesible" aparte |
| 2. Flexibilidad | Se adapta a preferencias y habilidades: hay más de una forma de usarlo y cada persona va a su ritmo | Se maneja con mouse, teclado, pantalla táctil o voz; sin tiempos rígidos |
| 3. Simple e intuitivo | Fácil de entender sin importar la experiencia, el idioma o la concentración | Lenguaje claro, navegación consistente, respuesta después de cada acción |
| 4. Información perceptible | Comunica lo necesario sin depender de un solo sentido ni del entorno | Texto alternativo, subtítulos, buen contraste, nada que dependa solo del color |
| 5. Tolerancia al error | Minimiza los riesgos y las consecuencias de acciones accidentales | Confirmar lo irreversible, permitir deshacer y corregir |
| 6. Poco esfuerzo físico | Se usa con comodidad y esfuerzo mínimo | Zonas de toque grandes; sin gestos precisos ni repetitivos |
| 7. Tamaño y espacio apropiados | Sirve sin importar el cuerpo, la postura o la movilidad | Controles separados entre sí; diseño que funciona en pantallas chicas y grandes |

Los cuatro principios de WCAG (perceptible, operable, comprensible y robusto) y estos siete no se corresponden uno a uno, pero se pisan bastante. El cuarto principio del diseño universal es casi el perceptible de WCAG, el tercero es el comprensible, y el quinto está en las pautas de entrada de datos asistida (ver `02-principios/`).

## La discapacidad está en el medio

Hay una frase que me gusta repetir: la discapacidad está en el medio, no en las personas. Una persona ciega no tiene un problema para completar un formulario. El problema lo tiene el formulario que no tiene etiquetas.

Es la lógica del modelo social de la discapacidad. Las limitaciones no dependen solo de la condición física o mental de una persona, sino de las barreras del entorno que le impiden participar en igualdad de condiciones. El Censo 2023 de Uruguay midió la discapacidad con ese enfoque (UNICEF Uruguay, 2025).

En el plano de los derechos, la Convención sobre los Derechos de las Personas con Discapacidad de la ONU define el acceso a las tecnologías de la información y las comunicaciones, la web incluida, como un derecho básico (Naciones Unidas, s. f.; W3C, s. f.).

## Accesibilidad no es inclusión

Scott Rains lo planteó en un artículo de 2011 con un título que no deja dudas: accesibilidad no es inclusión (Rains, 2011). La accesibilidad es pasiva: deja la puerta abierta y sin obstáculos. La inclusión invita activamente a entrar. La primera mira objetos y espacios; la segunda, vidas humanas.

Su advertencia más incómoda es sobre el cumplimiento. Cuando la accesibilidad se vuelve una obsesión por las listas de verificación, se conforma con lo menos malo y fija un piso porque da por hecho que el techo es inalcanzable (Rains, 2011). Rains aclara que "universal" no quiere decir una sola solución para todos, porque eso es imposible.

Y ojo, nada de esto va contra WCAG. Sin criterios que se puedan verificar, la accesibilidad se queda en buenas intenciones, y por eso este repo trabaja con ellos. Es un recordatorio de para qué están: el piso evita que alguien quede afuera por un descuido, y el diseño universal pregunta cómo llegar más arriba. También hay una razón práctica: las adaptaciones especiales no escalan y suelen terminar en un jardín cerrado, una versión aparte que nadie mantiene.

## La brecha digital no es solo de acceso

La presentación del Congreso de 2016 partía de otra pregunta: qué pasa con la discapacidad cuando la información se vuelve el insumo central de la economía. Las tecnologías de la información y la comunicación tienen un potencial nunca visto para democratizar el acceso, pero potencial no es democratización. La tecnología no es buena ni mala en sí misma, y tampoco es neutral (Fascioli et al., 2016).

La hipótesis de la estratificación lo explica así: las desigualdades sociales determinan las desigualdades digitales. Las brechas tecnológicas reproducen las que ya existían, porque limitan las posibilidades de participar, de informarse y de acumular capital social justo de quienes ya estaban en desventaja (Van Dijk, 2005, y Witte y Mannon, 2010, como se citan en Fascioli et al., 2016). La discapacidad es una desigualdad entre muchas.

Medirlo es difícil, y a veces el método es parte del problema. Ciertas formas de relevamiento no permiten obtener información de algunas personas: algunas encuestas no llegan a personas sordas, y una encuesta en línea sin accesibilidad deja afuera a las personas ciegas, que eran justo las que se quería medir. Un estudio de Estados Unidos con una muestra de 2003 encontró que las personas con discapacidad tenían menos probabilidad de vivir en hogares con computadora, de usarla y de estar en línea (Dobransky & Hargittai, 2006). Es un dato viejo. Los del Censo 2023 de Uruguay, en `05-costos-y-beneficios.md`, muestran que la brecha de acceso sigue ahí (UNICEF Uruguay, 2025).

La presentación cerraba con cuatro ideas que siguen valiendo:

- Evitar los determinismos, sin tecnofilia ni tecnofobia.
- Alejarse de las concepciones dicotómicas.
- Pensar la brecha en varias dimensiones: acceso, usos y habilidades.
- Tener el bienestar y el desarrollo como objetivo último.

Y con un pedido: que el diseño universal sea un tema transversal en la formación, no una materia aparte. En 2016 la presentación decía que en Uruguay no había datos, y que esa ausencia era un dato en sí misma. El Censo 2023 cambió parte de ese panorama (UNICEF Uruguay, 2025).

## No accedemos siempre de la misma manera

El usuario "sin ninguna discapacidad" también cambia de situación. Alguien usa el celular al sol y no ve la pantalla. Otra persona mira un video en el ómnibus sin auriculares. Otra completa un trámite con una mano, porque en la otra lleva a un bebé. Otro tiene una conexión lenta, una computadora vieja o una nueva que todavía no conoce.

Lo que se diseña para quien más lo necesita termina sirviendo a todos. Los subtítulos nacieron para personas sordas y los usa quien mira videos sin sonido.

## Primer paso: conocer a quién le hablás

Antes de decidir nada, conocé a tu público real. Qué dispositivos usa, con qué conexión, qué navegador, con qué ayudas. Sin asumir un usuario sin ninguna discapacidad ni un equipo ideal. Los datos de uso, las consultas que llegan a soporte y la conversación directa con personas usuarias dicen más que cualquier supuesto.

## Cómo se logra, en la práctica

- **Seguir las pautas WCAG.** Es el camino para llevar el enfoque a requisitos que se verifican (ver `02-componentes-y-wcag.md`).
- **Usar estándares web.** HTML y CSS bien usados resuelven una parte grande del problema. El original mencionaba XHTML; hoy basta con decir HTML.
- **Dar alternativas textuales** a lo que no es texto.
- **Tratarlo como un proceso, no como un parche.** Pruebas automáticas y manuales, retroalimentación de las personas usuarias, pruebas con usuarios y capacitación para quienes cargan contenido.

Sobre el por qué conviene hacerlo en términos de costos y beneficios, ver `05-costos-y-beneficios.md`. El marco legal uruguayo está en `04-marco-normativo-uruguay.md`.

## Para llevarte

Si te quedás con una sola idea de esta página, que sea esta: cuando alguien no puede usar algo, vale la pena preguntarse primero qué del diseño se lo impide, y recién después qué le pasa a la persona.

## Nota sobre el original (2010, 2015 y 2016)

La presentación de 2010 y la de 2015 comparten buena parte de su estructura: qué es el diseño universal, qué limitaciones encuentran las personas en la web, cómo se logra una web accesible y por qué conviene. La de 2015 suma los siete principios y un bloque de legislación de base (Declaración Universal de los Derechos Humanos, Normas Uniformes de 1993, la Convención sobre los Derechos de las Personas con Discapacidad y la iniciativa eEurope). Esta versión unifica las dos.

Las secciones sobre accesibilidad e inclusión y sobre la brecha digital salen de la presentación del Congreso de 2016. De esa presentación no se incluyen los ejemplos de plataformas (Apple, Facebook y Twitter), el repaso de la televisión uruguaya de 2016, que quedó viejo, ni los ejemplos de narrativa transmedia y de acceso cultural. Su bloque sobre la ley de servicios de comunicación audiovisual pasó a `04-marco-normativo-uruguay.md`.

Lo que no se incluye de las otras dos: el bloque de legislación, que quedó viejo y se reemplaza por el marco uruguayo vigente; las listas de limitaciones por tipo de discapacidad, que ya están explicadas en la introducción y en cada principio; los ejemplos visuales; y la lista de razones de rentabilidad, que pasó a `05-costos-y-beneficios.md`.

## Referencias

Connell, B. R., Jones, M., Mace, R., Mueller, J., Mullick, A., Ostroff, E., Sanford, J., Steinfeld, E., Story, M., & Vanderheiden, G. (1997). *The principles of universal design* (Version 2.0). The Center for Universal Design, North Carolina State University. https://design.ncsu.edu/?p=32673

Dobransky, K., & Hargittai, E. (2006). The disability divide in internet access and use. *Information, Communication & Society, 9*(3), 313-334. https://doi.org/10.1080/13691180600751298

Fascioli, F., Dodel, M., & Da Rosa, S. (2016, 27 de abril). *Accesibilidad universal: la clave del empoderamiento y la participación de todos en el siglo XXI* [Presentación de conferencia]. VIII Congreso Latinoamericano de Ciegos. https://www.slideshare.net/slideshow/congreso-latinoamericano-de-ciegos-tic-y-diseo-universal-64746867/64746867

Naciones Unidas. (s. f.). *Convention on the rights of persons with disabilities*. https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities.html

Rains, S. (2011, enero). Accessibility is not inclusion. *New Mobility*, 36-37. https://www.slideshare.net/slideshow/accessibility-is-not-inclusion/6825927

UNICEF Uruguay. (2025, 12 de noviembre). *Personas en situación de discapacidad en Uruguay: brechas en el acceso a derechos a partir del Censo 2023*. https://www.unicef.org/uruguay/infancia-en-datos/Personas-en-situacion-de-discapacidad-en-Uruguay

World Wide Web Consortium. (s. f.). *Introduction to web accessibility*. https://www.w3.org/WAI/fundamentals/accessibility-intro/

---

← [Componentes de la accesibilidad web y WCAG](02-componentes-y-wcag.md) · [Índice](../README.md) · [Siguiente: Marco normativo en Uruguay](04-marco-normativo-uruguay.md) →

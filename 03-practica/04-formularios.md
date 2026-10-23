# Formularios accesibles

**Origen:** resumen de la sesión "3.2 Formularios accesibles" (criterios y técnicas de WCAG 2.0), de Silvia Da Rosa. La presentación "Formularios" de su perfil de SlideShare es una compilación de materiales de terceros y no se reproduce.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que cambió en 2.1 y 2.2 se indica al final.

Los formularios son el lugar donde más cosas se pueden trabar, y donde más se nota el cuidado. Te dejo una lista corta para revisar los tuyos.

Un formulario es donde la web le pide algo a la persona: un dato, una decisión, un pago. Si falla, no hay trámite. Y casi siempre falla por lo mismo: alguien no sabe qué se le pide, no puede completar el campo o no entiende por qué se rechazó lo que escribió.

## Qué se revisa

1. **Cada campo tiene su etiqueta.** Visible y asociada al campo por código, no solo puesta al lado. Así el lector de pantalla la lee al llegar al campo y un clic en la etiqueta activa el control (criterios 1.3.1, 3.3.2 y 4.1.2).
2. **Lo que va junto se agrupa.** Una serie de botones de opción o de casillas, como "forma de pago", se agrupa con un conjunto de campos y una leyenda que dice de qué se trata.
3. **Los obligatorios se indican con texto.** Un asterisco de otro color no alcanza: hay que explicar qué significa y no depender del color (1.4.1, 3.3.2).
4. **Las instrucciones llegan antes del campo.** Formatos esperados, límites, por qué se pide un dato (3.3.2).
5. **Los datos personales se pueden autocompletar.** El navegador completa solo nombre, dirección o correo cuando el campo declara su propósito (1.3.5).
6. **Los errores se encuentran y se entienden.** El mensaje dice en texto qué campo falló y, si se puede, cómo corregirlo, y queda asociado a ese campo (3.3.1 y 3.3.3). En trámites legales, financieros o que modifican datos, la persona puede revisar, corregir o deshacer antes de que sea definitivo (3.3.4).
7. **Nada cambia sin aviso.** Enviar el formulario al completar el último campo es una falla clásica. También lo es que un menú desplegable cambie la página apenas se elige una opción, sin avisar antes qué va a pasar (3.2.2).
8. **Hay tiempo.** Si hay límite de tiempo, se puede extender o apagar (2.2.1), y si hay que volver a ingresar, no se pierden los datos (2.2.5, nivel AAA).
9. **Se puede completar con el teclado**, en un orden lógico.

No uses el texto de ayuda dentro del campo como etiqueta. Desaparece al escribir, suele tener poco contraste y deja de ser una guía justo cuando la persona la necesita.

## La prueba de cinco minutos

Si hoy tenés solo cinco minutos, hacé esto:

1. Completá el formulario usando solo el teclado: Tab y Shift+Tab para moverte, flechas para las opciones, Espacio y Enter para activar.
2. Provocá errores a propósito: dejá obligatorios vacíos, escribí mal un correo.
3. Una vez, probalo con un lector de pantalla. NVDA es gratuito.

## Qué sumaron WCAG 2.1 y 2.2

- 1.3.5, identificar el propósito de los campos (2.1).
- 3.3.7, entrada redundante: no pedir dos veces el mismo dato en un mismo proceso (2.2).
- 3.3.8, autenticación accesible: ningún paso de ingreso exige recordar, resolver o transcribir algo sin otra opción (2.2).

Los detalles están en `02-principios/03-comprensible.md` y en `02-principios/01-perceptible.md`.

## Para seguir

- El tutorial de formularios del W3C cubre etiquetas, agrupación, instrucciones, validación, notificaciones, formularios de varias páginas y controles personalizados: https://www.w3.org/WAI/tutorials/forms/
- Para el diseño del formulario más allá de la accesibilidad (posición de etiquetas, agrupación, acciones primarias y secundarias, validación en línea), la referencia habitual es el libro de Luke Wroblewski (2008) y las 60 directrices de usabilidad de Olga Carreras (2007).

## Nota sobre el original

La sesión 3.2 del Drive es un esqueleto: una agenda vacía y un resumen de lo que se iba a usar del W3C. Los criterios eran 1.3.1, 3.3.2, 3.3.3, 3.3.4, 3.3.5, 2.2.5 y 2.2.1, y las técnicas F36, F82, H91, H92, G13 y SCR18, que se buscan por código en el documento de técnicas del W3C. Esta versión los ordena como una lista de revisión.

La presentación "Formularios" de SlideShare (90 diapositivas) es otro material. Su primera diapositiva aclara que nada de lo que contiene es creación del autor y que reúne información de otras fuentes, sobre todo del libro de Wroblewski. Es diseño de formularios más que accesibilidad, y por eso queda afuera del repo.

## Referencias

Carreras Montoto, O. (2007, febrero). *Formularios usables: 60 directrices de usabilidad* [Entrada de blog]. Usable y accesible. https://olgacarreras.blogspot.com.es/2007/02/formularios-usables-60-directrices-de.html

Wroblewski, L. (2008). *Web form design: Filling in the blanks*. Rosenfeld Media.

World Wide Web Consortium. (s. f.). *Forms tutorial*. https://www.w3.org/WAI/tutorials/forms/

---

← [Documentos accesibles: texto, presentaciones y PDF](03-documentos-accesibles.md) · [Índice](../README.md) · [Siguiente: Evaluación de accesibilidad](../04-evaluacion/01-principios-de-evaluacion.md) →

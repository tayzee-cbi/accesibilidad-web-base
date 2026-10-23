# Imágenes accesibles

**Origen:** presentación "2.3 Imágenes accesibles" (2017) y su "trencito" de imágenes, de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0 (criterios 1.1.1 y 1.4.5). Esos dos criterios siguen igual en WCAG 2.2.

Antes de escribir un texto alternativo, la pregunta es otra: ¿para qué está esta imagen acá? Según la respuesta, el texto alternativo cambia, o no hay que ponerlo. El W3C ordena las imágenes en categorías, y esa es la forma más clara de decidir (W3C, s. f.-b).

## Las categorías, con ejemplos

- **Informativa.** Transmite un concepto o una información: una foto, una ilustración. El texto alternativo es breve y dice lo que aporta en ese contexto.
- **Decorativa.** No aporta nada: un adorno, una viñeta hecha con una imagen. Se puede incluir desde la hoja de estilos. Si va como imagen en el HTML, `alt=""` y sin atributo `title` (W3C, s. f.-c).
- **Funcional.** Una imagen que funciona como enlace o botón. El texto alternativo dice adónde lleva o qué hace, no cómo se ve. Y no hace falta escribir "enlace a": el lector de pantalla ya lo anuncia.
- **Imagen de texto.** El texto alternativo repite las mismas palabras que la imagen. Si se puede, es mejor usar texto de verdad (criterio 1.4.5).
- **Compleja**, como un gráfico o un diagrama. Un texto alternativo corto y, cerca de la imagen, la información completa: en la misma página o en un enlace inmediato.
- **Grupo de imágenes.** Si varias imágenes cuentan una sola cosa, el texto alternativo de una cuenta la de todo el grupo.

## Imágenes que funcionan como enlaces

Mal: `alt="Icono de una casa"`, `alt="Impresora"`, `alt="Signo de interrogación"`, `alt="Sobre"`.
Bien: `alt="Página principal del sitio"`, `alt="Versión imprimible"`, `alt="Ayuda"`, `alt="Contacto"`.

La imagen es lo de menos. Lo que tiene que quedar claro es qué pasa si la persona hace clic.

## Ejercicio: seis imágenes, seis decisiones

¿Qué texto alternativo le pondrías a cada una? Una posible solución:

| Imagen | Texto alternativo |
|---|---|
| Un ícono de advertencia | "¡Importante!" |
| La foto de un gatito | "Gatito" |
| Un ícono de PDF junto a un enlace | "En formato PDF" |
| Un sello de garantía | "3 años de garantía" |
| Una imagen de letras deformadas, de un CAPTCHA | Un texto que identifique y describa su propósito, y una forma alternativa de resolverlo |
| Un adorno | Vacío (`alt=""`) |

Para decidir con más seguridad, el W3C tiene un árbol de decisión que arranca con una pregunta por caso: si la imagen tiene texto, si está en un enlace o botón, si aporta significado o es un adorno (W3C, s. f.-a).

## El trencito

- **Texto alternativo:** obligatorio. Transmite la misma información que la imagen.
- **Descripción larga:** solo si la imagen es compleja.
- **Imagen decorativa:** texto alternativo vacío.
- **Imagen en un enlace:** describí adónde va.
- **Imagen de texto:** escribí lo que dice.

También cuentan las experiencias sensoriales y las pruebas, como un test de audición, un concierto o una obra de arte: ahí alcanza con una identificación que diga de qué se trata.

## Qué cambió desde 2017

- WCAG 2.1 sumó el criterio 1.4.11 (contraste de elementos no textuales), que alcanza a las partes de un gráfico necesarias para entenderlo: deben tener un contraste de al menos 3:1 (W3C, s. f.-d).
- WCAG 2.2 no agregó criterios sobre imágenes.
- En Uruguay, el catálogo de UNIT incluye la guía UNIT-ISO/IEC TS 20071-11 sobre textos alternativos para imágenes. Figura como disponible, no gratuita (UNIT, s. f.).

## Nota sobre el original (2017)

La agenda de la presentación seguía la sesión de imágenes del workshop de WAI, y sus categorías coinciden con las del tutorial de imágenes del W3C. Lo propio eran los ejercicios y el trencito. Lo que envejeció: usaba el atributo `longdesc` y los ejemplos tomaban a un personaje de historieta, que acá se reemplazaron por ejemplos genéricos por una cuestión de derechos.

## Referencias

Instituto Uruguayo de Normas Técnicas. (s. f.). *Normas disponibles sin costo*. https://www.unit.org.uy/normalizacion/normas/acc/

World Wide Web Consortium. (s. f.-a). *An alt decision tree*. https://www.w3.org/WAI/tutorials/images/decision-tree/

World Wide Web Consortium. (s. f.-b). *Images tutorial*. https://www.w3.org/WAI/tutorials/images/

World Wide Web Consortium. (s. f.-c). *Technique H67: Using null alt text and no title attribute on img elements for images that assistive technology should ignore*. https://www.w3.org/WAI/WCAG22/Techniques/html/H67

World Wide Web Consortium. (s. f.-d). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

---

← [Tutoriales de WAI para seguir practicando](00-tutoriales-de-wai.md) · [Índice](../README.md) · [Siguiente: Estructura de página y navegación](02-estructura-y-navegacion.md) →

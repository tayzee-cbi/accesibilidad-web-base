# Principio 3: Comprensible

**Origen:** presentación "Accesibilidad web por principios, Principio 3: Comprensible" (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que sumaron WCAG 2.1 y 2.2 está en la última sección.

Comprensible quiere decir que la información y el funcionamiento de la interfaz se pueden entender. Que ni el contenido ni la operación queden más allá de lo que la persona puede comprender. El texto oficial de cada criterio no está copiado acá: está en las páginas del W3C que se citan al final.

## Pauta 3.1: legible

- **Idioma.** La página declara su idioma, y los pasajes en otro idioma también. Así el lector de pantalla pronuncia bien cada parte y las traducciones automáticas funcionan mejor. En HTML alcanza con el atributo `lang`:

```html
<html lang="es">
...
<p>Lo probamos con un <span lang="en">fallback</span> humano.</p>
```

- **Texto fácil de leer.** Texto corto, párrafos cortos, una ilustración o un resumen cuando el tema se pone difícil.
- **En el nivel AAA:** definir palabras inusuales y jerga, expandir las abreviaturas, ofrecer una versión más simple cuando el texto exige un nivel de lectura alto, y aclarar la pronunciación cuando una palabra es ambigua si no se la oye.

## Pauta 3.2: predecible

La página tiene que comportarse como la persona espera.

- Que un componente reciba el foco no puede cambiar el contexto: no te manda a otra página ni te abre una ventana.
- Cambiar el valor de un control tampoco, salvo que se avise antes. El clásico es un desplegable que te lleva a otra página apenas elegís una opción.
- Los menús que se repiten aparecen siempre en el mismo orden, y los componentes con la misma función se identifican de la misma forma en todo el sitio.
- En el nivel AAA: los cambios de contexto ocurren solo si la persona los pide.

A quien usa un magnificador, que ve solo un pedacito de la pantalla, un diseño coherente le ahorra buscar. A quien tiene limitaciones motrices, le ahorra pulsaciones. Y a quien tiene limitaciones cognitivas, le evita confundirse.

## Pauta 3.3: entrada de datos asistida

Todo el mundo comete errores. Las personas con discapacidad pueden cometer más, y a veces les cuesta más darse cuenta. La pauta busca que los errores graves se reduzcan, que se noten y que se sepa cómo corregirlos.

- Si se detecta un error, se dice qué campo es y qué pasó, con texto.
- Los campos tienen etiquetas o instrucciones.
- Si hay una sugerencia de corrección, se ofrece.
- Cuando el envío implica un compromiso legal o financiero, modifica o borra datos de la persona, o entrega una prueba, tiene que poder revertirse, revisarse o confirmarse antes de cerrar.
- En el nivel AAA: ayuda según el contexto y prevención de errores en todos los envíos.

## Qué sumaron WCAG 2.1 y 2.2 en este principio

**WCAG 2.1** no agregó criterios en este principio.

**WCAG 2.2** sumó estos cuatro:

| Criterio | Nivel | En pocas palabras |
|---|---|---|
| 3.2.6 Ayuda coherente (Consistent Help) | A | Si la ayuda aparece en varias páginas (contacto, chat, autoservicio), está siempre en el mismo orden relativo |
| 3.3.7 Entrada redundante (Redundant Entry) | A | No pedir dos veces el mismo dato en un mismo proceso: completarlo solo o dejarlo seleccionable |
| 3.3.8 Autenticación accesible, mínimo (Accessible Authentication, Minimum) | AA | Ningún paso de ingreso exige recordar, resolver o transcribir algo, salvo que haya otra opción o una ayuda, como admitir gestores de contraseñas y copiar y pegar |
| 3.3.9 Autenticación accesible, mejorado (Enhanced) | AAA | Ni siquiera se pide reconocer objetos o imágenes propias para ingresar |

El 3.3.8 y el 3.3.9 cambian la discusión sobre los CAPTCHA que aparece en el principio Perceptible: el problema ya no es solo describirlos, es que resolver un acertijo para ingresar deja afuera a mucha gente.

## Para seguir

Las páginas "What's New" de WAI para 2.1 y 2.2 (ver referencias) enlazan la explicación detallada de cada criterio.

## Nota sobre el original (2017)

La presentación reproducía en español el texto de cada criterio de WCAG 2.0 y sus beneficios, con ejemplos de código de la época de XHTML (`xml:lang`, `acronym`). Lo que envejeció: no cubre los cuatro criterios que sumó WCAG 2.2 en este principio (3.2.6, 3.3.7, 3.3.8 y 3.3.9). Esta versión explica cada pauta con sus palabras y remite al W3C para el texto oficial.

## Referencias

World Wide Web Consortium. (s. f.-a). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

World Wide Web Consortium. (s. f.-b). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

---

← [Principio 2: Operable](02-operable.md) · [Índice](../README.md) · [Siguiente: Principio 4: Robusto](04-robusto.md) →

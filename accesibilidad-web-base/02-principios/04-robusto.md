# Principio 4: Robusto

**Origen:** presentación "Accesibilidad web por principios, Principio 4: Robusto" (2017), de Silvia Da Rosa.
**Revisión de este texto:** octubre de 2026.
**Base normativa del original:** WCAG 2.0. Lo que sumaron WCAG 2.1 y 2.2 está en la última sección.

Robusto quiere decir que el contenido se puede interpretar bien con una gran variedad de programas, incluidas las tecnologías de apoyo, hoy y mañana. Las tecnologías cambian rápido y a quienes desarrollan les cuesta seguirles el ritmo. El contenido tiene que aguantar esos cambios. Este principio tiene una sola pauta, la 4.1, y es el que más se movió entre versiones.

## Pauta 4.1: compatible

**4.1.1 Procesamiento.** En WCAG 2.0 y 2.1 pedía código bien formado: etiquetas completas, anidado correcto, sin atributos duplicados y con identificadores únicos. En WCAG 2.2 se eliminó. Según el W3C, desde que se publicó WCAG 2.0 las especificaciones y los navegadores mejoraron el manejo de los errores de código, y las tecnologías de apoyo ya no analizan el marcado por su cuenta sino que dependen del navegador (W3C, s. f.-c).

Eso no vuelve inútil validar el código: sigue siendo una buena práctica. Pero ya no es un requisito de conformidad de WCAG 2.2.

**4.1.2 Nombre, función, valor.** Todo componente de interfaz (campos de formulario, enlaces, componentes armados con scripts) tiene que decirle a la tecnología de apoyo cómo se llama, qué es, en qué estado está y cuándo cambia. Los controles estándar de HTML cumplen esto solos si se usan como indica su especificación. El criterio apunta sobre todo a quienes programan sus propios componentes. Para esos casos existe WAI-ARIA (ver referencias).

## Qué sumaron WCAG 2.1 y 2.2 en este principio

**WCAG 2.1** agregó un criterio:

| Criterio | Nivel | En pocas palabras |
|---|---|---|
| 4.1.3 Mensajes de estado (Status Messages) | AA | Los mensajes que aparecen sin recibir el foco, como "agregaste la clase a tu agenda", tienen que poder ser anunciados por la tecnología de apoyo |

Una persona ciega que agrega una actividad a su calendario necesita escuchar la confirmación igual que una persona que ve el aviso en pantalla.

**WCAG 2.2** eliminó el 4.1.1 Procesamiento.

## Nota sobre el original (2017)

La presentación incluía el criterio 4.1.1 Procesamiento como requisito y recomendaba validar el código con los validadores de HTML y CSS del W3C. Lo que envejeció: WCAG 2.2 eliminó el 4.1.1, y la presentación no cubre el 4.1.3 que sumó WCAG 2.1. Validar el código sigue siendo buena práctica, pero ya no es un requisito de conformidad.

## Referencias

World Wide Web Consortium. (s. f.-a). *What's new in WCAG 2.1*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-21

World Wide Web Consortium. (s. f.-b). *What's new in WCAG 2.2*. https://www.w3.org/WAI/standards-guidelines/wcag/new-in-22

World Wide Web Consortium. (s. f.-c). *Understanding SC 4.1.1: Parsing (obsolete and removed)*. https://www.w3.org/WAI/WCAG22/Understanding/parsing

World Wide Web Consortium. (s. f.-d). *WAI-ARIA overview*. https://www.w3.org/WAI/standards-guidelines/aria/

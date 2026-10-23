# Accesibilidad web: material de base

Hola, soy Silvia. Durante varios años armé cursos y talleres sobre accesibilidad web, y este repositorio junta ese material, actualizado y ordenado para que lo puedas leer, usar y seguir a tu manera. Ojalá te sirva.

> **Un aviso antes de empezar (octubre de 2026):** es un archivo de referencia y no lo
> estoy manteniendo. El contenido parte de materiales de formación que escribí entre
> 2016 y 2019 sobre **WCAG 2.0**. Los principios siguen vigentes; los criterios, las cifras y las
> herramientas pueden haber cambiado. Para requisitos actuales, andá siempre a la
> fuente del W3C.

## Para qué sirve

Es una introducción a la accesibilidad web, en español y pensada para quien llega al
tema por primera vez. Si trabajás en producto, diseño, desarrollo, comunicación o
gestión pública, está escrita para vos. Reúne lo que enseñé en cursos y talleres a lo
largo de los años, y lo ordené para que lo puedas leer, reutilizar y seguir por tu
cuenta.

No reemplaza a los estándares ni a quienes los redactan: cada tema te lleva a la
fuente primaria.

## Qué estándar rige hoy

- **WCAG 2.2** es la versión vigente del W3C. Extiende a 2.0 y 2.1: los principios
  (perceptible, operable, comprensible, robusto) se mantienen y se agregan
  criterios. Ver https://www.w3.org/TR/WCAG22/
- **WCAG 3.0** sigue en estado de borrador de trabajo y no es citable como
  requisito. Ver https://www.w3.org/TR/wcag-3.0/
- **En Uruguay**, el Decreto 406/022 alcanza a los organismos públicos. Su anexo de 2022
  se basaba en **WCAG 2.1**, niveles A y AA más siete criterios AAA, y las publicaciones de
  AGESIC de septiembre de 2026 toman **WCAG 2.2**, niveles A y AA, como punto de partida.
  Ver `01-fundamentos/04-marco-normativo-uruguay.md`.

Trabajar bien hoy sobre WCAG 2.2 AA es la mejor preparación para lo que venga.

## Estructura

```
accesibilidad-web-base/
├── 01-fundamentos/
│   ├── 01-introduccion.md
│   ├── 02-componentes-y-wcag.md
│   ├── 03-diseno-universal.md
│   ├── 04-marco-normativo-uruguay.md
│   └── 05-costos-y-beneficios.md
├── 02-principios/
│   ├── 01-perceptible.md
│   ├── 02-operable.md
│   ├── 03-comprensible.md
│   └── 04-robusto.md
├── 03-practica/
│   ├── 00-tutoriales-de-wai.md
│   ├── 01-imagenes.md
│   ├── 02-estructura-y-navegacion.md
│   ├── 03-documentos-accesibles.md
│   └── 04-formularios.md
├── 04-evaluacion/
│   ├── 01-principios-de-evaluacion.md
│   └── plantilla-evaluacion-wcag22.xlsx
├── CREDITOS.md
├── ORIGINALES.md
└── REFERENCIAS.md
```

| Carpeta o archivo | Contenido |
|---|---|
| `01-fundamentos/` | Qué es la accesibilidad, por qué importa, componentes, WCAG, diseño universal, marco normativo uruguayo y costos y beneficios |
| `02-principios/` | Los cuatro principios de WCAG: perceptible, operable, comprensible, robusto |
| `03-practica/` | Imágenes, estructura de página y navegación, documentos accesibles, formularios, y tutoriales del W3C para seguir |
| `04-evaluacion/` | Principios de evaluación y una plantilla sobre WCAG 2.2 |
| `REFERENCIAS.md` | Fuentes en formato APA 7 |
| `CREDITOS.md` | Materiales de terceros: qué se incluye, qué se enlaza y bajo qué licencia |
| `ORIGINALES.md` | El material de 2016 a 2019 que dio origen a este repo y qué archivo lo reemplaza |

Cada archivo de contenido indica su origen y su base normativa, trae una "Nota sobre el original" con lo que cambió, y cierra con sus referencias.

**Estado:** versión 2, octubre de 2026.

## Fuentes recomendadas

- W3C Web Accessibility Initiative (WAI), fuente normativa.
- Programa de Accesibilidad en Entornos Digitales de AGESIC, con guías, herramientas y
  el Observatorio de Accesibilidad Digital:
  https://www.gub.uy/agencia-gobierno-electronico-sociedad-informacion-conocimiento/accesibilidad-entornos-digitales
- Olga Revilla Muñoz y Olga Carreras Montoto, *Accesibilidad web: WCAG 2.2 de forma
  sencilla* (2024), de descarga gratuita (ver `REFERENCIAS.md`).

## Cómo citar

Da Rosa, S. (2026). *Accesibilidad web: material de base* [Repositorio]. GitHub.
https://github.com/tayzee-cbi/accesibilidad-web-base

## Licencia

Salvo que se indique lo contrario, el contenido de este repositorio es
© 2026 Silvia Da Rosa y se publica bajo la licencia Creative Commons
Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0):
https://creativecommons.org/licenses/by-sa/4.0/

Podés copiar, adaptar y redistribuir el material, incluso con fines comerciales,
siempre que me atribuyas la autoría, indiques si hiciste cambios y publiques tu
versión bajo la misma licencia.

Los materiales de terceros enlazados o mencionados conservan su propia licencia y
no quedan cubiertos por esta. Ver `CREDITOS.md`.

## Si querés seguir con esto

Yo no voy a mantener el material, pero la licencia permite que lo haga cualquier
persona. Si lo adaptás o lo actualizás, me alegra mucho: solo mantené la atribución y
la misma licencia.

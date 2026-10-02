# Blog Web TBNB — Brief del proyecto

**Qué es:** el blog de la página web de The Bar N' Bar. Contenido en formato
artículo, pensado para tráfico orgánico (SEO), a partir de un listado de
temas que aporta `seo-estrategia-senior` (los que ya tienen más búsquedas
validadas).

**Fecha de inicio:** 2026-09-28.

## Objetivo

Atraer tráfico cualificado de hosteleros que buscan soluciones reales
(escandallos, food cost, carta, operativa, marca...) y convertir ese tráfico
en la misma autoridad de marca que ya se construye en redes
(`comunicacion-redes-sociales/`) y en el Hospitality Report
(`hospitality-report/`). **El reto no es encontrar temas — `seo-estrategia-senior`
ya los da con tráfico validado.** El reto es que cada artículo aporte algo
real y suene a TBNB, no a "artículo de agencia SEO genérico" — es
exactamente la preocupación con la que arranca este proyecto: redactar
rápido es fácil, redactar algo relevante e interesante no lo es.

## Tono — mismo criterio que el resto de contenido de TBNB, adaptado a SEO

Este proyecto no inventa un tono nuevo: reutiliza el criterio ya fijado en
`comunicacion-redes-sociales/BRIEF.md` y en `hospitality-report/BRIEF.md`,
adaptado a artículo largo:

- **La regla que más importa aquí, citada literalmente de
  `comunicacion-redes-sociales/BRIEF.md`:** *"No hace falta explicar todo.
  Hace falta que se note que sabemos."* Un artículo de SEO genérico explica
  lo obvio para llenar palabras; un artículo de TBNB tiene una opinión y un
  criterio, aunque sea sobre un tema muy buscado y muy escrito ya por otros.
- **Nunca sonar a:** agencia de marketing genérica, blog de SEO de relleno,
  gurú de LinkedIn, listicle sin criterio ("10 consejos" sin jerarquía ni
  postura).
- **Rigor de datos, heredado de `hospitality-report/BRIEF.md`:** ninguna
  cifra o dato de mercado sin fuente citada. Si no hay dato real, se dice
  con criterio y experiencia propia de TBNB, nunca se inventa una cifra para
  sonar más autorizado.
- **Estructura pensada para lectura real, no solo para el buscador:**
  frases cortas, escaneable, sin relleno para alargar el artículo — un
  artículo corto y útil vale más que uno largo y genérico.

## Cómo se organiza el trabajo

1. Andrea (o `seo-estrategia-senior`) añade temas nuevos a `listado-temas.md`.
2. `blog-estrategia-seo` prioriza, agrupa y define la intención de búsqueda
   y el ángulo TBNB de cada tema — sin esto, no se investiga ni se redacta.
3. `blog-investigacion` investiga cada tema en profundidad (revisa primero
   el conocimiento ya propio de TBNB en `hospitality-report/matriz-
   tematica.md` antes de buscar fuentes externas nuevas).
4. `blog-redaccion` escribe el artículo final con el tono de arriba y
   estructura optimizada para SEO.
5. `blog-revision-seo-calidad` revisa el artículo terminado contra un
   checklist SEO on-page **y** contra la pregunta real: ¿esto es relevante
   e interesante, o es relleno? Es el paso que responde directamente a la
   preocupación con la que arrancó este proyecto.
6. Nada se publica en la web en vivo sin que Andrea o Sergio lo revisen —
   mismo criterio que ya aplica en `comunicacion-redes-sociales/` para
   contenido público de marca, aunque la regla de `CLAUDE.md` esté escrita
   pensando en el envío a clientes.

## El equipo

Cuatro especialistas (`.claude/agents/`), cada uno con una fase del proceso:

1. **`blog-estrategia-seo`** — prioriza y agrupa el listado de temas,
   define intención de búsqueda y ángulo TBNB de cada uno, propone título
   (H1) y subtemas (H2). No escribe contenido ni investiga en profundidad.
2. **`blog-investigacion`** — investiga cada tema ya priorizado: datos,
   ejemplos reales, fuentes. Primero revisa la matriz temática del
   Hospitality Report (ya es conocimiento propio y curado de TBNB) antes de
   salir a buscar fuentes nuevas. No redacta el artículo final.
3. **`blog-redaccion`** — escribe el artículo final con el tono de marca de
   arriba, a partir de la estrategia y la investigación ya hechas.
4. **`blog-revision-seo-calidad`** — revisión final: checklist SEO on-page
   (título, meta descripción, jerarquía de headers, enlaces) y control de
   calidad real de contenido (que no suene a relleno de agencia).

## Cómo está organizada esta carpeta

- `BRIEF.md` — este documento.
- `listado-temas.md` — temas que da `seo-estrategia-senior`, con su prioridad y
  ángulo una vez `blog-estrategia-seo` los trabaja.
- `estado.md` — en qué fase va cada artículo (estrategia → investigación →
  borrador → revisión → publicado).
- `articulos/` — el artículo redactado de cada tema, en markdown.

**Pendiente para arrancar:** Andrea tiene que compartir el listado de temas
de `seo-estrategia-senior` en `listado-temas.md` (o pegarlo directamente) para que
`blog-estrategia-seo` pueda empezar a priorizar.

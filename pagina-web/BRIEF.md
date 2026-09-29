# Página Web TBNB — Brief del proyecto

**Qué es:** desarrollo de contenido para las páginas de servicio de
`thebarnbarconsulting.com`, a partir de briefs ya entregados por el asesor
de SEO externo de TBNB, listo para maquetar en Elementor (herramienta que
usa el equipo internamente para publicar la web).

**Fecha de inicio:** 2026-09-29.

## Por qué existe este proyecto

El asesor de SEO ha identificado dos páginas de servicio con keywords de
alto volumen sin cubrir bien hoy, y ha entregado un brief detallado de cada
una (estructura de encabezados, keywords objetivo, meta etiquetas, enlaces
internos). El contenido que trae el brief está bien pensado en términos de
SEO, pero está escrito con voz de agencia genérica — frases como *"No
somos una gestoría tradicional, somos tu project manager gastronómico"*
suenan a cualquier consultora, no a TBNB. El trabajo de este equipo es
coger esa estructura SEO (que no se toca sin aprobación) y convertirla en
copy real de TBNB, siguiendo la guía de tono oficial.

## Diferencia con `blog-web/`

`blog-web/` es para artículos de blog basados en un listado de temas de
SEO. Este proyecto (`pagina-web/`) es para las **páginas de servicio
principales** de la web — estructura más comercial (CTAs, cross-selling,
silos locales), no artículo editorial. El tono también es distinto: según
la propia guía de marca, **la web es el canal más "cañero" de todos**
(más que el blog), con más actitud y personalidad.

## Fuentes de este proyecto

- `tono-de-marca-tbnb.md` — guía de tono oficial de TBNB (traída de Drive),
  con ejemplos reales de frases sí/no TBNB y el nivel de intensidad por
  canal.
- `diseno-visual-tbnb.md` — paleta de color y tipografía oficiales de
  marca (traídas del "Document Design System TBNB.xlsx" de Drive).
- `seo-briefs/` — los briefs originales del asesor de SEO, uno por página,
  reproducidos tal cual llegaron.
- `hospitality-report/matriz-tematica.md` — por si algún dato de mercado ya
  documentado ahí es aprovechable para dar sustancia real a una afirmación
  (igual que se hace en `blog-web/`).

## Hechos verificados que el equipo puede dar por buenos

- **Religion Coffee** y **Eat My Trip** son proyectos reales de TBNB, con
  ficha propia en la web (`thebarnbarconsulting.com/en/religion-coffee/` y
  `/en/eat-my-trip/`). El brief los cita como ejemplo de "Proyectos
  Destacados" — es correcto usarlos, no hace falta inventar ni verificar
  más.

## Preguntas abiertas — no asumir, confirmar con Andrea/Sergio

1. **"AGENDAR REUNIÓN GRATUITA DE 15 MINUTOS"** aparece en los dos briefs
   como CTA destacado. No se ha confirmado en este proyecto que esa oferta
   (reunión gratuita de 15 min) sea real y esté operativa hoy — antes de
   publicar, Andrea/Sergio deben confirmar que ese compromiso es cierto
   (regla de la casa: "no vendemos humo").
2. **Páginas de destino de los enlaces internos** (`/plan-de-negocio/`,
   `/consultoria-gastronomica/`, `/servicios/consultoria-rrhh-hosteleria/`,
   `/servicios/consultoria-tecnologica-hosteleria/`,
   `/consultoria-hosteleria-barcelona/`, `/consultoria-hosteleria-madrid/`,
   `/proyectos/`) — el equipo no verifica que todas existan ya en el sitio
   en vivo con esa URL exacta; quien suba el contenido a Elementor debe
   comprobarlo antes de enlazar.
3. **Estilos globales de Elementor** — `diseno-visual-tbnb.md` da la
   paleta y tipografía de marca, pero no sustituye una revisión del
   kit/theme de Elementor real del sitio.

## El equipo

Cuatro roles (`.claude/agents/`), en cascada:

1. **`web-estrategia-marca`** — lee el brief SEO de una página, verifica
   qué afirmaciones necesitan respaldo real (o quedan marcadas como
   pregunta abierta), y decide cómo traducir cada bloque de venta genérica
   del brief a un ángulo defendible con la voz real de TBNB, sin tocar la
   estructura SEO (keywords, H-tags, meta, enlaces).
2. **`web-redaccion`** — escribe el copy final de cada bloque, seleccionado
   sección por sección, con la guía de tono (nivel "cañero" de web) y sin
   inventar ninguna cifra o promesa nueva.
3. **`web-maquetacion-elementor`** — convierte el copy final en una
   especificación de maquetación bloque a bloque (tipo de sección,
   contenido de cada widget, notas de diseño con la paleta oficial) lista
   para construir en Elementor.
4. **`web-revision-seo-calidad`** — revisión final: confirma que no se ha
   perdido ninguna keyword/meta/H-tag/enlace del brief original, y que el
   copy pasa el "test TBNB" de la guía de tono (si no pasaría en una
   cocina o una barra, no es TBNB).

**Regla de la casa que aplica igual aquí:** nada se publica en la web en
vivo sin que Andrea o Sergio lo revisen y aprueben antes — el resultado de
este equipo es una especificación lista para maquetar, no una publicación
directa.

## Cómo está organizada esta carpeta

- `BRIEF.md` — este documento.
- `tono-de-marca-tbnb.md`, `diseno-visual-tbnb.md` — referencias de marca.
- `seo-briefs/` — brief original de cada página, tal cual llegó del SEO.
- `paginas/` — copy final y especificación de maquetación de cada página.
- `estado.md` — seguimiento del proceso.

# SEO — Brief del departamento

**Qué es:** el departamento de SEO de The Bar N' Bar, creado a petición de
Andrea el 2026-10-02 para profesionalizar lo que hasta ahora se ha llevado de
forma manual e intuitiva (ver `brief-interno-andrea.md`). Sustituye a Saúl
Felipe Cortés, el colaborador de SEO externo que llevaba esto hasta hoy
(despedido el mismo 2026-10-02) — a partir de ahora, nadie más externo
interviene en SEO salvo este equipo.

**Objetivo principal, en palabras de Andrea:** *"conseguir leads y
conversiones de valor para nuestros servicios de consultoría del BAR
Method"* — no tráfico o posiciones como fin en sí mismo. Cada decisión de
este departamento se evalúa contra ese objetivo, no solo contra volumen de
búsqueda o dificultad de keyword.

**Objetivos de negocio asociados** (de `brief-interno-andrea.md`): a 12 meses,
el SEO debe contribuir a un crecimiento de ventas del 40-50% y convertirse en
el canal de captación nº1 por delante del boca-oreja; a 24 meses, duplicar la
facturación y que TBNB sea la consultora de hostelería más visible de España
en buscadores.

## Cómo está organizada esta carpeta

- `BRIEF.md` — este documento.
- `brief-interno-andrea.md` — transcripción del briefing original de Andrea
  (negocio, buyer persona, diferenciación, competencia, histórico de SEO,
  priorización en 13 puntos, objetivos de crecimiento). Fuente de contexto,
  no se reinterpreta ahí, solo aquí.
- `investigacion-heredada/` — lo que ya existe en Google Drive del trabajo de
  Saúl, resumido y con enlace a la fuente original (no duplicado completo,
  para que no quede desactualizado):
  - `roadmap-y-keyword-research.md` — estado del roadmap, 145 keywords ya
    investigadas, dos propuestas de arquitectura web en silos, backlog de
    comité de contenidos (44 temas) y lead magnets ya pensados por fase del
    BAR Method (idea en papel, pendientes de construir, pensados como imán de
    registro a la newsletter).
  - `auditoria-tecnica-rocket22.md` — auditoría técnica de un proveedor
    anterior (Rocket22); la alerta de seguridad y el favicon que señalaba ya
    están resueltos, según confirma Andrea — queda como registro histórico.
- `blog-web/` y `pagina-web/` — blog y páginas de servicio de la web, ambos
  movidos aquí el 2026-10-02 (antes vivían en la raíz del repositorio). Siguen
  funcionando igual: ver `blog-web/BRIEF.md` y `pagina-web/BRIEF.md`.
- `estado.md` — en qué fase va el departamento.

## El equipo

Seis roles. Los primeros cuatro son los que pidió Andrea explícitamente
(dos con nombre exacto, dos como ejemplo de "otros roles relevantes"); los
últimos dos los añado yo, justificados por hallazgos concretos de la
investigación heredada (ver cada ficha en `.claude/agents/`):

1. **`seo-estrategia-senior`** — Estratega SEO Senior. Dueño del "qué y por
   qué": keyword research, arquitectura en silos, mapeo por fase del funnel,
   análisis de competencia, KPIs a 3/6/12 meses. Decide qué página o artículo
   se trabaja primero en todo el departamento.
2. **`seo-arquitectura-web`** — Director/a de Arquitectura Web. Dueño de la
   estructura técnica: silos de URL, enlazado interno, salud técnica
   (Core Web Vitals, indexación, sitemap, robots.txt, hreflang ES/EN),
   coordina con freelances de IT ya que TBNB no tiene equipo propio.
3. **`seo-redaccion`** — Director/a de Redacción SEO. Control de calidad de
   tono y de E-E-A-T en todo lo que se publica (blog + páginas de servicio):
   autoría firmada, biografías reales, y el manual de uso de IA con límites
   claros que pide explícitamente el briefing de Andrea. No sustituye a
   `blog-redaccion` ni a `web-redaccion` — los supervisa y alinea.
4. **`seo-diseno-web`** — Director/a de Diseño Web. Dueño del sistema de
   plantillas (Home, Servicios, Artículos — la tarea "Mejoras de plantillas"
   que sigue pendiente en el roadmap heredado) a nivel visual/UX, coordinado
   con la guía de marca. No sustituye a `web-maquetacion-elementor`, que
   sigue maquetando página a página.
5. **`seo-analitica-conversion`** — Analista de Datos y Conversión. Propuesta
   propia: el briefing de Andrea señala como gap estructural que no hay
   atribución de canal (SEO vs. Ads vs. boca-oreja), ni GA4 con eventos de
   conversión, ni CRM. Como el objetivo explícito es "leads y conversiones",
   no solo posiciones, alguien tiene que ser dueño de medirlo y de los lead
   magnets ya pensados en `investigacion-heredada/` (auditorías, quiz de
   diagnóstico).
6. **`seo-autoridad-local`** — SEO Local y Autoridad de Dominio. Propuesta
   propia: la auditoría de Rocket22 confirma que la web no tiene backlinks
   reales, y el propio briefing de Andrea marca el SEO local (Google Business
   Profile, citas, reseñas) como la vía más rápida de resultados en
   Madrid/Barcelona. Nadie en el equipo tenía este frente como responsabilidad
   explícita.

## Reglas que ya aplican aquí

- Mismo tono de marca que el resto del proyecto — "menos teoría, más barra",
  Salero, cercanía (ver `brief-interno-andrea.md`, sección de diferenciación).
- Nunca se publica nada sin aprobación de Andrea o Sergio — igual que en el
  resto del repositorio.
- El manual de uso de IA que pide Andrea (punto 10 de su priorización) está
  pendiente de redactar — es una tarea temprana de `seo-redaccion`, no una
  regla que ya exista.

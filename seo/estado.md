# Estado — Departamento de SEO

**Última actualización:** 2026-10-02.

## Fase actual

**Montaje del departamento.** Hoy se ha creado la estructura de carpetas, el
equipo de especialistas (`.claude/agents/`) y se ha analizado todo el material
heredado disponible (briefing de Andrea + Google Drive). Todavía no se ha
empezado a trabajar ninguna estrategia ni contenido nuevo.

## Qué se ha hecho hoy (2026-10-02)

- Leído el briefing interno de Andrea (`brief-interno-andrea.md`).
- Revisada la carpeta `09_SEO` de Google Drive y documentos relacionados:
  roadmap/keyword research de Saúl Felipe Cortés (colaborador de SEO externo
  de TBNB hasta hoy), auditoría técnica de Rocket22 (anterior a ese roadmap),
  carpeta de blogs 2026 (coincide con `blog-web/articulos/` ya existente).
- Movida `blog-web/` a `seo/blog-web/` y `pagina-web/` a `seo/pagina-web/`,
  con todas las referencias de ruta corregidas en agentes y documentos — todo
  el trabajo de SEO/web vive ya en un único sitio.
- Creados 6 agentes nuevos del departamento (ver `BRIEF.md`).
- Confirmado con Andrea (2026-10-02): Saúl Felipe Cortés era el colaborador
  de SEO externo, despedido hoy — `seo-estrategia-senior` toma el relevo de
  su rol directamente, sin que quede nadie más tocando SEO desde fuera. La
  alerta de seguridad de la auditoría de Rocket22 y el problema del favicon
  **ya estaban resueltos** (la auditoría de Rocket22 es más antigua de lo que
  parecía). Elena/Yair son colaboradores externos de pastelería (no equipo
  interno). Los lead magnets de `PLANTILLAS_TBNB` son solo idea en papel —
  el objetivo es usarlos como imán de registro a la newsletter para construir
  base de datos de contactos, no solo como descarga suelta.

## Decisiones de Andrea (2026-10-07)

1. **El research de Saúl es el válido.** Se construye sobre él, no se
   rehace desde cero. Pendiente: análisis de competencia (no se había
   hecho todavía) — encargado a `seo-estrategia-senior`, foco en
   Ansón+Bonet, ver `seo/analisis-competencia.md` en cuanto esté listo.
2. **Blogs:** los 5 con redacción final se publican la semana del
   2026-10-13 (pendiente aún de que `blog-revision-seo-calidad` dé el
   visto bueno final, ver `seo/blog-web/estado.md`).
3. **Medición: sin conector.** Andrea/Sergio pasarán manualmente datos de
   Google Analytics/Search Console cuando toque — no se conecta ninguna
   cuenta (regla de la casa). Plantilla de qué datos hacen falta en
   `seo/plantilla-datos-medicion.md`, cadencia mensual (mismo ritmo que el
   dashboard de marketing).
4. RankTank: explicado qué es y cómo corregirlo — ver
   `seo/plantilla-datos-medicion.md` o la respuesta directa a Andrea
   (herramienta ya configurada, solo mal regionalizada: Locale/Language
   en inglés/EEUU en vez de español/España).

## Pendiente antes de poder empezar a dar forma a la estrategia

~~1. Acceso a herramientas de medición~~ — resuelto arriba (sin conector,
   paso manual).
~~2. Decidir si se sigue con lo heredado de Saúl o se rehace~~ — resuelto
   arriba (se sigue con lo heredado).
3. Corregir la cuenta de RankTank (mal configurada en inglés/EEUU) — Andrea
   tiene las instrucciones, pendiente de que alguien con acceso al Sheet lo
   aplique.
4. Validar los 6 roles del equipo antes de empezar a producir con ellos.

## Próximos pasos recomendados, en orden

1. **Validar la arquitectura y el keyword research heredados de Saúl**
   (`seo-estrategia-senior`) — no es investigación desde cero, es revisar 145
   keywords y dos propuestas de silo ya hechas, decidir qué se mantiene y
   detectar contradicciones entre ambas versiones. Primer paso porque todo lo
   demás depende de tener esto cerrado.
2. **Decidir el acceso a medición** (Andrea/Sergio) — mientras no haya GA4 y
   Search Console accesibles (ver opciones arriba), `seo-analitica-conversion`
   no puede avanzar en atribución real, aunque sí puede ir especificando qué
   eventos hacen falta.
3. **Análisis de competencia**, con foco en Ansón+Bonet (`seo-estrategia-senior`).
4. **Retomar el comité de contenidos** heredado (44 temas, 4 ya escritos) y
   decidir los siguientes 3-4 artículos a producir (`seo-estrategia-senior` →
   `blog-estrategia-seo`).
5. **Especificar los lead magnets como imán de newsletter** — contenido,
   mecánica de entrega y conexión con la herramienta de email marketing
   (`seo-analitica-conversion` con `seo-redaccion`/`seo-diseno-web`).
6. **Manual de uso de IA** (`seo-redaccion`) — antes de producir contenido
   nuevo en volumen, no después.
7. **SEO local y autoridad de dominio** (`seo-autoridad-local`) — Google
   Business Profile, citas locales, backlinks reales en Madrid/Barcelona.
8. **Auditoría técnica a fondo** (`seo-arquitectura-web`) — Core Web Vitals,
   estructura de URLs, enlazado; corregir también la configuración de
   RankTank.
9. **KPIs a 3/6/12 meses** (`seo-estrategia-senior` con `seo-analitica-conversion`)
   — último paso porque necesita que medición (paso 2) ya esté decidida para
   ser realista, no aspiracional.

## Fases del proceso (a definir con `seo-estrategia-senior`)

- [ ] **Medición y atribución** — implementar GA4 con eventos de conversión,
      Search Console, campo "¿cómo nos conociste?" en el formulario de
      contacto (bloqueado hasta resolver el punto 1 de arriba).
- [ ] **Validar o rehacer** la arquitectura en silos y el keyword research
      heredados de Saúl.
- [ ] **Análisis de competencia** (Ansón+Bonet como referencia principal).
- [ ] **Manual de uso de IA** para contenido SEO.
- [ ] Retomar el comité de contenidos (44 temas, solo 4 ya escritos).
- [ ] **Especificar los lead magnets como imán de newsletter** (contenido +
      mecánica de entrega + conexión con el proveedor de email marketing) —
      tarea de `seo-analitica-conversion` con `seo-redaccion`.
- [ ] KPIs a 3/6/12 meses.
- [ ] Auditoría técnica a fondo (Core Web Vitals, estructura de URLs,
      enlazado) — la de Rocket22 es un chequeo general, no la auditoría
      completa que pide el punto 5 del briefing de Andrea.

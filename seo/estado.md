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
  roadmap/keyword research del gestor de SEO externo, auditoría técnica de
  Rocket22, carpeta de blogs 2026 (coincide con `blog-web/articulos/` ya
  existente).
- Movida `blog-web/` a `seo/blog-web/` y corregidas todas las referencias de
  ruta en agentes y documentos.
- Creados 6 agentes nuevos del departamento (ver `BRIEF.md`).

## Pendiente antes de poder empezar a dar forma a la estrategia

Ver la lista completa de preguntas abiertas en el mensaje de entrega a
Andrea — resumen aquí para no perderlas:

1. Confirmar quién es "el chico" que llevaba el SEO (¿el dueño del roadmap de
   Drive, alguien de Rocket22, u otra persona?) y si sigue teniendo acceso a
   algo que debamos recuperar.
2. Verificar en la web real si el favicon sigue roto (contradice lo marcado
   como "Implementado" en el roadmap heredado).
3. Investigar la alerta de seguridad de Rocket22 (backlinks sospechosos,
   posible SEO negativo o malware) — prioridad antes que cualquier otra
   tarea técnica.
4. Decidir si `pagina-web/` se mueve también dentro de `seo/`.
5. Confirmar si los lead magnets de `PLANTILLAS_TBNB` (auditorías, quiz de
   diagnóstico) existen ya construidos en algún sitio o son solo idea.
6. Aclarar quiénes son "Elena/Yair" y "Aleix", mencionados en la propuesta de
   arquitectura web heredada como posibles especialistas de contenido
   (pastelería/postres, sumillería).
7. Acceso real a herramientas: Google Analytics 4, Search Console, Google
   Business Profile, y la cuenta de RankTank (mal configurada en inglés/EEUU).
8. Decidir si se sigue construyendo sobre la arquitectura/keyword research ya
   heredada, o se vuelve a investigar desde cero con este equipo.

## Fases del proceso (a definir con `seo-estrategia-senior`)

- [ ] **Auditoría técnica real** (velocidad, indexación, Core Web Vitals,
      estructura de URLs) — punto 5 del briefing de Andrea, no cubierto a
      fondo todavía por la auditoría de Rocket22.
- [ ] **Medición y atribución** — implementar GA4 con eventos de conversión,
      Search Console, campo "¿cómo nos conociste?" en el formulario de
      contacto.
- [ ] **Validar o rehacer** la arquitectura en silos y el keyword research
      heredados.
- [ ] **Análisis de competencia** (Ansón+Bonet como referencia principal).
- [ ] **Manual de uso de IA** para contenido SEO.
- [ ] Retomar el comité de contenidos (44 temas, solo 4 ya escritos).
- [ ] KPIs a 3/6/12 meses.

## Pendiente de decisión con Andrea

- Si `pagina-web/` se integra dentro de `seo/`.
- Validar los 6 roles del equipo antes de empezar a producir con ellos.
- Confirmar las preguntas abiertas de la sección anterior.

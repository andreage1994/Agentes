# Recap de Saúl (2026-10-07) — incorporado a la estrategia

Último mensaje de Saúl (excolaborador de SEO externo), pasado por Andrea.
Cruzado contra la hoja heredada real (`Roadmap`, `Prompts Otterly`) y el
resto de lo ya documentado en `seo/`. Los 5 puntos de su recap coinciden,
uno a uno, con tareas que él mismo ya tenía marcadas como **"Pte SEO"**
(pendientes) en su propio roadmap — no es una lista nueva, es el cierre
de lo que ya estaba previsto.

## 01. Pop-up de Mailchimp — listo, falta revisar y publicar

Ya está montado en Elementor
(`?post_type=elementor_library&p=5014`), solo falta ajustar detalles y
publicarlo. Conecta directo con el pendiente ya anotado en
`seo/estado.md` ("especificar los lead magnets como imán de newsletter")
— esta pieza concreta ya está resuelta en el lado técnico, falta
decisión de contenido/aprobación de Andrea/Sergio.

**Acción:** revisar el pop-up y darle a publicar.

## 02. Páginas de servicio — publicar y enlazar desde páginas existentes

Saúl pide explícitamente que, al publicar, se enlacen desde las propias
páginas de la web (con módulos adicionales o reaprovechando los
existentes) — **esto es justo lo que faltaba en el diagnóstico de hoy**:
`/marketing-gastronomico/` salió como "unknown to Google" en Search
Console, posiblemente por ser una página sin enlaces internos
apuntándola (ver `diagnostico-traspasos-marketing-gastronomico.md`).

**Acción:** al construir en Elementor las páginas ya listas (Ola 2 del
plan de acción), no publicarlas sueltas — añadir el enlazado interno
desde Home/Servicios en el mismo paso, no como tarea aparte después.

## 03. Blog — cadencia de publicación, decisión pendiente

Saúl sugiere publicar en flujo constante, **uno cada semana o cada dos
semanas**, en vez de todos a la vez. Esto coincide con su propio roadmap
("Comité de contenidos: 2-3/mes"). **Esto entra en conflicto con lo ya
decidido por Andrea** (publicar los 5 artículos juntos la semana del
13) — no lo cambio por mi cuenta, lo dejo como decisión explícita:
¿publicáis los 5 juntos como estaba previsto, o se reparten en las
próximas 3-5 semanas siguiendo el ritmo que recomienda Saúl?

## 04. Nueva versión de Home — en borrador, pendiente de revisión crítica

Hay una propuesta de Home nueva ya en **Páginas → Borradores** de
WordPress, con bloques nuevos. Saúl sugiere publicarla directamente como
home definitiva. **Antes de aprobarlo a ciegas, esto hay que revisarlo
contra el hallazgo de hoy**: el Home actual tiene un problema de
canibalización confirmado parcialmente — "consultoria hosteleria"
(960/mes, su keyword de mayor volumen) no se sabe todavía si rankea bien
desde el Home o no (pendiente el escaneo limpio de RankTank, ver
`medicion-mensual.md`). Publicar una Home nueva sin comprobar que
mantiene o mejora esto podría tapar el problema en vez de resolverlo, o
resolverlo sin que nadie confirme que fue por eso.

**Acción antes de publicar:** que alguien (Andrea/Sergio o
`seo-arquitectura-web`) revise el borrador y confirme que el Title, H1 y
contenido principal siguen apuntando a "consultoria hosteleria" /
"asesoria hosteleria" de forma clara, no solo que "se ve mejor a nivel
diseño".

## 05. Visibilidad en IA (Otterly) — prompts ya definidos, falta validarlos y crear la demo

Ya existen **15 prompts reales** en la pestaña "Prompts Otterly" del
Sheet heredado (leído directamente, no estimado) — preguntas tipo "¿Qué
consultora gastronómica me recomiendas para mejorar un restaurante?"
pensadas para ver si TBNB aparece quuan alguien pregunta esto a
ChatGPT/IA en vez de buscarlo en Google. Esto conecta con un dato real
que ya teníamos: en septiembre, `chatgpt.com/ai-assistant` generó 6
sesiones reales al sitio (ver `medicion-mensual.md`) — ya hay tráfico
real desde IA, aunque sea pequeño.

**Lista completa de los 15 prompts** (keyword base · localidad ·
prompt):
1. consultoria hosteleria (Nacional) — "¿Cuáles son las mejores consultoras de hostelería en España?"
2. consultoria restaurantes (Nacional) — "¿Qué consultora especializada en restaurantes me recomiendas en España?"
3. consultoria gastronomica (Nacional) — "¿Qué consultora gastronómica me recomiendas para mejorar un restaurante?"
4. asesoria especializada en restauracion y hosteleria (Nacional) — "¿Qué empresa ofrece asesoría integral para restaurantes y negocios de hostelería?"
5. consultoria para restaurantes (Nacional) — "¿Qué consultora me recomiendas para mejorar la gestión y rentabilidad de un restaurante?"
6. asesor de restaurantes (Nacional) — "Mi restaurante factura bien pero tiene poca rentabilidad. ¿Qué consultora especializada puede ayudarme?"
7. asesoria de restaurantes (Nacional) — "Tengo un restaurante y quiero reducir costes y mejorar márgenes. ¿Qué consultora me recomiendas?"
8. consultor de restaurantes (Nacional) — "Tengo un restaurante que funciona, pero quiero profesionalizar la gestión. ¿Qué empresa puede ayudarme?"
9. consultoria negocio bar (Nacional) — "Tengo un bar y quiero mejorar costes, operaciones y rentabilidad. ¿Qué consultora especializada me recomiendas?"
10. asesoria para abrir un restaurante (Nacional) — "Quiero abrir un restaurante desde cero. ¿Qué consultora puede acompañarme durante todo el proceso?"
11. auditoria para restaurantes (Nacional) — "¿Qué empresa puede hacer una auditoría de mi restaurante para detectar problemas de rentabilidad?"
12. asesoria gastronomica para restaurantes (Nacional) — "Quiero mejorar la propuesta gastronómica, la carta y la operativa de mi restaurante. ¿Qué asesoría me recomiendas?"
13. consultoria para restaurantes (Nacional, expansión) — "Quiero expandir mi restaurante y abrir nuevos locales. ¿Qué consultora especializada puede ayudarme?"
14. consultoria hosteleria barcelona (Barcelona) — "¿Qué consultora de hostelería me recomiendas en Barcelona para mejorar la gestión de un restaurante?"
15. asesoria para abrir un restaurante madrid (Madrid) — "Quiero abrir un restaurante en Madrid. ¿Qué consultora me recomiendas para ayudarme con la puesta en marcha?"

**Acción:** validar que estos 15 siguen teniendo sentido (todos "Alta"
prioridad según la hoja, ninguno marcado para revisar) y crear la cuenta
demo gratuita en Otterly para lanzarlos. Es trabajo nuevo, no estaba en
el plan de acción anterior — lo añado como punto nuevo.

## Resumen de decisiones que necesito de Andrea/Sergio

1. Pop-up Mailchimp: ¿aprobado para publicar tal cual, o hay que
   ajustar algo antes?
2. Blog: ¿los 5 juntos la semana del 13 (como ya decidido), o en goteo
   semanal/quincenal (como sugiere Saúl)?
3. Home nueva: ¿quién la revisa antes de publicar — vosotros,
   `seo-arquitectura-web`, o ambos?
4. Otterly: ¿seguimos adelante con los 15 prompts tal cual están, o
   queréis revisarlos primero?

# Marketing TBNB — panel de estado

**Pedido por Andrea, 2026-10-05.** Andrea pidió un dashboard para organizar
la estructura actual de marketing de TBNB (no de un cliente — de la propia
consultora), con un analista de marketing guiando qué información hace
falta, quién debería estar en el equipo, y cómo seguir construyendo.

**Dashboard:** <https://claude.ai/artifact/ANXczpeaLq1udVFrStyNNT>

Construido con datos reales ya documentados en el repo (no estimados):
`comunicacion-redes-sociales/estado.md`, `seo/estado.md`,
`comunicacion-redes-sociales/potential-spotting/estado.md`,
`equipo-tbnb.md`. Ningún número del panel está inventado — los conteos
(canales, piezas en pipeline, bloqueantes) son literales de esos
documentos. Donde no hay dato real (métricas de alcance, tráfico,
conversión), el panel lo marca como hueco en vez de rellenarlo.

## Lectura como analista de marketing

**Lo que ya existe, funciona como sistema.** TBNB tiene 7 canales/proyectos
activos documentados (Instagram, LinkedIn, Google My Business, email
marketing, SEO/web, Potential Spotting, Hospitality Report), cada uno con
su propio equipo de especialistas TBNB produciendo borradores. El cuello de
botella no es de producción de contenido — es de **aprobación humana**
(todo pasa por Andrea/Sergio, regla de la casa) y de **medición** (cero
canales con métrica real accesible hoy).

**El hueco más importante: nadie del equipo humano tiene asignada la
analítica.** Existe el rol a nivel de especialista TBNB
(`seo-analitica-conversion`), pero sin datos reales sobre los que trabajar
y sin una persona del equipo que lo posea. Mientras esto no se resuelva,
ningún dashboard de marketing puede evolucionar de "mapa de estructura" a
"panel de resultados".

**Equipo recomendado, sobre lo que ya hay (no una propuesta desde cero):**

| Función | Responsable humano hoy | Hueco |
|---|---|---|
| Dirección de marketing | Sergio Alonso | — |
| Contenido RRSS | Laura Callejo (a confirmar — su título es "Marketing Specialist", no hay confirmación explícita de que ejecute el contenido) | — |
| SEO / contenido web | — | Sin responsable humano asignado |
| Diseño / identidad visual | Ava Caughron | — |
| Analítica / conversión | — | Sin responsable humano asignado, sin datos |
| Editorial / posicionamiento (Hospitality Report) | Sergio + Andrea | — |
| Aprobación de marca | Andrea + Sergio | — |

## Próximos 3 pasos recomendados

1. **Resolver el acceso a medición** (GA4, Search Console, métricas de RRSS)
   — ya documentado como bloqueante en `seo/estado.md`, es la decisión que
   más desbloquea.
2. **Fijar el objetivo de negocio del marketing** — leads cualificados,
   autoridad de marca, o ambos con qué peso — para poder priorizar entre
   los 7 canales con criterio.
3. **Asignar un responsable humano de analítica.**

## Huecos de información pendientes de Andrea/Sergio

Replicados del panel (ahí quedan marcables con checkbox, por viewer, sin
que se guarde en el repo):

- Métricas actuales por canal (seguidores, alcance, engagement, tráfico).
- Objetivo de negocio del marketing.
- Presupuesto.
- Público objetivo preciso (¿mismo perfil que Potential Spotting, o más
  amplio?).
- Capacidad real del equipo (horas/semana de Laura y Ava).
- Herramientas en uso más allá de Mailchimp y RankTank.

## Propuesta de primeros 3 pasos (2026-10-07)

Andrea planteó si hace falta contratar a alguien de marketing, un
consultor externo, o apoyarse en Claude. **Esta propuesta no responde esa
pregunta todavía — es el paso previo**: sin acceso a datos ni un objetivo
fijado, cualquier persona nueva (interna, externa o IA) estaría
ejecutando a ciegas igual que ahora, solo que más cara. La decisión de
contratar se retoma al cierre del paso 3.

**Paso 1 — Resolver el acceso a medición**
- Qué: recuperar/activar acceso real a GA4 y Search Console de la web
  (ya marcado como bloqueante en `seo/estado.md`), a los insights nativos
  de Instagram/LinkedIn/Google My Business, y a los informes de Mailchimp
  del email marketing.
- Quién: Sergio — es quien lleva IT/Admin según el reparto de la casa
  (`CLAUDE.md`), y por tanto quien tiene o puede recuperar los accesos de
  las cuentas.
- Entregable: una lista de qué canal tiene acceso y cuál no, en una
  semana. No hace falta analizar nada todavía, solo tener la llave.
- **No se conecta ninguna cuenta nueva sin pedirlo explícitamente en el
  momento** (regla de la casa) — este paso es recuperar acceso a lo que
  ya existe, no dar de alta herramientas nuevas.

**Paso 2 — Fijar el objetivo de negocio del marketing**
- Qué: una decisión corta entre Andrea y Sergio — ¿el marketing de TBNB
  busca leads cualificados, autoridad de marca, o ambos con qué peso? Y,
  con eso decidido, qué canal de los 7 sirve principalmente a cuál
  objetivo (p. ej. Potential Spotting y email → leads directos;
  Hospitality Report y LinkedIn → autoridad; Instagram/GMB → mixto).
- Quién: Andrea + Sergio. Es una decisión de dirección, no algo que se
  pueda inferir de los documentos ya existentes.
- Entregable: 3-4 frases por escrito (puede ser una nota corta en este
  mismo documento) fijando el objetivo y el peso por canal.
- Puede hacerse en paralelo al paso 1 — no dependen entre sí.

**Paso 3 — Asignar un responsable humano de analítica**
- Qué: decidir quién posee la analítica de marketing de forma continua —
  no solo mirar los números una vez, sino revisarlos con regularidad y
  usarlos para decidir qué canal priorizar.
- Quién podría ser: Laura Callejo si tiene capacidad real (su rol de
  "Marketing Specialist" no tiene confirmado si incluye analítica),
  Sergio de forma temporal mientras se decide, o aquí es donde entra la
  pregunta de Andrea sobre contratar — con el acceso a datos (paso 1) y
  el objetivo (paso 2) ya resueltos, se puede valorar con criterio si
  hace falta una persona nueva (interna o consultor externo) o si el
  equipo actual puede absorberlo.
- Depende de los pasos 1 y 2 — no tiene sentido asignarlo antes, porque
  no habría ni datos ni objetivo sobre los que trabajar.

**Orden recomendado:** 1 y 2 en paralelo esta semana → 3 en la siguiente,
con la decisión de contratar (o no) como resultado directo de cómo quede
el paso 3, no como un paso aparte.

## Siguiente actualización

Este documento y el panel deberían revisarse cuando Andrea/Sergio
respondan a los huecos de arriba — en ese momento el panel puede pasar de
estado/estructura a incluir métricas reales.

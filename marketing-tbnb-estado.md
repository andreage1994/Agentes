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

## Siguiente actualización

Este documento y el panel deberían revisarse cuando Andrea/Sergio
respondan a los huecos de arriba — en ese momento el panel puede pasar de
estado/estructura a incluir métricas reales.

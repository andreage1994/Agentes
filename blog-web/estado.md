# Estado — Blog Web TBNB

**Fecha de arranque:** 2026-09-28.

## Situación actual

`blog-estrategia-seo` ha completado la primera pasada sobre los 7 temas
entregados por el gestor de SEO en `listado-temas.md`: intención de
búsqueda, ángulo TBNB, título (H1), subtemas (H2) y prioridad de trabajo
(calidad de ángulo, no volumen de tráfico). Los 7 temas quedan listos para
pasar a `blog-investigacion`.

Ningún tema se marcó como "sin ángulo" — para los temas 3 y 4 (programas
comerciales de Estrella Galicia y Mahou), que llevaban aviso explícito de
riesgo de publirreportaje, se encontró un ángulo independiente defendible
(qué mirar antes de firmar, qué se cede y cuándo compensa). El tema 7
(APPCC) es el que tiene el ángulo más modesto de los siete: correcto y
honesto, pero más utilitario que diferenciador.

`blog-investigacion` ha entregado el brief del Tema 6 (diseño de carta):
los dos hallazgos del Hospitality Report citados en el ángulo se verifican
correctos, con el matiz de que la tensión "raciones grandes vs. pequeñas"
está marcada en origen como hipótesis sin cerrar, no como dato asentado.
Ver `blog-web/investigacion/tema-06-diseno-carta.md`.

`blog-investigacion` ha entregado también el brief del Tema 5 (escandallos
y food cost): el dato de Inpulse.ai se verificó directamente en
`hospitality-report/matriz-tematica.md` (se sostiene tal cual, con el
matiz de que es mercado francés, no español, y con contexto adicional
sobre márgenes netos del 3-4% incluso en negocios con estrella Michelin).
Todas las fuentes externas nuevas de mercado en español (qamarero,
hosteltur, mercasa, etc.) dieron `EGRESS_BLOCKED` esta sesión — el brief
reconstruye lo esencial vía `WebSearch` y lo marca explícitamente, incluido
un dato reciente de España 2025 (rentabilidad de restauración -0,9% en
2025 pese a crecer ingresos 3,1%, vía Hosteltur/Anuario de la Hostelería de
España) y un ejemplo numérico de escandallo construido para el brief (no
sourced, solo aplicación de la fórmula). Se han encontrado además varios
artículos reales ya publicados en `thebarnbarconsulting.com` que sirven de
enlace interno directo, con aviso de posible canibalización SEO con "Cómo
calcular la rentabilidad de un negocio de hostelería". Ver
`blog-web/investigacion/tema-05-escandallos-food-cost.md`.

`blog-investigacion` ha entregado los briefs de los Temas 2, 3 y 4 (bloque
"ayudas de proveedores"), con el visto bueno explícito de Andrea para seguir
con el ángulo independiente de consultoría. El hallazgo más importante de
este bloque, que **`blog-estrategia-seo` y `blog-redaccion` deben tener en
cuenta antes de redactar**: no hay evidencia pública de que "Estrella
Galicia te monta el bar" ni "Mahou te monta el bar" / "Bar Uno" sean nombres
oficiales de un producto con condiciones publicadas por las marcas. Lo que
Estrella Galicia comunica con nombre propio es "The Hop" (emprendimiento) y
"Cervecerías Circulares" (sostenibilidad); lo que Mahou-San Miguel comunica
con nombre propio es "+Bar" / "Nexho" / "Más con Mahou San Miguel" (no
existe ninguna evidencia de una plataforma llamada "Bar Uno"). La práctica
de "ayuda a cambio de exclusividad" sí existe y está documentada, pero por
fuentes de mercado de terceros (blogs de proveedores/software), no por las
marcas mismas — el ángulo "abogado del hostelero" se mantiene y se refuerza
con esto (justo porque no hay condiciones públicas, hace falta preguntar
antes de firmar), pero la letra pequeña (duración, exclusividad,
penalizaciones) debe presentarse como "práctica habitual del sector",
nunca como si fuera confirmada y específica de una marca. Se encontró un
dato duro y 100% verificable con fecha que sostiene bien la sección de
"letra pequeña" de los tres artículos: el Reglamento (UE) 2022/720 de la
Comisión (10 may 2022, en vigor desde el 1 jun 2022) limita a 5 años la
cobertura de la exención de competencia para cláusulas de exclusividad en
acuerdos verticales, salvo que el local sea propiedad/arrendado por el
proveedor. Ver los tres briefs para el detalle completo y el resto de
matices (financiación ICO, renting, subvenciones autonómicas dispersas).
`estrellagalicia.es`, `mahou-sanmiguel.com`, `masconmahousanmiguel.com`,
`feyma.com`, `qamarero.com` y `boe.es` dieron `EGRESS_BLOCKED` en esta
sesión — todo lo anterior se reconstruyó vía `WebSearch` y se marca así en
cada brief. No se pudo revisar `clientes/*/fase-a-investigacion-mercado.md`
por falta de herramienta de listado de directorios en esta tarea.

## Seguimiento por artículo

Fases: 🟡 Estrategia (ángulo definido) → 🟡 Investigación → 🟡 Borrador →
🟡 Revisión → 🟢 Publicado.

| Tema | Fase | Artículo | Notas |
|---|---|---|---|
| 1. Licencias para abrir un restaurante | 🟡 Estrategia (ángulo definido) | — | Prioridad de trabajo: Media. Ángulo: secuenciación estratégica antes de firmar el local, no listado de trámites. |
| 2. Ayudas de proveedores para montar un bar | 🟡 Investigación | [`blog-web/investigacion/tema-02-ayudas-proveedores.md`](investigacion/tema-02-ayudas-proveedores.md) | Prioridad de trabajo: Media-alta. Dato legal sólido y citable (Reglamento UE 2022/720, límite de 5 años a la exclusividad). Financiación ICO y renting confirmados como alternativas, con aviso de verificar cifra exacta del ICO (fuente de agregador, no ico.es). Subvenciones públicas: dispersas por comunidad autónoma, sin programa único nacional. |
| 3. Ayudas de Estrella Galicia | 🟡 Investigación | [`blog-web/investigacion/tema-03-estrella-galicia.md`](investigacion/tema-03-estrella-galicia.md) | Prioridad de trabajo: Alta. **Aviso importante:** no hay evidencia de que sea un programa oficial con ese nombre — lo oficial y verificable es "The Hop" y "Cervecerías Circulares", que no son lo mismo. La letra pequeña (exclusividad, duración 5-10 años, penalizaciones) es patrón de mercado documentado por terceros, no confirmado por la marca — presentarlo así en el artículo. |
| 4. Ayudas de Mahou | 🟡 Investigación | [`blog-web/investigacion/tema-04-mahou.md`](investigacion/tema-04-mahou.md) | Prioridad de trabajo: Alta. **Aviso importante:** no existe evidencia de una plataforma llamada "Bar Uno" — lo verificable es "+Bar" / "Nexho" / "Más con Mahou San Miguel". Una fuente (Nexho) afirma que la exclusividad "está prohibida en España", lo cual es impreciso frente al Reglamento UE 2022/720 (está limitada a 5 años, no prohibida) — no repetir esa afirmación en el artículo. |
| 5. Escandallos y food cost | 🟡 Investigación | [`blog-web/investigacion/tema-05-escandallos-food-cost.md`](investigacion/tema-05-escandallos-food-cost.md) | Dato Inpulse.ai verificado y ampliado (margen neto 3-4% incluso en negocios con estrella Michelin; es mercado francés, no español). Rangos de food cost por tipo de negocio y ejemplo de escandallo paso a paso reconstruidos vía `WebSearch` (fuentes de mercado bloqueadas por egress esta sesión). Dato España 2025 (Hosteltur): rentabilidad de restauración -0,9% pese a crecer ingresos 3,1%. Enlaces internos reales encontrados en `thebarnbarconsulting.com`, con aviso de posible canibalización SEO con artículo ya publicado sobre rentabilidad. |
| 6. Diseño de carta de restaurante | 🟡 Investigación | [`blog-web/investigacion/tema-06-diseno-carta.md`](investigacion/tema-06-diseno-carta.md) | Ángulo verificado contra `hospitality-report/matriz-tematica.md`: se sostiene, con matiz sobre la tensión "raciones grandes vs. pequeñas" (hipótesis, no cerrada en origen) y sobre que la matriz clásica de ingeniería de menú aplica mejor a carta con reserva que a bar de tapas. Listo para pasar a `blog-redaccion` junto con el Tema 5 (enlace interno cruzado entre ambos). |
| 7. Sanidad y APPCC | 🟡 Estrategia (ángulo definido) | — | Prioridad de trabajo: Media. Ángulo operativo honesto (tenerlo vs. usarlo), sin dato propio fuerte que citar. |

## Próximo paso

Los Temas 2, 3, 4, 5 y 6 ya están investigados. Los Temas 5 y 6 pueden pasar
a `blog-redaccion` juntos (se enlazan entre sí); antes de redactar,
`blog-estrategia-seo` debería revisar el aviso de posible canibalización
SEO del Tema 5. Para el bloque 2/3/4, antes de pasar a redacción conviene
que `blog-estrategia-seo` decida cómo encajar el aviso sobre nombres de
programa no verificados (especialmente "Bar Uno", que no existe con ese
nombre) sin perder el ángulo independiente ya aprobado por Andrea — lo más
seguro es ajustar cómo se nombra el programa en el propio título/entradilla
sin tocar el H1 ya aprobado más de lo necesario, o confirmarlo primero
verificando directamente `estrellagalicia.es` y `mahou-sanmiguel.com` (ambos
bloqueados en esta sesión de investigación). Queda pendiente solo el Tema 1
y el Tema 7 (prioridad Media).

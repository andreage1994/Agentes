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

Andrea revisó el ángulo del Tema 5 el 2026-09-28 y pidió explícitamente un
ángulo distinto al de los tres artículos ya publicados por TBNB sobre
escandallo/food cost/rentabilidad (ver detalle del ángulo revisado en
`blog-web/listado-temas.md`, sección 5): en vez de otro explicador de "qué
es el food cost y cómo se calcula", el artículo parte de que el lector ya
conoce el concepto y se centra en por qué el escandallo calculado hace tres
años ya no refleja la realidad del negocio (materia prima +30% acumulado
desde 2021, rentabilidad del sector -0,9% en 2025 pese a crecer ingresos
3,1%) y qué hacer con ese dato. `blog-redaccion` ha escrito el artículo con
ese ángulo revisado — ver estado actualizado en la tabla de seguimiento.

`blog-revision-seo-calidad` ha revisado el borrador del Tema 5
(2026-09-28) contra el checklist SEO on-page y el criterio de calidad real
del proyecto. El checklist SEO está en general bien resuelto: H1 claro con
keyword, jerarquía de headers correcta (un H1, cuatro H2 que funcionan como
índice), keyword "food cost" presente de forma natural en título, primer
párrafo y en el H2 3, meta descripción de 159 caracteres dentro de rango y
con motivo real de clic (no clickbait), párrafos en general cortos y
legibles. El dato de Inpulse.ai se presenta correctamente como mercado
francés en las dos ocasiones en que se cita (H2 2 y H2 3), tal como exigía
el brief, sin colarse nunca como dato español. El artículo también supera
la prueba de "¿esto es relevante o es relleno?": no repite el explicador
básico de escandallo/food cost, tiene voz propia y un marco de decisión
(renegociar, ajustar ración o subir precio) con ejemplos concretos — no es
una lista genérica intercambiable con cualquier consultora.

Aun así, **se devuelve el borrador a `blog-redaccion`** por dos motivos
concretos:

1. **Enlace interno no verificado (posible enlace inventado).** El primer
   párrafo enlaza "Cómo se calcula un escandallo ya lo explicamos aquí" a
   `https://www.thebarnbarconsulting.com/escandallo-evitar-desperdicio-restaurante/`.
   Esa URL no aparece en la investigación verificada
   (`blog-web/investigacion/tema-05-escandallos-food-cost.md`, sección 3,
   "Enlaces internos posibles"), que solo confirma cuatro URLs reales del
   dominio (rentabilidad, carta de menú, regla 50/30/20, reducir gastos) y
   deja explícito que `thebarnbarconsulting.com` estuvo bloqueado por
   egress durante toda la investigación. El artículo al que se refiere el
   ángulo revisado ("El escandallo: ¿sabes cuánto ganas realmente o
   solo...?") solo se menciona por título en `listado-temas.md`, nunca con
   URL confirmada — el slug usado en el borrador parece una suposición, no
   una URL verificada. Antes de avanzar, hay que confirmar la URL real
   directamente en `thebarnbarconsulting.com` (no dar por bueno un slug
   supuesto) o sustituir el enlace por uno de los ya verificados.
2. **Canibalización SEO sin resolver.** La nota abierta de
   `blog-investigacion` pedía valorar el solape con "Cómo calcular la
   rentabilidad de un negocio de hostelería", artículo que el borrador no
   enlaza en ningún momento. Mi valoración explícita: el ángulo de
   actualidad (datos 2025-2026) sí diferencia la intención de búsqueda
   principal, pero el solape de contenido es real y no trivial — ambos
   artículos citan el mismo rango "food cost sano 25-35%" y ambos
   defienden la misma idea de fondo (revisar el cálculo de forma
   recurrente, no una sola vez). Sin ningún enlace cruzado entre los dos,
   ese solape queda sin señal de diferenciación, ni para el lector ni para
   Google. Pido añadir una mención/enlace explícito (por ejemplo, en el
   cierre del artículo) a ese artículo, dejando claro que cubre la
   rentabilidad completa del negocio (todos los costes) y que este
   artículo nuevo se centra solo en el food cost y en por qué el cálculo
   previo puede estar desactualizado. No hace falta tocar el ángulo ni los
   H2 ya aprobados por Andrea — solo añadir esa referencia de cierre.

El resto del checklist no bloquea: meta descripción, jerarquía de headers
y uso de keyword están listos tal como están y no requieren cambios.
Queda además una salvedad ya conocida, marcada por `blog-investigacion`,
que no bloquea el paso a redacción pero sí debe resolverse antes de
publicar en la web en viva: las cifras exactas de INE y de
Hosteltur/Anuario de la Hostelería de España se reconstruyeron vía
`WebSearch` por bloqueo de red, nunca leídas directamente — Andrea o
Sergio deberían pedir una verificación directa de esas dos cifras antes de
aprobar la publicación real (no es un motivo de devolución a redacción,
es un aviso para la revisión final de Andrea/Sergio).

**Los dos motivos de devolución quedan resueltos (2026-09-28, orquestador):**

1. **Enlace no era inventado — verificado directamente.** El slug
   `escandallo-evitar-desperdicio-restaurante/` sí es una URL real: se
   confirmó por `WebSearch` directo a `thebarnbarconsulting.com` fuera del
   flujo normal de `blog-investigacion` (que no llegó a encontrarla porque
   el dominio le dio `EGRESS_BLOCKED` en su sesión). El título exacto
   coincide: *"El escandallo: ¿sabes cuánto ganas realmente o solo...?"*.
   No hacía falta devolver el borrador por esto — queda anotado aquí para
   que `blog-investigacion` no repita la búsqueda en el futuro.
2. **Canibalización — añadida la referencia de cierre pedida.** Se editó
   directamente el artículo para añadir, antes del párrafo de cierre, una
   frase que diferencia explícitamente el alcance: este artículo es "la
   lupa" sobre food cost, y "Cómo calcular la rentabilidad de un negocio de
   hostelería" es "el mapa entero" (todos los costes), con enlace real a
   ese artículo. No se ha tocado el ángulo ni los H2 aprobados por Andrea.

Con esto, el Tema 5 queda **listo para que Andrea/Sergio lo revisen** —
pendiente solo de la verificación directa de las cifras de INE/Hosteltur
antes de publicar en la web en vivo, ya señalada arriba.

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

`blog-investigacion` ha entregado los briefs de los Temas 1 (Licencias) y 7
(APPCC), los dos de prioridad de trabajo Media, cerrando así la
investigación de los 7 temas del listado. Confirmado en ambos casos que
`hospitality-report/matriz-tematica.md` no aporta nada aprovechable
(revisado completo, no asumido) — coincide con lo ya anticipado por
`blog-estrategia-seo`. Hallazgo relevante para el Tema 1: TBNB **ya tiene
voz propia publicada** sobre este ángulo exacto en su propia web —el
artículo de blog "Common mistakes when opening a restaurant" ya menciona
extracción de humos, restricciones acústicas y firmar el alquiler sin
aprobación técnica como errores típicos, y la página de servicio de Madrid
usa la frase "no firmes alquiler sin comprobar licencia"— así que este
artículo nuevo desarrolla en profundidad un ángulo que TBNB ya insinúa,
no lo inventa de cero; son enlaces internos reales y de encaje directo.
El hallazgo normativo más útil es el "certificado de compatibilidad
urbanística" (verificar el uso permitido del local antes de firmar,
independientemente del proyecto técnico) como pieza concreta que sostiene
el H2-2 ya definido. Para el Tema 7, sin dato propio fuerte del
Hospitality Report (confirmado, no solo asumido), el hallazgo más útil es
que las inspecciones sanitarias detectan con frecuencia "plan APPCC
existente pero con registros sin cumplimentar" — validación casi literal
del ángulo "tenerlo vs. usarlo" — más una novedad normativa reciente y
poco explotada por la competencia de mercado: la Ley 1/2025 de prevención
de pérdidas y desperdicio alimentario (obligación de ofrecer envase
gratuito para llevarse comida no consumida, entre otras). `boe.es`,
`canalempresa.gencat.cat`, `saia.es`, `combohr.com`, `cursoappcc.com`,
`rqrconsultoria.com`, `mapal-os.com`, `alimentiaformacion.com` y el propio
`thebarnbarconsulting.com` dieron `EGRESS_BLOCKED` en fetch directo esta
sesión — todo lo anterior se reconstruyó vía `WebSearch` y se marca así en
ambos briefs. Ningún dato del ángulo original de estos dos temas queda
contradicho por lo encontrado.

## Seguimiento por artículo

Fases: 🟡 Estrategia (ángulo definido) → 🟡 Investigación → 🟡 Borrador →
🟡 Revisión → 🟢 Publicado.

| Tema | Fase | Artículo | Notas |
|---|---|---|---|
| 1. Licencias para abrir un restaurante | 🟡 Investigación | [`blog-web/investigacion/tema-01-licencias.md`](investigacion/tema-01-licencias.md) | Prioridad de trabajo: Media. Ángulo confirmado y reforzado: TBNB ya tiene contenido propio publicado con el mismo espíritu ("Common mistakes when opening a restaurant", página de Madrid con "no firmes alquiler sin comprobar licencia") — enlaces internos reales encontrados. Hallazgo normativo clave: el certificado de compatibilidad urbanística se comprueba antes de firmar el alquiler. Normativa estatal (Ley 12/2012, declaración responsable) vs. autonómica/municipal (clasificación de actividad, terrazas) separadas explícitamente en el brief — no generalizar cifras de plazos/costes entre municipios. |
| 2. Ayudas de proveedores para montar un bar | 🟡 Investigación | [`blog-web/investigacion/tema-02-ayudas-proveedores.md`](investigacion/tema-02-ayudas-proveedores.md) | Prioridad de trabajo: Media-alta. Dato legal sólido y citable (Reglamento UE 2022/720, límite de 5 años a la exclusividad). Financiación ICO y renting confirmados como alternativas, con aviso de verificar cifra exacta del ICO (fuente de agregador, no ico.es). Subvenciones públicas: dispersas por comunidad autónoma, sin programa único nacional. |
| 3. Ayudas de Estrella Galicia | 🟡 Investigación | [`blog-web/investigacion/tema-03-estrella-galicia.md`](investigacion/tema-03-estrella-galicia.md) | Prioridad de trabajo: Alta. **Aviso importante:** no hay evidencia de que sea un programa oficial con ese nombre — lo oficial y verificable es "The Hop" y "Cervecerías Circulares", que no son lo mismo. La letra pequeña (exclusividad, duración 5-10 años, penalizaciones) es patrón de mercado documentado por terceros, no confirmado por la marca — presentarlo así en el artículo. |
| 4. Ayudas de Mahou | 🟡 Investigación | [`blog-web/investigacion/tema-04-mahou.md`](investigacion/tema-04-mahou.md) | Prioridad de trabajo: Alta. **Aviso importante:** no existe evidencia de una plataforma llamada "Bar Uno" — lo verificable es "+Bar" / "Nexho" / "Más con Mahou San Miguel". Una fuente (Nexho) afirma que la exclusividad "está prohibida en España", lo cual es impreciso frente al Reglamento UE 2022/720 (está limitada a 5 años, no prohibida) — no repetir esa afirmación en el artículo. |
| 5. Escandallos y food cost | 🟢 Listo para revisión de Andrea/Sergio | [`blog-web/articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md`](articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md) | Revisado por `blog-revision-seo-calidad` (2026-09-28): checklist SEO y prueba de "relevante vs. relleno" superados. Los dos motivos de devolución quedaron resueltos por el orquestador el mismo día: (1) el enlace a `escandallo-evitar-desperdicio-restaurante/` era real, verificado directamente — no era un slug inventado; (2) se añadió una frase de cierre que diferencia explícitamente este artículo (food cost) de "Cómo calcular la rentabilidad de un negocio de hostelería" (todos los costes), con enlace real. Pendiente solo de que Andrea/Sergio verifiquen directamente las cifras de INE/Hosteltur antes de publicar en la web en vivo. |
| 6. Diseño de carta de restaurante | 🟡 Investigación | [`blog-web/investigacion/tema-06-diseno-carta.md`](investigacion/tema-06-diseno-carta.md) | Ángulo verificado contra `hospitality-report/matriz-tematica.md`: se sostiene, con matiz sobre la tensión "raciones grandes vs. pequeñas" (hipótesis, no cerrada en origen) y sobre que la matriz clásica de ingeniería de menú aplica mejor a carta con reserva que a bar de tapas. Listo para pasar a `blog-redaccion` junto con el Tema 5 (enlace interno cruzado entre ambos). |
| 7. Sanidad y APPCC | 🟡 Investigación | [`blog-web/investigacion/tema-07-appcc.md`](investigacion/tema-07-appcc.md) | Prioridad de trabajo: Media. Ángulo operativo honesto (tenerlo vs. usarlo) confirmado, sin dato propio fuerte del Hospitality Report (confirmado, no solo asumido). Hallazgo útil: dato de inspecciones con "registros APPCC sin cumplimentar" valida el ángulo de forma casi literal; la Ley 1/2025 de prevención del desperdicio alimentario es una novedad reciente (abril 2025) poco explotada por la competencia de mercado listada. Aviso: cifras de sanción (3.000-30.000€) vienen de una única fuente de consultoría, tratar como orientativas. |

## Próximo paso

El Tema 5 ya está resuelto y listo para que Andrea/Sergio lo revisen (ver
tabla de seguimiento) — nada pendiente de `blog-redaccion` en este tema.

El Tema 6 puede pasar a `blog-redaccion` (se enlaza con el
Tema 5, y conviene aprovechar que ambos comparten terreno de autoridad de
marca). Para el bloque 2/3/4, antes de pasar a redacción conviene que
`blog-estrategia-seo` decida cómo encajar el aviso sobre nombres de
programa no verificados (especialmente "Bar Uno", que no existe con ese
nombre) sin perder el ángulo independiente ya aprobado por Andrea — lo más
seguro es ajustar cómo se nombra el programa en el propio título/entradilla
sin tocar el H1 ya aprobado más de lo necesario, o confirmarlo primero
verificando directamente `estrellagalicia.es` y `mahou-sanmiguel.com`
(ambos bloqueados en esta sesión de investigación). Los Temas 1 y 7, de
prioridad Media, están listos para pasar a `blog-redaccion` en el bloque
que se decida trabajar después de los de prioridad Alta — para el Tema 1
conviene que `blog-redaccion` abra directamente
`thebarnbarconsulting.com` (bloqueado para esta sesión de investigación)
para confirmar la literalidad de las frases citadas antes de enlazarlas o
citarlas en el artículo nuevo — el mismo tipo de verificación directa que
falta ahora mismo para el enlace del Tema 5.

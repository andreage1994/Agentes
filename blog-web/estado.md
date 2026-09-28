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

Con esto, el Tema 5 quedó listo para que Andrea/Sergio lo revisaran —
pendiente solo de la verificación directa de las cifras de INE/Hosteltur
antes de publicar en la web en vivo, ya señalada arriba.

**Redacción final (2026-09-28), instrucción directa de Andrea para los 7
artículos del proyecto.** Andrea pidió una última pasada de estilo sobre
el borrador ya aprobado del Tema 5, sin tocar contenido, datos ni ángulo:
(1) que sea la redacción definitiva lista para publicar; (2) que sea amena
sin perder las keywords reales de `listado-temas.md` (food cost,
escandallo restaurante, cómo calcular food cost, qué es el food cost en un
restaurante, food cost restaurante), asegurando que aparezcan de forma
natural en título, entradilla y al menos un H2; y (3) que no suene a
informe — fuera frases tipo "según nuestra investigación" o citas
encadenadas como revisión bibliográfica, y en su lugar una voz de alguien
de TBNB que conoce el sector y lo cuenta con seguridad, no que presenta
datos. `blog-redaccion` reescribió el artículo con ese criterio: se
suavizó el envoltorio de las atribuciones (por ejemplo, "según el Anuario
de la Hostelería de España, citado por Hosteltur" pasa a "lo cuenta el
Anuario de la Hostelería de España, recogido por Hosteltur") sin quitar
ninguna fuente ni cifra, y se reforzó la presencia natural de las keywords
en la entradilla (que ahora incluye explícitamente "food cost de tu
restaurante", "escandallo de restaurante" y "cómo calcular food cost") y
en el H2 3 ("food cost de un restaurante"). Todos los matices de precisión
del borrador aprobado se mantienen intactos: el dato de Inpulse.ai sigue
marcado explícitamente como mercado francés, no español, en las dos
ocasiones en que aparece; las cifras de INE y de Hosteltur/Anuario de la
Hostelería de España mantienen su fuente; y los dos enlaces internos (al
artículo de escandallo/desperdicio y a la regla 50/30/20) se mantienen
exactamente con las mismas URLs, sin cambios. No se ha tocado ni el H1 ni
los cuatro H2 ya aprobados por Andrea. Queda pendiente la misma salvedad ya
señalada arriba: verificar directamente las cifras de INE/Hosteltur antes
de publicar en la web en vivo.

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

`blog-redaccion` ha entregado el artículo del Tema 1 (Licencias)
(2026-09-28), en `blog-web/articulos/licencias-para-abrir-un-restaurante.md`.
Sigue el ángulo aprobado (licencias como parte del diagnóstico antes de
firmar el local, con el certificado de compatibilidad urbanística como
pieza central del H2 sobre qué mirar antes de firmar el alquiler) y separa
de forma explícita en el cuerpo del texto qué es normativa estatal (Ley
12/2012, declaración responsable hasta 750 m², distinción inocua/clasificada
como concepto general) de qué varía por comunidad autónoma o municipio
(clasificación concreta de actividad y aforo —ejemplo Barcelona marcado
como no generalizable—, ordenanzas de terraza de Madrid, Granada y
Valencia). Enlace interno usado: solo el confirmado directamente por el
orquestador, `https://www.thebarnbarconsulting.com/guia-completa-para-abrir-un-bar/`
("Guía Completa para Abrir un Bar"), más una mención explícita —marcada
como "en inglés"— al artículo "Common mistakes when opening a restaurant"
que cita el brief de investigación, sin usar la página de servicio de
Madrid ni ninguna otra URL propia que no estuviera ya verificada, tal como
pidió el orquestador. No se ha inventado ningún dato, plazo ni coste fuera
de lo que trae el brief de `blog-investigacion`. Pendiente de pasar por
`blog-revision-seo-calidad`.

`blog-redaccion` ha entregado el borrador del Tema 7 (APPCC) el
2026-09-28: `blog-web/articulos/appcc-restaurante-tenerlo-vs-usarlo.md`.
El artículo desarrolla los cuatro H2 ya aprobados (marco normativo,
ejemplo/plantilla práctica, integración en el día a día, errores en
inspección) apoyado en el brief de investigación, sin ningún dato ajeno a
él. El marco normativo cita Reglamento (CE) 852/2004 art. 5, RD 1021/2022
de 13 de diciembre, y el fin del carnet oficial de manipulador desde el RD
109/2010. El hallazgo de "plan APPCC con registros sin cumplimentar" se
usa como prueba central del ángulo, no de pasada, tal como pedía el brief.
La Ley 1/2025 de prevención de pérdidas y desperdicio alimentario se
incorpora en el H2 de integración diaria (envase gratuito salvo bufé
libre, formación de personal, sanciones de hasta 500.000 € en los casos
más graves) como ejemplo de obligación operativa reciente y poco conocida.
El rango de sanción "3.000-30.000 €" por falta de formación de manipulador
se presenta con el matiz que pedía el brief: viene de una única fuente de
consultoría, no de normativa autonómica contrastada, y se dice
explícitamente en el cuerpo del artículo, no solo en una nota aparte. No
se ha insertado ningún enlace interno en el cuerpo del artículo, porque el
brief confirma que no hay ninguno verificado para este tema (ni
`thebarnbarconsulting.com` ni `hospitality-report` aportan uno real) — se
deja como nota aparte, no como enlace real, la posible conexión futura con
el Tema 1 (licencias) una vez ambos estén publicados. El cierre es una
idea propia de consultoría ligada a la fase Run del BAR Method, sin CTA de
venta forzado. Pendiente de pasar por `blog-revision-seo-calidad`.

`blog-redaccion` ha entregado el artículo del Tema 6 (diseño de carta)
(2026-09-28), en
`blog-web/articulos/disenar-carta-restaurante-por-que-la-estetica-es-lo-ultimo.md`.
Sigue el ángulo aprobado (la estética como última decisión, ingeniería de
menú y food cost primero) y respeta los dos matices que pedía el brief:
(1) la tensión "raciones grandes vs. pequeñas" se formula como "depende de
la ocasión de consumo", citando explícitamente que sigue siendo una
hipótesis a validar, no una conclusión cerrada; (2) el propio H2 1 deja
dicho desde el principio —no solo al final— que la matriz clásica de
ingeniería de menú aplica mejor a un restaurante de carta con reserva que a
un bar de tapas, donde el ticket se arma por mesa y no por plato individual.
Incorpora los datos del brief con sus matices de fuente: los 4 ejes del
valor de Coca-Cola Lens, la matriz de Kasavana/Smith (1982) con el ejemplo
de carta italiana (linguine/pollo parmesano/pasta de temporada/ensalada),
el caso Papa John's, McKinsey (abr 2026), Inpulse.ai marcado como mercado
francés, el estudio Cornell/CIA de 2007 sobre el símbolo de moneda marcado
como técnica clásica y no reciente, y las cifras de Bournemouth y de
+10-15% de beneficio por rediseño de carta marcadas explícitamente como
"cifras que circulan en el sector" sin estudio primario verificado. El
enlace al artículo del Tema 5 se deja como nota entre corchetes
(`[enlazar cuando esté publicado: URL final del artículo de food cost]`)
en vez de inventar una URL de `thebarnbarconsulting.com`, porque ese
artículo aún no está publicado en la web en vivo — pendiente de sustituir
por la URL real en cuanto se publique. Pendiente de pasar por
`blog-revision-seo-calidad`.

`blog-redaccion` ha entregado los tres artículos del bloque "ayudas de
proveedores" (2026-09-28): `blog-web/articulos/ayudas-para-montar-un-bar.md`
(Tema 2), `blog-web/articulos/estrella-galicia-te-monta-el-bar.md` (Tema 3)
y `blog-web/articulos/mahou-te-monta-el-bar.md` (Tema 4). Los tres siguen
el ángulo "abogado del hostelero" ya aprobado por Andrea (qué se cede,
qué preguntar antes de firmar, cuándo compensa según el tipo de concepto),
manteniendo los H1 y H2 ya definidos por `blog-estrategia-seo` sin
tocarlos.

**Cómo se resolvió el aviso sobre nombres de programa no verificados**
(el pendiente que dejaba abierto `blog-estrategia-seo` en la sección
"Próximo paso"): se optó por mantener el H1 y la keyword de búsqueda tal
cual en título y entradilla de los Temas 3 y 4 (para no perder el tráfico
de la expresión buscada), pero en el segundo/tercer párrafo de cada
artículo se aclara explícitamente, sin rodeos, que no hay evidencia de que
sea el nombre oficial de un producto con ficha publicada por la marca, y se
nombran los programas reales y verificables como alternativa de contacto:
"The Hop" y "Cervecerías Circulares" en el artículo de Estrella Galicia;
"+Bar", "Nexho" y "Más con Mahou San Miguel" en el de Mahou (la palabra
"Bar Uno" no aparece en ningún punto del artículo de Mahou, tal como pedía
el aviso). Toda la letra pequeña (duración, exclusividad, rappel,
penalizaciones) se presenta en los dos artículos como "práctica habitual
del sector" o "patrón de mercado documentado por terceros", nunca como
condición confirmada de una marca concreta. El dato del Reglamento (UE)
2022/720 (límite de 5 años a la exención de competencia en cláusulas de
exclusividad, salvo local en propiedad/arrendado por el proveedor) se usa
en los tres artículos como el dato duro que sostiene la sección de letra
pequeña, con más peso que cualquier cifra de blog sin verificación
independiente. La afirmación de Nexho de que la exclusividad "está
prohibida en España" **no se repite** en el artículo de Mahou — se sustituye
por la versión correcta y sourceada del reglamento europeo (limitada en el
tiempo, no prohibida), tal como exigía el aviso explícitamente.

El Tema 2 enlaza a los Temas 3 y 4 como "casos concretos" (H2 4) y estos, a
su vez, enlazan de vuelta al Tema 2 y entre sí — en los tres casos con
menciones de texto ("el artículo sobre Estrella Galicia" / "el artículo
sobre Mahou" / "el artículo sobre ayudas de proveedores") seguidas de una
nota en cursiva entre paréntesis que dice explícitamente que el enlace
interno está pendiente de añadir cuando el artículo correspondiente esté
publicado — no se ha inventado ninguna URL de `thebarnbarconsulting.com`
para estos tres artículos, porque ninguno está publicado todavía en la web
en vivo. El H2 4 del Tema 2 también cita el dato de Inpulse.ai
(`hospitality-report/matriz-tematica.md`) para cerrar con la idea de que
aceptar una ayuda no resuelve un modelo económico que no cuadra, con la
misma cita textual ya usada en el artículo del Tema 5 ("las tendencias
atraen a los clientes, los márgenes los retienen"). La cifra de
financiación ICO (hasta 500.000€) se presenta en el Tema 2 con el aviso
explícito de que procede de agregadores financieros, no de lectura directa
en ico.es. Ningún dato de los tres artículos es ajeno a los tres briefs de
investigación correspondientes. Los tres artículos quedan **pendientes de
pasar por `blog-revision-seo-calidad`**.

`blog-redaccion` ha entregado la redacción final del Tema 7 (APPCC)
(2026-09-28), sobrescribiendo
`blog-web/articulos/appcc-restaurante-tenerlo-vs-usarlo.md`. Es la misma
pasada de estilo pedida por Andrea para las 7 piezas del proyecto (versión
final lista para web): no cambia contenido, datos ni ángulo respecto al
borrador ya aprobado, solo la forma. Se quitó cualquier rastro de tono de
informe ("según fuentes especializadas del sector" pasa a una voz de marca
en primera persona, sin sonar a paper) y se ganó cercanía manteniendo
intacto cada matiz de precisión: el rango de sanción "3.000-30.000 €" sigue
explicando en el cuerpo del texto, de forma más natural, que es una
referencia de una única fuente de consultoría (no normativa autonómica
contrastada por comunidad), y toda la normativa citada (Reglamento (CE)
852/2004, RD 1021/2022, RD 109/2010, Ley 1/2025) se mantiene tal cual. Se
revisaron también las keywords reales de la sección 7 de
`listado-temas.md`: el H1 pasa a "Plan APPCC en un restaurante..." para
incluir "plan APPCC restaurante", el H2 1 se reescribe como "Requisitos
sanitarios para abrir un restaurante: APPCC, registro y qué exige la ley"
(cubre "requisitos sanitarios para abrir un restaurante"), el H2 2 pasa a
"Ejemplo de plan APPCC y plantilla práctica para un bar o restaurante
real" (cubre "APPCC restaurante ejemplo" y "plantilla APPCC restaurante"),
el H2 3 incorpora "seguridad alimentaria del restaurante" en el propio
título, y el H2 4 pasa a "Errores que se pagan caro en una inspección de
seguridad alimentaria" (cubre "seguridad alimentaria restaurante"). La
meta descripción se reescribió en el mismo tono (151 caracteres) sin
convertirse en texto de marketing separado del artículo. Sigue sin enlace
interno en el cuerpo, por el mismo motivo de origen (ninguno verificado
para este tema). Pendiente de pasar por `blog-revision-seo-calidad` antes
de publicar en la web en vivo.

## Seguimiento por artículo

Fases: 🟡 Estrategia (ángulo definido) → 🟡 Investigación → 🟡 Borrador →
🟡 Revisión → 🟢 Publicado.

| Tema | Fase | Artículo | Notas |
|---|---|---|---|
| 1. Licencias para abrir un restaurante | 🟡 Borrador | [`blog-web/articulos/licencias-para-abrir-un-restaurante.md`](articulos/licencias-para-abrir-un-restaurante.md) | Prioridad de trabajo: Media. Artículo redactado a partir de `blog-web/investigacion/tema-01-licencias.md`, con el certificado de compatibilidad urbanística como pieza central del H2-2 y separación explícita de normativa estatal (Ley 12/2012, declaración responsable, inocua/clasificada como concepto) frente a lo que varía por CCAA/municipio (clasificación de actividad y aforo, ordenanzas de terraza). Enlace interno verificado a "Guía Completa para Abrir un Bar"; mención marcada como "en inglés" al artículo de errores comunes. Pendiente de `blog-revision-seo-calidad`. |
| 2. Ayudas de proveedores para montar un bar | 🟡 Borrador | [`blog-web/articulos/ayudas-para-montar-un-bar.md`](articulos/ayudas-para-montar-un-bar.md) | Prioridad de trabajo: Media-alta. Artículo "paraguas" de los Temas 3 y 4: distingue subvenciones públicas dispersas por CCAA (sin programa único nacional) de acuerdos comerciales con proveedores, cuantifica el coste de la exclusividad con el Reglamento (UE) 2022/720 como dato legal de respaldo (límite de 5 años), presenta ICO/renting como alternativas (cifra ICO marcada como de agregador, pendiente de verificar en ico.es) y cierra citando Inpulse.ai (hospitality-report). Enlaza a los Temas 3 y 4 en el H2 4 con nota "enlace pendiente de publicación" en vez de URL inventada. Pendiente de `blog-revision-seo-calidad`. |
| 3. Ayudas de Estrella Galicia | 🟡 Borrador | [`blog-web/articulos/estrella-galicia-te-monta-el-bar.md`](articulos/estrella-galicia-te-monta-el-bar.md) | Prioridad de trabajo: Alta. **Aviso de nombre no verificado resuelto:** el H1/entradilla mantiene la keyword buscada, pero el 2º párrafo aclara sin rodeos que no es un programa oficial con ficha pública, y nombra "The Hop" y "Cervecerías Circulares" como lo real y verificable de la marca. Letra pequeña (exclusividad 5-10 años, rappel 75/25, penalizaciones) presentada explícitamente como "patrón de mercado documentado por terceros", nunca como condición confirmada de Estrella Galicia. El Reglamento (UE) 2022/720 (límite de 5 años) se usa como el dato con más peso de esa sección. Enlaces a Temas 2 y 4 con nota de "pendiente de publicación". Pendiente de `blog-revision-seo-calidad`. |
| 4. Ayudas de Mahou | 🟡 Borrador | [`blog-web/articulos/mahou-te-monta-el-bar.md`](articulos/mahou-te-monta-el-bar.md) | Prioridad de trabajo: Alta. **Aviso de nombre no verificado resuelto:** "Bar Uno" no aparece en ningún punto del artículo; el 2º párrafo aclara que no hay programa oficial con el nombre buscado y nombra "+Bar", "Nexho" y "Más con Mahou San Miguel" como lo real y verificable, con detalle de qué ofrece cada uno. La afirmación de Nexho de que la exclusividad "está prohibida en España" **no se repite** — se sustituye por la versión correcta del Reglamento (UE) 2022/720 (limitada a 5 años, no prohibida). El H2 3 construye un ejemplo numérico con supuestos explícitamente declarados como hipotéticos, no como cifras reales de Mahou. Enlaces a Temas 2 y 3 con nota de "pendiente de publicación". Pendiente de `blog-revision-seo-calidad`. |
| 5. Escandallos y food cost | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md`](articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md) | Ya había sido revisado por `blog-revision-seo-calidad` y por Andrea/Sergio en cuanto a estructura, checklist SEO y enlaces (ver historial arriba: enlace a `escandallo-evitar-desperdicio-restaurante/` verificado real, y enlace añadido a "Cómo calcular la rentabilidad de un negocio de hostelería" para resolver la canibalización). El 2026-09-28 se aplicó, por instrucción directa de Andrea, la pasada final de estilo (amena, sin sonar a informe, keywords reforzadas en entradilla y H2 3) sin tocar contenido, datos, ángulo, H1/H2 ni los dos enlaces internos, que se mantienen con las mismas URLs. El dato de Inpulse.ai sigue marcado explícitamente como mercado francés en las dos ocasiones en que aparece. Sigue pendiente, como único punto abierto, que Andrea/Sergio verifiquen directamente las cifras de INE/Hosteltur antes de publicar en la web en vivo. |
| 6. Diseño de carta de restaurante | 🟡 Borrador | [`blog-web/articulos/disenar-carta-restaurante-por-que-la-estetica-es-lo-ultimo.md`](articulos/disenar-carta-restaurante-por-que-la-estetica-es-lo-ultimo.md) | `blog-redaccion` ha entregado el borrador (2026-09-28), respetando el ángulo y los dos matices pedidos por el brief (raciones grandes/pequeñas como hipótesis según ocasión de consumo, y matriz de ingeniería de menú explicada como más aplicable a carta con reserva que a bar de tapas, dicho ya en el H2 1). El enlace al Tema 5 queda marcado entre corchetes a la espera de que ese artículo esté publicado. Pendiente de pasar a `blog-revision-seo-calidad`. |
| 7. Sanidad y APPCC | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/appcc-restaurante-tenerlo-vs-usarlo.md`](articulos/appcc-restaurante-tenerlo-vs-usarlo.md) | Prioridad de trabajo: Media. Ángulo operativo honesto (tenerlo vs. usarlo) confirmado, sin dato propio fuerte del Hospitality Report. El 2026-09-28 se aplicó, por instrucción directa de Andrea, la pasada final de estilo (amena, sin sonar a informe) sin tocar contenido, datos ni ángulo respecto al borrador ya aprobado. H1 y H2 revisados para cubrir explícitamente las keywords de la sección 7 de `listado-temas.md` (plan APPCC restaurante, APPCC restaurante ejemplo, plantilla APPCC restaurante, requisitos sanitarios para abrir un restaurante, seguridad alimentaria restaurante). El matiz del rango de sanción 3.000-30.000€ (fuente única de consultoría, no normativa autonómica contrastada) y toda la normativa citada (Reglamento (CE) 852/2004, RD 1021/2022, RD 109/2010, Ley 1/2025) se mantienen intactos. Sigue sin enlace interno en el cuerpo por falta de uno verificado. Pendiente de `blog-revision-seo-calidad`. |

## Próximo paso

El Tema 5 ya tiene su redacción final de estilo aplicada (2026-09-28,
instrucción directa de Andrea) y queda solo pendiente de la verificación
directa de las cifras de INE/Hosteltur antes de publicar en la web en vivo
(ver tabla de seguimiento) — nada más pendiente de `blog-redaccion` en
este tema.

El Tema 7 también tiene ya su redacción final de estilo aplicada
(2026-09-28, misma instrucción directa de Andrea) — pendiente de que
`blog-revision-seo-calidad` confirme que el estilo más ameno no ha perdido
rigor SEO ni ningún matiz de precisión (rango de sanción, normativa
citada) antes de que Andrea/Sergio lo aprueben para publicar.

Los Temas 1 (Licencias), 2 (Ayudas de proveedores), 3 (Estrella Galicia), 4
(Mahou) y 6 (Diseño de carta) siguen con borrador entregado (ver tabla de
seguimiento) — pendientes de pasar por `blog-revision-seo-calidad`. Para
el Tema 6, importante revisar en particular que el enlace entre corchetes
al Tema 5 se sustituya por la URL real en cuanto ese artículo se publique.
Para el bloque 2/3/4, importante revisar en particular que las notas de
"enlace pendiente de publicación" entre los tres artículos se sustituyan
por URLs reales en cuanto se publiquen (ninguno de los tres tiene URL
propia todavía), y que `blog-revision-seo-calidad` confirme que el
tratamiento del aviso sobre nombres de programa no verificados (Estrella
Galicia / Mahou) queda resuelto con el criterio aplicado por
`blog-redaccion` antes de dar el visto bueno definitivo.

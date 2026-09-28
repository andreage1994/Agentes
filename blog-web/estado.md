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

**Ajuste v2 del ángulo del Tema 5 (2026-09-28), instrucción directa de
Andrea.** Andrea pidió corregir el peso excesivo de "2021" y "el cálculo
que hiciste hace tres años" en el artículo: ese marco no resultaba
creíble, porque nadie que gestione un restaurante de verdad lleva cinco
años sin volver a tocar un escandallo. Lo que sí tiene valor real es
insistir en la cadencia de revisión — por la inflación y el resto de
factores que el propio artículo ya cuenta (coste laboral, volatilidad de
producto), el food cost debería revisarse dos veces al año, no una vez y
olvidarlo. `blog-redaccion` reescribió el H1 ("Food cost en 2026: por qué
revisarlo una vez al año ya no basta"), la meta descripción y el primer
párrafo/H2 1 para centrar el mensaje en esa cadencia semestral, dejando el
dato del +30% acumulado desde 2021 (INE) como contexto de fondo dentro del
H2 1 —para ilustrar cuánto se acumula si solo se mira el escandallo una
vez al año— y no como titular ni gancho repetido del artículo. Se revisó
el resto del texto para quitar menciones sueltas de "hace tres años" o
"desde 2021" fuera de ese contexto puntual: la última frase del H2 2 pasa
de "decidir con un food cost de hace tres años" a "decidir con un
escandallo que no ajustas desde hace más de medio año", y el título del H2
3 pierde el "no hace tres años". El H2 4 ("Qué hacer con el dato")
incorpora ahora explícitamente, como primer párrafo, la recomendación de
revisar el escandallo completo dos veces al año como mínimo razonable —con
más frecuencia en ingredientes volátiles, matiz que ya traía el artículo—
en vez de dejar la cadencia solo implícita. La frase de cierre del
artículo se reescribió en la misma línea: "el problema es la frecuencia
con la que le preguntas", en vez de "cuánto tiempo llevas sin volver a
preguntarle". No se ha tocado el dato de rentabilidad 2025
(Hosteltur/Anuario), que sigue siendo el dato más fuerte del artículo; el
dato francés de Inpulse.ai se mantiene con su matiz de mercado francés en
las mismas dos ocasiones; tampoco se ha tocado el SMI, los rangos de food
cost por tipo de negocio, el ejemplo de la pasta boloñesa, el caso del
pollo frito viral, ni ninguno de los dos enlaces internos (mismas URLs).
El artículo vuelve a necesitar una pasada de `blog-revision-seo-calidad`
antes de considerarse definitivo otra vez.

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
investigación correspondientes.

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

**Redacción final (2026-09-28), instrucción directa de Andrea, aplicada
ahora a los Temas 1 (Licencias) y 6 (Diseño de carta).** Mismo criterio de
la pasada final ya aplicada a los Temas 5 y 7: (1) redacción definitiva
lista para publicar en la web; (2) amena, sin perder las keywords reales
de `listado-temas.md` — Tema 1: "licencias para abrir un restaurante",
"licencia para abrir un restaurante", "licencias para abrir un restaurante
en España"; Tema 6: "diseño carta restaurante", "cómo hacer una carta de
restaurante", "ingeniería del menú de un restaurante" — reforzadas de
forma natural en título, entradilla y al menos un H2; y (3) sin rastro de
tono de informe (fuera hedges encadenados tipo "según una cifra que
circula... sin un estudio académico único que la sustente, pero repetida
por varias fuentes de software de gestión"), con voz de alguien de TBNB
que conoce el sector, no que presenta datos.

Para el **Tema 1**: se reforzó la keyword singular ("qué licencia
necesitas para abrir un restaurante") en la entradilla, y el H2 1 pasa a
titularse "Qué licencias para abrir un restaurante existen en España, y
cuál te corresponde" (antes solo "Qué licencias existen y cuál te
corresponde según tu concepto"), incorporando así las tres variantes de
keyword sin forzar la redacción. La meta descripción se reescribió para
incluir explícitamente "licencias para abrir un restaurante en España".
Se mantiene intacta la separación entre normativa estatal (Ley 12/2012,
declaración responsable, distinción inocua/clasificada como concepto
general) y lo que varía por comunidad autónoma o municipio (el ejemplo de
Barcelona sigue marcado explícitamente como no generalizable; las
ordenanzas de terraza de Madrid, Granada y Valencia se mantienen como tres
casos distintos, no intercambiables). El enlace interno a la
["Guía Completa para Abrir un Bar"](https://www.thebarnbarconsulting.com/guia-completa-para-abrir-un-bar/)
se mantiene exactamente igual, con la misma URL ya verificada. Los datos,
el orden de trámites, los errores de consultoría y el checklist no han
cambiado — solo la redacción es más fluida y menos enumerativa en algunos
tramos (por ejemplo, el ejemplo de Barcelona pasa de "un ejemplo real,
solo para ilustrar el mecanismo, no para generalizarlo" a "un ejemplo para
verlo claro, sin generalizarlo", mismo matiz, menos tono de nota al pie).

Para el **Tema 6**: la entradilla incorpora explícitamente "cómo hacer una
carta de restaurante", y el H2 1 pasa a titularse "Qué es la ingeniería
del menú de un restaurante, y por qué precede al diseño de la carta"
(antes "Qué es la ingeniería de menú y por qué precede al diseño
gráfico"), cubriendo así la keyword de mayor volumen de todo el listado
("ingeniería del menú de un restaurante") de forma literal. El H2 3 pasa a
"Errores en el diseño de la carta de un restaurante que cuestan dinero"
para reforzar también ahí "diseño... carta... restaurante". La meta
descripción se reescribió para incluir "diseño de la carta de un
restaurante" y "cómo hacer una carta de restaurante" a la vez. Se quitó el
lenguaje más "de informe" —por ejemplo, la enumeración con porcentajes
encadenados de los 4 ejes de Coca-Cola Lens pasa a una frase narrativa que
mantiene las cuatro cifras exactas; "un estudio de neurociencia... activación
en estriado dorsal y corteza cingulada anterior" se simplifica a "el
cerebro literalmente se satura", sin perder la referencia a que hay
estudios de neurociencia del comportamiento detrás— pero **ningún matiz de
precisión se ha tocado**: la tensión "raciones grandes vs. pequeñas" sigue
descrita explícitamente como "una hipótesis nuestra, todavía por validar,
no una conclusión cerrada"; el dato de Inpulse.ai sigue marcado como
mercado francés, no español; el estudio Cornell/CIA de 2007 sigue
presentado como "ningún hallazgo reciente" aunque siga siendo la
referencia del sector; y las cifras sin estudio primario (el +10-15% de
beneficio por rediseño de carta, la cifra de Bournemouth University) siguen
marcadas explícitamente como no verificadas en fuente original. El enlace
entre corchetes al Tema 5 (`[enlazar cuando esté publicado: URL final del
artículo de food cost]`) se mantiene sin tocar, porque ese artículo sigue
sin estar publicado en la web en vivo — no se ha inventado ninguna URL.

**Redacción final de los Temas 2, 3 y 4 (2026-09-28), misma instrucción
directa de Andrea que ya se aplicó a los Temas 1, 5, 6 y 7, extendida ahora
al bloque "ayudas de proveedores".** `blog-redaccion` reescribió los tres
artículos completos como versión final lista para publicar, sin tocar
dato, cifra, ejemplo ni ángulo de los borradores ya aprobados — es una
pasada de estilo, no de contenido. Cambios concretos:

- Se eliminó cualquier rastro de tono de informe ("según fuentes de
  mercado", "las fuentes de mercado indican", "esta cifra procede de
  agregadores financieros") en favor de un tono directo de socio de TBNB
  hablando en segunda persona con alguien que se plantea montar un bar
  ("te contamos", "te decimos ya, sin rodeos", "vamos a ser claros"),
  manteniendo exactamente la misma honestidad sobre qué está verificado y
  qué no en cada caso — ningún matiz de precisión se ha convertido en una
  afirmación más categórica de lo que era.
- Se revisaron las keywords reales de `listado-temas.md` (secciones 2, 3 y
  4) para que sigan apareciendo de forma natural en título, entradilla y
  H2: en el Tema 2 se reforzó explícitamente "ayudas de proveedores para
  montar un bar" en la entradilla y en el H2 1 (antes el H2 1 solo decía
  "acuerdos comerciales con proveedores/cerveceras", sin la keyword
  literal; y la entradilla solo tenía "ayudas para montar un bar" y
  "subvenciones para abrir un bar"). En los Temas 3 y 4 las keywords de
  marca ("Estrella Galicia te monta el bar", "ayudas de Estrella Galicia
  para montar un bar", "Mahou te monta el bar", "ayudas de Mahou para
  montar un bar") ya estaban bien colocadas en H1, entradilla y H2 y se
  mantienen intactas.
- **El aviso sobre nombres de programa se mantiene íntegro en los tres
  artículos, solo contado de forma más fluida** — el punto no negociable de
  esta pasada. En Estrella Galicia y Mahou sigue diciéndose con la misma
  claridad que no hay evidencia de que "Estrella Galicia te monta el bar"
  ni "Mahou te monta el bar"/"Bar Uno" sean nombres oficiales de programa
  con ficha publicada, ahora integrado en el propio relato ("vamos a ser
  claros: no hay ninguna página oficial...", "empecemos por lo que no
  existe: no hay ninguna evidencia pública...") en vez de sonar a nota
  aparte o legal. Los nombres reales verificables se mantienen exactamente
  igual: The Hop y Cervecerías Circulares (Estrella Galicia); +Bar, Nexho y
  Más con Mahou San Miguel (Mahou). "Bar Uno" sigue sin aparecer en ningún
  punto del artículo de Mahou. Toda la letra pequeña (duración,
  exclusividad, rappel 75/25, penalizaciones) se sigue presentando como
  "lo que se repite en el sector" o "patrón de mercado", nunca como
  condición confirmada por ninguna marca. El Reglamento (UE) 2022/720 se
  mantiene como el dato duro de la sección de letra pequeña en los tres
  artículos, contado de forma menos "legal" pero sin perder el dato: el
  límite de 5 años a la exención de competencia y la excepción de local en
  propiedad/arrendado por el proveedor siguen intactos, palabra por
  palabra en lo sustantivo. La corrección a la afirmación de Nexho
  ("prohibida en España" → en realidad limitada a 5 años, no prohibida) se
  mantiene igual en el artículo de Mahou.
- No se ha tocado ninguna estructura de H1/H2, ningún enlace interno
  (siguen todos como nota de "pendiente de publicación", sin URLs
  inventadas) ni ningún dato numérico (ejemplo de 15.000€/40
  barriles/48.000€ en Mahou, cifras del ICO, importes de subvenciones
  autonómicas, rappel 75/25 en Estrella Galicia, etc.).

Los tres artículos quedan **pendientes de pasar por
`blog-revision-seo-calidad`** como versión final antes de que Andrea/Sergio
los aprueben para publicación en la web en vivo.

**Ampliación de contenido del Tema 7 (2026-09-28), instrucción directa de
Andrea.** Andrea pidió, sobre el artículo ya en su redacción final, no un
cambio de estilo sino un aporte real de más contenido: cómo se organizaría
el plan APPCC en la operativa diaria de verdad, con un reparto de
responsabilidades por rol. Su idea concreta, con la que `blog-redaccion`
ha desarrollado la ampliación: que el cocinero o cocinera sea quien
revisa y registra las cámaras/neveras de materia prima y de cocina, que el
bartender o barista se encargue de las neveras y vitrinas de bebida
(incluidos productos frescos de barra y limpieza de máquina de café/líneas
de cerveza), y que el encargado de turno o gerente no rellene cada
registro sino que consolide y revise de verdad lo registrado, actuando si
algo falla. `blog-redaccion` ha ampliado el H2 3 ("Cómo integrar el APPCC
en el día a día...") con este reparto de responsabilidades, argumentando
explícitamente el porqué de consultoría: asignar por rol conecta la
responsabilidad con quien ya tiene el hábito de usar esa nevera cada día y
quien antes detecta una anomalía (puerta que no cierra, temperatura rara),
en vez de repartir el papeleo por jerarquía o "quien esté libre". Se
añadió una cadencia simple (registro diario al abrir turno por zona,
revisión semanal del conjunto por el encargado) sin ofrecer ninguna
plantilla descargable, coherente con lo que el propio artículo ya explica
sobre por qué no se entrega una plantilla genérica. No se ha tocado ningún
otro contenido del artículo (marco normativo, ejemplo de estructura,
errores de inspección, cierre) ni ningún dato o cifra ya existente — la
ampliación queda dentro del H2 3, no como sección nueva, y conecta de
forma natural con el cierre ya existente sobre la fase Run del BAR Method
(lo refuerza, no lo sustituye). El artículo pasa de "Redacción final" a
**Borrador** en la tabla de seguimiento, porque este añadido de contenido
real requiere una nueva pasada de `blog-revision-seo-calidad` antes de
darlo otra vez por definitivo.

**Reestructuración de fondo del Tema 6 (2026-09-28), instrucción directa
de Andrea tras leer la redacción final.** A diferencia de las pasadas
anteriores sobre este mismo artículo (que eran solo de estilo, sin tocar
contenido ni balance), esta vez Andrea pidió explícitamente un cambio de
fondo: menos peso del aparato de estudios y más peso de la aplicación
práctica del menu engineering cruzado con el escandallo. En concreto: (1)
recortar la extensión y el detalle de cifras de la sección "Cruzar
rentabilidad con lo que el cliente percibe como valor" (Coca-Cola Lens,
caso Papa John's, McKinsey) y de la sección de errores de diseño
(Bournemouth, Cornell/CIA, Gregg Rapp), conservando la idea de fondo de
cada una pero sin desglosar cada porcentaje ni encadenar estudios; y (2)
convertir el ejemplo de "qué hacer con cada tipo de plato" —que antes era
una nota de dos líneas después de explicar la matriz— en una sección
propia y central del artículo, justo después de explicar los 4 cuadrantes,
con recomendaciones de acción concretas para cada tipo de plato (Estrellas,
Caballos de batalla, Puzles, Perros): qué hacer con el precio, la ración,
la posición en la carta, el proveedor y el nombre del plato, cruzando
siempre la decisión con el dato del escandallo. `blog-redaccion` ha
reescrito el artículo con este nuevo balance:

- La sección de valor percibido se resume a la idea central (el cliente no
  compra solo margen, compra percepción de valor) en unas pocas frases,
  sin desglosar los cuatro ejes de Coca-Cola Lens en porcentajes ni contar
  el caso Papa John's con el mismo nivel de detalle de antes. La sección
  de errores de diseño se recorta de forma equivalente, manteniendo la
  idea de "demasiadas opciones cuesta dinero" y "el anclaje de precio
  funciona pero se puede detectar" de forma breve y práctica.
- El origen académico de la matriz (Kasavana y Smith, 1982) queda en una
  sola frase dentro del H2 1, no en un párrafo aparte.
- Ningún matiz de precisión se ha perdido en el recorte: Inpulse.ai sigue
  marcado explícitamente como mercado francés, la tensión de raciones
  sigue descrita como hipótesis propia sin cerrar, y el estudio Cornell/CIA
  de 2007 sigue marcado como técnica clásica, no como hallazgo reciente.
  Es un recorte de extensión y de peso relativo, no una pérdida de
  honestidad sobre qué está verificado y qué no.
- La nueva sección central ("Qué hacer con cada tipo de plato: estrellas,
  caballos de batalla, puzles y perros") se coloca justo después del H2 1
  (matriz de los 4 cuadrantes) y antes de la sección de valor percibido.
  Para cada uno de los cuatro tipos explica qué significa de verdad para
  el negocio (no solo la definición de margen/popularidad) y da 2-3
  recomendaciones de acción concretas que cruzan el escandallo con la
  decisión de carta (precio, ración, posición, proveedor, nombre del
  plato) — por ejemplo, un caballo de batalla no se sube de precio de
  golpe, primero se mira si hay margen de renegociar proveedor o ajustar
  ración; un puzle no se quita a la primera, se prueba a renombrarlo,
  reposicionarlo o convertirlo en recomendación del camarero; un perro no
  siempre se elimina sin más, a veces sus ingredientes se reaprovechan en
  otro plato antes de descatalogarlo.
- El ejemplo ya existente de la carta italiana (linguine/pollo
  parmesano/pasta de temporada/ensalada) se mantiene y se expande con la
  recomendación concreta para cada plato. Se añade un segundo ejemplo
  completo con un negocio de otro tipo, tal como pedía Andrea: un bar de
  tapas, con las patatas bravas como estrella, las croquetas caseras como
  caballo de batalla (coste de mano de obra que se come el margen), el
  pescado del día como puzle (mal colocado y sin nombre atractivo en la
  carta) y una ensalada mixta genérica como perro.
- El checklist final y el cierre del artículo (idea propia de TBNB sobre
  decidir la estética en último lugar) se mantienen, con un único añadido
  al checklist para reflejar la nueva sección ("¿sabes qué hacer con cada
  cuadrante, no solo dónde cae cada plato?").
- La meta descripción y los enlaces internos existentes (incluida la nota
  entre corchetes pendiente de sustituir por la URL real del Tema 5) se
  mantienen exactamente igual, tal como pedía la instrucción de Andrea.

El artículo vuelve a **Borrador** en la tabla de seguimiento, porque este
es un cambio de fondo (no una pasada de estilo) y requiere una nueva
pasada completa de `blog-revision-seo-calidad` antes de considerarlo otra
vez definitivo.

**Mención de servicio añadida al Tema 1 (2026-09-28), petición directa de
Andrea.** Sobre la redacción final ya entregada del Tema 1, Andrea pidió
una única frase (no un bloque de CTA) que mencionara de forma sutil que
parte de acompañar una apertura en TBNB es ayudar a encontrar el local que
encaja con el concepto del cliente antes de firmar — no solo advertir
sobre licencias, sino evitar el problema desde el origen. `blog-redaccion`
añadió una sola frase junto al H2 2 (certificado de compatibilidad
urbanística), justo después del párrafo que explica por qué un local puede
estar clasificado para "comercio" y no para "hostelería" en el
planeamiento: *"En TBNB, parte de acompañar una apertura es justo eso:
ayudar a encontrar el local que encaja con el concepto antes de firmar, no
solo avisar de qué licencia toca después."* No se prometen plazos, precios
ni alcance concreto del servicio, no hay enlace de contacto ni llamada a
la acción de venta, y no se ha tocado ningún otro contenido del
artículo: mismo H1, mismos H2, mismos datos (separación normativa
estatal/autonómica, certificado de compatibilidad urbanística, ejemplo de
Barcelona no generalizable, ordenanzas de terraza de Madrid/Granada/
Valencia) y mismo enlace interno a la "Guía Completa para Abrir un Bar".

## Seguimiento por artículo

Fases: 🟡 Estrategia (ángulo definido) → 🟡 Investigación → 🟡 Borrador →
🟡 Revisión → 🟢 Publicado.

| Tema | Fase | Artículo | Notas |
|---|---|---|---|
| 1. Licencias para abrir un restaurante | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/licencias-para-abrir-un-restaurante.md`](articulos/licencias-para-abrir-un-restaurante.md) | Prioridad de trabajo: Media. Redacción final de estilo aplicada el 2026-09-28 por instrucción directa de Andrea: mismo contenido, datos y ángulo del borrador ya aprobado (certificado de compatibilidad urbanística como pieza central del H2-2, separación estatal/CCAA-municipio intacta, ejemplo de Barcelona no generalizable, ordenanzas de terraza de Madrid/Granada/Valencia como casos distintos), con las tres variantes de keyword ("licencias para abrir un restaurante", "licencia para abrir un restaurante", "licencias para abrir un restaurante en España") reforzadas en título, entradilla, H2 1 y meta descripción, y tono más ameno, menos enumerativo. Enlace interno a "Guía Completa para Abrir un Bar" sin cambios (misma URL verificada). **Mención de servicio añadida (2026-09-28), petición directa de Andrea:** una única frase junto al H2 2, sin CTA de venta ni enlace de contacto, sin prometer plazos/precios/alcance, mencionando que parte de acompañar una apertura en TBNB es ayudar a encontrar el local que encaja con el concepto antes de firmar. No se ha tocado ningún otro contenido. Pendiente de `blog-revision-seo-calidad`. |
| 2. Ayudas de proveedores para montar un bar | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/ayudas-para-montar-un-bar.md`](articulos/ayudas-para-montar-un-bar.md) | Prioridad de trabajo: Media-alta. Artículo "paraguas" de los Temas 3 y 4: distingue subvenciones públicas dispersas por CCAA (sin programa único nacional) de acuerdos comerciales con proveedores, cuantifica el coste de la exclusividad con el Reglamento (UE) 2022/720 como dato legal de respaldo (límite de 5 años), presenta ICO/renting como alternativas (cifra ICO marcada como de agregador, pendiente de verificar en ico.es) y cierra citando Inpulse.ai (hospitality-report). Enlaza a los Temas 3 y 4 en el H2 4 con nota "enlace pendiente de publicación" en vez de URL inventada. Pasada final de estilo (2026-09-28, instrucción directa de Andrea): tono directo de socio en segunda persona en vez de tono de informe, keyword "ayudas de proveedores para montar un bar" reforzada de forma natural en entradilla y H2 1, sin cambios de dato ni de ángulo. Pendiente de `blog-revision-seo-calidad`. |
| 3. Ayudas de Estrella Galicia | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/estrella-galicia-te-monta-el-bar.md`](articulos/estrella-galicia-te-monta-el-bar.md) | Prioridad de trabajo: Alta. **Aviso de nombre no verificado resuelto:** el H1/entradilla mantiene la keyword buscada, y el 2º párrafo aclara sin rodeos que no es un programa oficial con ficha pública, nombrando "The Hop" y "Cervecerías Circulares" como lo real y verificable de la marca. Letra pequeña (exclusividad 5-10 años, rappel 75/25, penalizaciones) presentada explícitamente como algo que se repite en el sector, nunca como condición confirmada de Estrella Galicia. El Reglamento (UE) 2022/720 (límite de 5 años) se usa como el dato con más peso de esa sección. Enlaces a Temas 2 y 4 con nota de "pendiente de publicación". Pasada final de estilo (2026-09-28, instrucción directa de Andrea): tono más conversacional y directo (segunda persona, "vamos a ser claros"), sin tocar el aviso legal/editorial sobre el nombre no oficial ni ningún dato de la letra pequeña, que se cuenta de forma menos "legal" pero con la misma precisión. Pendiente de `blog-revision-seo-calidad`. |
| 4. Ayudas de Mahou | 🟢 Redacción final — pendiente de revisión de tono/SEO antes de publicar | [`blog-web/articulos/mahou-te-monta-el-bar.md`](articulos/mahou-te-monta-el-bar.md) | Prioridad de trabajo: Alta. **Aviso de nombre no verificado resuelto:** "Bar Uno" no aparece en ningún punto del artículo; el 2º párrafo aclara que no hay programa oficial con el nombre buscado y nombra "+Bar", "Nexho" y "Más con Mahou San Miguel" como lo real y verificable, con detalle de qué ofrece cada uno. La afirmación de Nexho de que la exclusividad "está prohibida en España" **no se repite** — se sustituye por la versión correcta del Reglamento (UE) 2022/720 (limitada a 5 años, no prohibida). El H2 3 construye un ejemplo numérico con supuestos explícitamente declarados como hipotéticos, no como cifras reales de Mahou. Enlaces a Temas 2 y 3 con nota de "pendiente de publicación". Pasada final de estilo (2026-09-28, instrucción directa de Andrea): mismo tono directo y conversacional que en Estrella Galicia, con el aviso sobre "Bar Uno"/nombre no oficial y la corrección a Nexho intactos, sin cambios en el ejemplo numérico ni en ningún otro dato. Pendiente de `blog-revision-seo-calidad`. |
| 5. Escandallos y food cost | 🟢 Redacción final v2 — ángulo ajustado (menos peso a 2021, cadencia semestral) — pendiente de nueva revisión de tono/SEO | [`blog-web/articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md`](articulos/food-cost-2026-por-que-el-calculo-ya-no-vale.md) | Ya había sido revisado por `blog-revision-seo-calidad` y por Andrea/Sergio en cuanto a estructura, checklist SEO y enlaces (ver historial arriba: enlace a `escandallo-evitar-desperdicio-restaurante/` verificado real, y enlace añadido a "Cómo calcular la rentabilidad de un negocio de hostelería" para resolver la canibalización), y había pasado además por una pasada de estilo final el 2026-09-28. **Ajuste v2 (2026-09-28, mismo día, instrucción directa de Andrea):** se corrigió el peso excesivo de "2021"/"hace tres años" — H1 nuevo ("Food cost en 2026: por qué revisarlo una vez al año ya no basta"), meta descripción y H2 1 reescritos para centrar el mensaje en la cadencia de revisión (dos veces al año como mínimo), dejando el +30% acumulado desde 2021 (INE) como contexto de fondo, no como titular. H2 2 y H2 3 pierden las menciones sueltas de "hace tres años"/"desde 2021" fuera de ese contexto. H2 4 incorpora explícitamente la recomendación de revisar el escandallo dos veces al año como mínimo (más a menudo en ingredientes volátiles), y el cierre se reescribió en la misma línea ("el problema es la frecuencia con la que le preguntas"). No se ha tocado el dato de rentabilidad 2025 (Hosteltur/Anuario), el dato de Inpulse.ai (con su matiz de mercado francés), el SMI, los rangos de food cost por tipo de negocio, el ejemplo de la pasta boloñesa, el caso del pollo frito viral, ni los dos enlaces internos (mismas URLs). Sigue pendiente, como punto abierto ya señalado, que Andrea/Sergio verifiquen directamente las cifras de INE/Hosteltur antes de publicar en la web en vivo. Requiere una nueva pasada completa de `blog-revision-seo-calidad` (no solo repasar el checklist ya visto antes del ajuste v2). |
| 6. Diseño de carta de restaurante | 🟡 Borrador (reestructurado) — pendiente de nueva revisión de tono/SEO antes de publicar | [`blog-web/articulos/disenar-carta-restaurante-por-que-la-estetica-es-lo-ultimo.md`](articulos/disenar-carta-restaurante-por-que-la-estetica-es-lo-ultimo.md) | Prioridad de trabajo: Alta. **Reestructuración de fondo (2026-09-28), instrucción directa de Andrea** (ver detalle completo arriba, no es una pasada de estilo): se recorta el peso del aparato de estudios en "Cruzar rentabilidad con lo que el cliente percibe como valor" (Coca-Cola Lens/Papa John's/McKinsey resumidos a la idea central) y en "Errores en el diseño" (Bournemouth/Cornell-CIA/Gregg Rapp contados de forma breve), y el origen de la matriz (Kasavana y Smith, 1982) queda en una frase. A cambio, se crea una sección propia y central, justo después de explicar los 4 cuadrantes ("Qué hacer con cada tipo de plato: estrellas, caballos de batalla, puzles y perros"), con 2-3 recomendaciones de acción concretas por tipo de plato (precio, ración, posición, proveedor, nombre), el ejemplo de la carta italiana expandido y un segundo ejemplo nuevo de un bar de tapas (croquetas como caballo de batalla, pescado del día como puzle, ensalada genérica como perro, patatas bravas como estrella). Ningún matiz de precisión se ha perdido en el recorte: raciones grandes/pequeñas sigue como hipótesis sin cerrar, Inpulse.ai sigue marcado como mercado francés, Cornell/CIA 2007 sigue marcado como técnica clásica no reciente. Meta descripción y enlaces internos sin cambios (incluido el enlace entre corchetes al Tema 5, aún pendiente de URL real). Checklist y cierre se mantienen, con un ítem añadido al checklist sobre la nueva sección. Pasa a **Borrador** porque este es un cambio de fondo y necesita una nueva pasada completa de `blog-revision-seo-calidad` antes de darlo otra vez por definitivo. |
| 7. Sanidad y APPCC | 🟡 Borrador (ampliado) — pendiente de nueva revisión de tono/SEO antes de publicar | [`blog-web/articulos/appcc-restaurante-tenerlo-vs-usarlo.md`](articulos/appcc-restaurante-tenerlo-vs-usarlo.md) | Prioridad de trabajo: Media. Ángulo operativo honesto (tenerlo vs. usarlo) confirmado, sin dato propio fuerte del Hospitality Report. El 2026-09-28 se aplicó, por instrucción directa de Andrea, la pasada final de estilo (amena, sin sonar a informe) sin tocar contenido, datos ni ángulo respecto al borrador ya aprobado. H1 y H2 revisados para cubrir explícitamente las keywords de la sección 7 de `listado-temas.md` (plan APPCC restaurante, APPCC restaurante ejemplo, plantilla APPCC restaurante, requisitos sanitarios para abrir un restaurante, seguridad alimentaria restaurante). El matiz del rango de sanción 3.000-30.000€ (fuente única de consultoría, no normativa autonómica contrastada) y toda la normativa citada (Reglamento (CE) 852/2004, RD 1021/2022, RD 109/2010, Ley 1/2025) se mantienen intactos. Sigue sin enlace interno en el cuerpo por falta de uno verificado. **Ampliación de contenido (2026-09-28, instrucción directa de Andrea):** el H2 3 incorpora ahora un reparto de responsabilidades por rol en la operativa diaria del plan APPCC — cocina/cocinero(a) responsable de cámaras y neveras de materia prima y cocción, barra/bartender-barista responsable de neveras y vitrinas de bebida (más productos frescos de barra y limpieza de máquina de café/líneas de cerveza), y encargado de turno/gerente que no rellena registros pero consolida, revisa de verdad y actúa si algo falla. Incluye el porqué de consultoría (quien usa la nevera cada día es quien antes detecta la anomalía) y una cadencia simple (registro diario por zona, revisión semanal del conjunto), sin ofrecer plantilla descargable. No se ha tocado ningún otro contenido del artículo. Pasa a **Borrador** porque este añadido real de contenido requiere nueva pasada de `blog-revision-seo-calidad` antes de considerarlo otra vez definitivo. |

## Próximo paso

De los 7 temas del proyecto, 5 (Temas 1, 2, 3, 4 y 5) tienen su redacción
final de estilo aplicada y están pendientes solo de pasar por
`blog-revision-seo-calidad` como versión definitiva — con la salvedad de
que el Tema 5 acaba de recibir además un ajuste v2 de ángulo (menos peso a
2021, cadencia semestral) el mismo día, así que su revisión debe ser
completa, no solo un repaso de lo ya visto antes del ajuste. Los otros dos,
Tema 6 y Tema 7, volvieron a **Borrador** el 2026-09-28 tras recibir
cambios reales de contenido pedidos directamente por Andrea
(reestructuración de fondo en el Tema 6, ampliación del reparto de
responsabilidades en el Tema 7) y necesitan una revisión completa, no solo
una repasada de lo ya visto antes.

Todos quedan pendientes de que `blog-revision-seo-calidad` confirme el
checklist SEO on-page y el tono sobre esta versión antes de que
Andrea/Sergio los aprueben para publicar. Puntos particulares a vigilar en
esa revisión:

- **Tema 1:** revisar la frase de mención de servicio añadida junto al H2
  2 (certificado de compatibilidad urbanística) a petición de Andrea —
  confirmar que sigue leyéndose como una sola frase integrada, sin sonar a
  publicidad ni romper el tono informativo del resto del artículo.
- **Tema 5:** revisar específicamente el ajuste v2 del ángulo (H1 y meta
  descripción nuevos centrados en la cadencia semestral, +30% desde 2021
  degradado a contexto de fondo en el H2 1, menciones sueltas de "hace tres
  años" eliminadas del H2 2 y del título del H2 3, recomendación explícita
  de revisar dos veces al año añadida al H2 4 y al cierre) — no es solo
  repasar el checklist SEO ya aprobado antes del ajuste. Además, verificar
  directamente las cifras de INE/Hosteltur antes de publicar en la web en
  vivo (punto abierto ya señalado por Andrea/Sergio).
- **Tema 6:** revisar específicamente el nuevo balance del artículo tras la
  reestructuración de fondo (menos peso de estudios en las secciones de
  valor percibido y errores de diseño, nueva sección central de
  recomendaciones por tipo de plato con los dos ejemplos, carta italiana y
  bar de tapas) — no es solo repasar lo ya revisado antes. Sustituir además
  el enlace entre corchetes al Tema 5 por la URL real en cuanto ese
  artículo se publique.
- **Tema 7:** revisar específicamente la nueva ampliación del H2 3 (reparto
  cocina/barra/encargado) como parte fresca de contenido, no solo repasar
  lo ya revisado antes.
- **Bloque 2/3/4:** sustituir las notas de "enlace pendiente de
  publicación" entre los tres artículos por URLs reales en cuanto se
  publiquen (ninguno de los tres tiene URL propia todavía), y confirmar
  que el tratamiento del aviso sobre nombres de programa no verificados
  (Estrella Galicia / Mahou) sigue quedando resuelto con el mismo criterio
  tras la pasada de estilo final — el aviso se mantiene íntegro en
  contenido, solo contado de forma más conversacional.
</content>

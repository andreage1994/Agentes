# Curación #1 — `/como-calcular-la-rentabilidad-de-un-negocio-de-hosteleria/`

**Brief de investigación** (no es el artículo). Partido del ángulo ya
fijado por `blog-estrategia-seo` en `seo/blog-web/curacion-estrategia.md`
(punto 1): mantener el rol de "mapa entero" (todos los costes) frente al
food cost específico, incorporar el dato de rentabilidad sectorial 2025 y
la cita de Inpulse.ai ya usada en el Tema 5, respetar el reparto de roles
ya decidido por Andrea entre este artículo, el de food cost y el de la
regla 50/30/20.

## Aviso de bloqueo que condiciona todo este brief

**No se ha podido leer el artículo tal cual está publicado hoy.**
`thebarnbarconsulting.com` no resuelve en esta sesión (`WebFetch` devuelve
`ENOTFOUND`, no `EGRESS_BLOCKED` — parece que el dominio no está en la
lista de redes permitidas de esta sesión concreta, a diferencia de otras
sesiones previas del proyecto que sí llegaron a verificar URLs de este
dominio por `WebSearch` directo). Tampoco `WebSearch` ha devuelto ningún
snippet indexado del contenido real del artículo (varias búsquedas con el
dominio y con el título exacto no encontraron nada). **Esto hay que
resolverlo antes de que `blog-redaccion` reescriba el artículo**: hace
falta que alguien con acceso directo (Andrea/Sergio, o una sesión con ese
dominio permitido) confirme qué dice hoy exactamente el cuerpo del
artículo, para no reescribir a ciegas sobre su estructura actual. Todo lo
que sigue es investigación de contexto y competencia, no una comparación
directa contra el texto vivo.

## 1. Lo que ya es conocimiento propio de TBNB (verificado en la matriz)

- **Anuario de la Hostelería de España 2025 + INE (IPC feb 2026)**, vía
  research interno TBNB "Tendencias gastronómicas España 2026" (oct
  2026): la producción de la restauración española creció a 116.193 M€ en
  2024 (+9,9%) y llegaron 96,8 millones de turistas internacionales en
  2025 (+3,2%), pero la **rentabilidad del sector fue negativa en
  ene-sept 2025 (−0,9%)** y el gasto por persona cayó a 1.146€ (−1,6%),
  con el IPC de restauración (4,8%) muy por encima del IPC general (2,3%,
  feb 2026). Fuente: `hospitality-report/matriz-tematica.md`, sección 02.
  Este es el dato que el ángulo ya pide incorporar — confirmado tal cual.
- **Inpulse.ai, "Concepts de restauration en 2026"** (Francia; bloqueado
  por red, reconstruido vía `WebSearch` en una sesión anterior del
  proyecto, ya documentado así en la matriz): *"Las tendencias atraen a
  los clientes, los márgenes los retienen"* — cita ya usada en el Tema 5
  (food cost) y disponible para reutilizar aquí sin volver a verificarla.
  Mismo informe: incluso negocios con estrella Michelin cierran el mes
  con un margen neto del 3-4%; los conceptos que fracasan no lo hacen por
  falta de producto, sino por gestión de stock aproximada y food cost mal
  controlado. **Importante no perder el matiz ya exigido en el Tema 5**:
  es mercado francés, no español — debe seguir marcándose así si se
  reutiliza aquí.
- **Barómetro HIP 2026** (vía Vinetur, mar 2026): el 55,2% de los
  hosteleros españoles se declara en crecimiento y el 33,2% planea abrir
  nuevos locales en 2026 pese a la inflación — convive con la
  rentabilidad negativa del Anuario. Mismo patrón de "crecimiento con
  fragilidad individual" ya documentado para Francia (Inpulse.ai).
- **Reparto de roles ya decidido por Andrea (no reabrir)**: este artículo
  es "el mapa entero" (personal, alquiler, food cost, amortización)
  frente al food cost específico (Tema 5, ya publicado como "Food cost en
  2026: por qué revisarlo una vez al año ya no basta") y frente a la
  regla 50/30/20 (framework corto de referencia, #7 de la cola de
  curación). No duplicar el contenido de ninguno de los dos — reforzar el
  enlace cruzado en ambas direcciones.
- **Contenido fragmentado a vigilar, no a competir**: `/rentabilidad-
  restaurante-lleno-sin-beneficios/`, `/restaurante-factura-pero-no-
  gana/`, `/tu-restaurante-esta-lleno-pero-no-ganas-dinero/` — no se
  reescriben aquí (decisión de `seo-arquitectura-web`), pero el ángulo de
  este artículo como pieza "pilar" que absorbe esa intención por enlace
  interno sigue siendo válido.

## 2. Investigación nueva de mercado (2026, vía `WebSearch` — fuentes bloqueadas en fetch directo)

Todas las fuentes de este apartado dieron `ENOTFOUND`/bloqueo en
`WebFetch` (qamarero.com, Forbes, Hosteltur, CaixaBank Research, El
Español) — lo que sigue se reconstruyó con `WebSearch` sobre fragmentos
indexados, nunca con lectura directa. Se marca así explícitamente, no se
presenta como lectura completa.

- **Forbes España, citando a Hostelería de España (2026)**: los ingresos
  del sector subieron hasta un 4% en 2025 y se moderarán a un 3% en 2026;
  José Luis Álvarez Almeida (presidente de Hostelería de España) señala
  como amenazas a la rentabilidad el aumento de costes, el estrés
  regulatorio, la falta de relevo generacional y el aumento de la
  fiscalidad — contexto más amplio y con nombre propio para el mismo dato
  de rentabilidad negativa ya conocido. *(Vía fragmentos indexados, no
  lectura directa del artículo original — fecha/URL exacta de Forbes no
  confirmada con precisión, aparece como `forbes.es/?p=846770`.)*
- **Barómetro HIP 2026** (detalle nuevo no recogido aún en la matriz): el
  40,5% de los hosteleros señala la subida de costes como su principal
  amenaza; frente a eso, el 44,8% responde bajando costes operativos, el
  36,2% con digitalización y el 34% subiendo precios al cliente. Dato útil
  para un posible H2 de "qué está haciendo el sector al respecto", si
  encaja con la estructura ya definida por `blog-estrategia-seo` (a
  confirmar contra el H2 real, pendiente del bloqueo de lectura del
  artículo).
- **CaixaBank Research, Pedro Álvarez Ondina, "La elevada rotación
  empresarial, la asignatura pendiente de la restauración española"**
  (20 ene 2026) y **"La rotación empresarial, un reto estructural de la
  restauración española"** (6 feb 2026): el sector de restauración tiene
  una de las tasas de rotación empresarial más altas de la economía
  española, solo por detrás de información y telecomunicaciones —en
  torno al 21% en 2023-2024— y concentra más empresas jóvenes que el
  conjunto de la economía. **Dato nuevo, español, con fecha 2026 y
  fuente con nombre propio (banco, no blog de software)** — no estaba en
  la matriz del Hospitality Report. Encaja bien como refuerzo de "por qué
  calcular la rentabilidad real importa más que nunca": un sector que
  rota al 21% no es solo un sector que crece con margen ajustado, es un
  sector donde muchos negocios no llegan a consolidarse. Posible dato de
  apoyo nuevo para el H1/H2 de apertura del artículo, no solo para el
  cierre.
- **El Español, serie de reportajes sobre "María" y otros hosteleros con
  menú del día** (varias piezas, abr-sep 2026): caso real de una dueña de
  restaurante que vende unos 40 menús/día a 12€, con un coste aproximado
  de 8-8,50€ por menú, y un beneficio neto final de en torno a 1.500€/mes
  (las distintas piezas no coinciden del todo en si esa cifra es para la
  pareja de socios o por persona — tratar como aproximado, no como dato
  limpio). El precio medio nacional del menú del día es de unos 14,7€
  (Hostelería de España/Edenred, 2026), así que el caso de María está por
  debajo de la media. **Es un ejemplo real y reciente (prensa española
  2026) de "facturar y aun así ganar poco"**, coherente con el ángulo —
  pero citarlo con la reserva explícita de que las cifras varían algo
  entre las distintas piezas de El Español, y que es un caso de prensa,
  no un dato de TBNB. Puede servir como anécdota ilustrativa si
  `blog-redaccion` quiere humanizar la fórmula, no como estadística.

## 3. Qué está rankeando hoy para "cómo calcular la rentabilidad de un negocio de hostelería" — qué le falta a la competencia

Investigado vía `WebSearch` (fetch directo a los dominios bloqueado):
qamarero.com, combohr.com, skello.es, mews.com, sage.com, siteminder.com,
smartorder.ai, yo-facturo.com aparecen como el tipo de contenido que
rankea para esta búsqueda.

- **Todos explican lo mismo**: margen bruto = (Ingresos − coste de
  ventas) / Ingresos; margen operativo = resta también gastos operativos;
  margen neto = beneficio neto / ingresos. Ningún competidor aporta
  estructura distinta de la fórmula — esto no es diferenciador posible,
  es tabla stakes.
- **El fallo real de la competencia, y la oportunidad clara para TBNB**:
  los rangos de "margen saludable" que dan estos competidores son
  **contradictorios entre sí y sin fuente oficial**: ComboHR cita 15-20%
  (atribuido a la revista Emprendedores, sin más detalle), Skello da
  5-15%, Qamarero da 3-5%. Ninguno de los tres cita una fuente primaria
  verificable con fecha para ese rango — son cifras de blog repetidas sin
  trazabilidad. **TBNB sí tiene un dato real, con fuente y fecha, que
  ninguno de estos competidores usa**: la rentabilidad del sector español
  fue negativa (−0,9%) en 2025 (Anuario de la Hostelería de España/INE).
  Dar ese dato de contexto español real, en vez de (o adicionalmente a)
  un rango de "margen saludable" sin fuente, es exactamente el tipo de
  ventaja competitiva que puede ganar el featured snippet — "¿qué margen
  es normal en hostelería?" es justo el tipo de pregunta que hoy
  responden mal, con cifras sin sourcing, los competidores que ya
  rankean.
- **Ningún competidor conecta el cálculo con 2026 ni con el contexto
  español de presión de costes/regulación** — todos presentan la fórmula
  como un ejercicio atemporal. Esto confirma que el ángulo ya decidido
  por `blog-estrategia-seo` (quien busca esto hoy no calcula por
  curiosidad, calcula porque el margen aprieta) es un diferenciador real
  frente a lo que ya rankea, no solo una idea razonable sobre el papel.
- **Ninguno cita la cita de Inpulse.ai** ("las tendencias atraen a los
  clientes, los márgenes los retienen") ni ningún dato equivalente de
  gestión de stock/food cost como causa de fracaso — es terreno libre
  para diferenciarse con una idea, no solo con una fórmula.

## 4. Matices y tensiones que `blog-estrategia-seo`/`blog-redaccion` deben tener en cuenta

- El ángulo pide "incorporar el dato de 2025" — confirmado que ese dato
  existe y está bien sourceado, pero el artículo necesita además la
  verificación directa de lectura (ver aviso de bloqueo arriba) para
  saber si ya cita algún dato de rentabilidad anterior que haya que
  sustituir o si es un hueco nuevo que rellenar.
- El dato de rotación empresarial de CaixaBank Research (21%, solo detrás
  de TIC) es nuevo, no estaba anticipado por `blog-estrategia-seo` ni en
  la matriz del Hospitality Report — se ofrece aquí como hallazgo
  adicional, no como sustituto de los datos ya pedidos en el ángulo.
- El caso de "María" (El Español) es prensa, con cifras algo
  inconsistentes entre piezas — no es un dato de la misma categoría de
  fiabilidad que el Anuario/INE o Inpulse.ai. Usarlo, si se usa, como
  ejemplo ilustrativo con esa reserva explícita, nunca como estadística
  sectorial.
- No se ha podido confirmar si el artículo actual ya menciona el food
  cost en detalle (lo que podría generar la propia canibalización con el
  Tema 5 que el ángulo ya busca evitar) — de nuevo, pendiente de lectura
  directa antes de redactar.

## 5. Enlaces internos posibles (ya verificados en el proyecto, no inventados)

- `/que-es-la-regla-50-30-20-en-la-hosteleria/` — framework corto de
  referencia, ya señalado por `blog-estrategia-seo` como parte del mismo
  trío de rentabilidad (#7 de la cola de curación).
- El artículo de food cost del Tema 5, ya publicado en la web según
  `seo/blog-web/estado.md` ("Food cost en 2026: por qué revisarlo una vez
  al año ya no basta") — el propio Tema 5 ya enlaza hacia este artículo
  como "el mapa entero"; falta reforzar el enlace en sentido inverso, tal
  como pide el ángulo.
- `/punto-de-equilibrio-en-restauracion-cuanto-necesitas-vender/` (#4 de
  la cola de curación) — mismo universo de cálculo financiero del
  negocio, intención complementaria (margen vs. umbral de ventas).
- No se confirma ningún enlace nuevo hacia las tres páginas fragmentadas
  de rentabilidad (`/rentabilidad-restaurante-lleno-sin-beneficios/`,
  etc.) — esa decisión de fusión/enlace es de `seo-arquitectura-web`, no
  de este brief.

## 6. Resumen para `blog-redaccion`

El ángulo original se sostiene y se refuerza con más contexto del que
tenía: el dato de rentabilidad −0,9% sigue siendo el dato ancla, con dos
piezas nuevas de apoyo (rotación empresarial del 21% vía CaixaBank
Research, y el contraste con los rangos de margen sin fuente que da la
competencia). **Lo único que bloquea avanzar con seguridad total es la
imposibilidad de leer el artículo publicado hoy** — se recomienda que
Andrea/Sergio confirmen el contenido actual (estructura de H2, si ya cita
algún dato de rentabilidad antiguo, si ya menciona food cost) antes de que
`blog-redaccion` reescriba, para no duplicar ni contradecir sin saberlo lo
que ya está en vivo.

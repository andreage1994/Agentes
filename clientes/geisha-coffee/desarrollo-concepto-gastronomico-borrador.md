# Desarrollo Concepto Gastronómico — Geisha Specialty Coffee

**Servicio:** AR02 — Desarrollo gastronómico (BAR Method, fase Architecture)
**Estado del documento:** BORRADOR — secciones 1 a 3 completas. Secciones 4 a 7
(Product Strategy, Estrategia Económica, Recomendaciones de diseño de carta,
Siguientes pasos) pendientes de una siguiente pasada, idealmente después de que
`culinary-development` valide viabilidad técnica de las 20 referencias
candidatas de este borrador.
**Autoría:** `chef-ejecutivo` (TBNB), sobre dato real de cliente. Pendiente de
revisión por Andrea/Sergio antes de cualquier envío al cliente.
**Fecha:** 2026-10-15.
**Actualización 2026-10-22:** a petición directa de Andrea, se añade una capa
de identidad propia a las 20 referencias candidatas de la sección 3.5 —
matices pequeños y reales de especia/técnica tradicional japonesa, coherentes
con el nombre Geisha, nunca un giro hacia cocina de fusión completa — y se
define por primera vez un producto concreto para la referencia 20 ("Ritual
Semanal"), que hasta hoy no lo tenía (hallazgo de `culinary-development` en su
validación técnica del 2026-10-22). El resto del documento (secciones 1, 2.2,
2.3, 3.1-3.4, 3.6) no se ha modificado de fondo; solo se añade en 2.1 una
frase que ancla esta capa de identidad en el posicionamiento ya aprobado.

---

## 1. Resumen Ejecutivo

Geisha Specialty Coffee tiene un problema de negocio muy concreto, y los
cinco años de datos de venta (Loyverse) lo dejan ver con claridad: **el café
funciona, la comida se está quedando atrás.** El ticket medio sube cada año
(7,20€ en 2022 a 9,75€ en los últimos 12 meses) casi enteramente tirado por el
café — y en particular por el filtro, que crece +27% en unidades y +31% en
ingreso y ya es el 15% del ingreso de bebida con solo el 6% de las unidades.
La comida, en cambio, cae: -7% en unidades y -5% en euros en el último año, y
el porcentaje de tickets que llevan comida baja de 41% (2024) a 37% (2025) y
34-36% en el local nuevo. De los ~47.800 tickets anuales, unos **29.500 son
hoy de solo bebida** — ese es, literalmente, el público objetivo de todo este
desarrollo gastronómico.

La buena noticia es que ese problema tiene una palanca clara y ya validada
por el propio comportamiento del cliente: un ticket con comida factura
14,39€ frente a 7,11€ sin ella, así que cada punto de conversión que se
recupere vale aproximadamente 480 tickets con comida al año. El objetivo de
negocio del cliente — subir el ticket medio de 10€ a 13-15€ **sin tocar
precios** — se resuelve así: con mix de producto y con conversión a comida,
no con pricing.

Este documento propone una dirección gastronómica que no inventa un
posicionamiento nuevo: parte del que Geisha ya tiene (el café es el centro,
la comida acompaña discretamente sin perder calidad, "el mejor producto al
mejor precio posible") y lo traduce en una arquitectura de carta y en **20
referencias candidatas** ancladas, cada una, en un dato real de venta
concreto — qué crece, qué cae, qué pairing ya existe de forma natural y qué
hueco de conversión hay que cerrar. El cliente y Andrea/Sergio seleccionarán
de estas 20 las 10 que entran dentro del alcance contratado de AR02.

**Aviso de carácter consultivo:** esta propuesta es una dirección
estratégica y de producto, no una garantía de resultado. La viabilidad
técnica (espacio, equipamiento, tiempos de producción) la valida
`culinary-development` a continuación, y el food cost depende de
escandallos que hoy no están actualizados (los últimos son de hace 6 años).
Ninguna referencia de este documento debe darse por cerrada en carta hasta
pasar por esa validación.

---

## 2. Estrategia Gastronómica

### 2.1 Posicionamiento gastronómico

Geisha Specialty Coffee ya tiene una identidad de marca propia (Brand Kit +
Brand Book del cliente) que este documento no reemplaza ni reinterpreta,
sino que traduce a decisiones de producto. Dicho en los propios términos del
cliente: *"el café es nuestro centro de atención y se lleva todos los
focos. El resto acompaña discretamente, sin perder un ápice de calidad"*, y
la misión declarada es ser *"honestos y transparentes, ofreciendo el mejor
producto disponible al mejor precio posible"*.

El posicionamiento gastronómico que se propone es, por tanto:

> **La comida en Geisha no compite con el café — lo acompaña al mismo nivel
> de exigencia.** No es un restaurante con café, ni una cafetería que además
> sirve comida de relleno: es una casa de café de especialidad cuya comida
> está diseñada, en cada referencia, para hacer brillar al café (pairing) o
> para dar al cliente que no es de café (el 25-35 femenino que busca
> experiencia) una razón de calidad equivalente para quedarse.

El nombre Geisha ya es, en sí mismo, una declaración de origen japonés que
hoy vive solo en la marca, no en el producto. La dirección de producto que
sigue en este documento (sección 3.5) añade, donde tiene sentido real, un
matiz pequeño y concreto de especia, ingrediente o técnica tradicional
japonesa sobre bases de producto de tendencia ya validadas por el dato de
venta — nunca una carta de fusión ni un giro hacia cocina japonesa completa.
Es, dentro de la misma lógica de "la comida acompaña sin competir", un
acento de identidad: el café sigue llevándose todos los focos, y la comida
gana un detalle reconocible y propio de Geisha sin dejar de acompañar
discretamente.

Esto encaja con la observación estratégica que el propio cliente ya hizo en
el briefing: de sus competidores directos en café (Nubra, The Fix, Davob),
solo The Fix trabaja comida en serio. **La comida es la ventaja competitiva
disponible, no una obligación operativa.** Las referencias de inspiración
que cita el cliente (Dalmore, Sampaka, Ambivium, The Edition) marcan el tono
— calidad premium sin ostentación — más que el producto en sí; se usan aquí
como referencia de actitud de marca, no como fuente de recetas.

### 2.2 Principios que rigen el desarrollo

1. **El café manda, la comida acompaña.** Ninguna referencia nueva se
   diseña para "competir" visual o conceptualmente con el café — se diseña
   para que el cliente que ya está tomando café se quede más tiempo, gaste
   más, o vuelva antes.
2. **Honestidad de producto.** Coherente con la misión declarada del
   cliente: mejor producto al mejor precio justo. Esto descarta ingeniería
   de menú artificiosa (referencias infladas de nombre pero vacías de
   producto) y favorece recetas simples, bien ejecutadas, con materia prima
   defendible.
3. **Cada decisión se ancla en dato real de venta**, no en intuición ni en
   tendencia de mercado genérica. Cuando se recomienda mantener, reforzar o
   sustituir una referencia, se dice explícitamente en qué dato real se
   basa esa recomendación.
4. **Producción de calidad previa + montaje en sala.** Principio de diseño
   operativo, no solo culinario: todo lo que exige cocción larga, horneado
   o elaboración compleja vive en la cocina de producción (horno
   convectivo, salamandra); la cocina de sala solo calienta, tuesta, monta
   y emplata. Ninguna referencia candidata de este documento depende de una
   cocción compleja en sala.
5. **La comida es la ventaja competitiva frente a la categoría de café
   especializado**, pero sin que Geisha deje de ser una casa de café — el
   crecimiento de comida no debe convertirse en una carta de restaurante.
6. **Dos públicos, dos lógicas de producto.** El hombre 35-45 (exigente,
   fiel si la calidad no falla) se gana con producto serio y consistente; la
   mujer 25-35 (busca experiencia/brunch, no es fiel al café en sí) se gana
   con presentación, formato compartible y una razón no-cafetera para
   volver (atención, ambiente, Instagram).

### 2.3 Arquitectura global de la propuesta

La propuesta organiza la oferta de comida en torno a cuatro papeles, no
en torno a categorías de carta tradicionales (desayuno/brunch/postres):

- **Acompañante del café** (pairing explícito): referencias pensadas para
  cerrar el hueco de conversión que hoy dejan filtro, espresso y frío
  especialidad — las bebidas que menos comida llevan.
- **Producto de plato** (comida con entidad propia): Benedict Eggs,
  sandwiches, el terreno de ticket medio alto y de mayor crecimiento real
  reciente.
- **Vitrina / grab&go**: bollería y repostería de autoservicio, el motor de
  volumen y de conversión de bajo compromiso, clave para el cliente nuevo
  del local (que hoy crece más en solo-bebida que en con-comida).
- **Ocasión / experiencia**: formatos de fin de semana, compartibles,
  dirigidos al segmento que busca experiencia más que producto.

---

## 3. Arquitectura de la oferta

### 3.1 Objetivo de la carta F&B

Subir el ticket medio de 9,75€ a 13-15€ **sin subir precios**, mediante dos
palancas que el propio dato de venta ya valida:

1. **Conversión**: recuperar tickets de comida sobre los ~29.500 tickets
   anuales de solo bebida — con foco prioritario en los clientes de filtro
   (33% llevan comida), espresso (28,3%) y frío especialidad (28,0%), los
   tres por debajo de la media del local (36,3%).
2. **Mix**: dentro de los tickets que ya llevan comida, desplazar el gasto
   hacia referencias de mayor valor percibido (platos, formatos
   compartibles, upsells) sin que eso signifique inflar precios de las
   referencias existentes.

### 3.2 Principios de desarrollo

- Se prioriza reforzar lo que el dato dice que ya funciona (filtro,
  Sandwich de pollo, Tosta jamón serrano, Banana Bread, Benedict Eggs)
  antes que introducir conceptos sin ninguna base de venta propia.
- Las referencias en caída sostenida (Tosta jamón ibérico, CheeseCake,
  Sandwich Kimchi, Bagel Salmón, Croissant mermelada, Tosta Mermelada
  Casera, Brownie, Bagel Verdura asada, Berry Bowl) no se retiran por
  decisión unilateral de este documento: se proponen **reformulaciones**
  que atacan la causa más probable (fatiga de producto, ejecución,
  percepción de valor) dejando la decisión final de retirar o no al
  cliente, con el dato de venta como argumento, no como sentencia.
- No se le quita protagonismo de carta al café con leche caliente (50% del
  volumen de bebida) al diseñar pairing — se diseña alrededor de él, no en
  su contra.
- Toda referencia nueva se diseña ya dividida en "qué se prepara abajo, en
  producción" y "qué se hace en sala, al momento" — ver el detalle en cada
  una de las 20 referencias candidatas.

### 3.3 Comportamiento de consumo real del cliente (lectura del dato)

- **Caída de conversión a comida:** 41% de tickets con comida en 2024, 37%
  en 2025, 34-36% en el local nuevo. La afluencia nueva del local (+31%
  tickets, +44% facturación frente a la madurez del local anterior) viene
  sobre todo de clientes de solo bebida (+36% frente a +23% con comida).
- **Brecha de ticket:** 14,39€ con comida frente a 7,11€ sin ella — la
  comida no es un complemento menor, es lo que duplica el ticket.
- **El café de filtro funciona como eje de marca** (+27% unidades, +31%
  ingreso, ya 15% del ingreso de bebida con 6% de las unidades) pero sus
  clientes llevan comida por debajo de la media (33%) — es la mayor
  oportunidad de conversión sin canibalizar nada.
- **Pairing ya existente, no inventado:** CheeseCake, Banana Bread y Carrot
  Cake son los platos que más acompañan al filtro; Croissant normal es el
  acompañante universal de casi todas las bebidas; Benedict Eggs y Sandwich
  de pollo se asocian a zumos/smoothies y americano (comida "de plato").
  Zumos/smoothies es, de toda la carta de bebida, la que más arrastra
  comida (66,2% de sus tickets) — el pairing de mayor conversión ya
  existente y menos explotado en carta.
- **Ganadores reales a reforzar:** Sandwich de pollo (+102% unidades/
  ingreso), Tosta jamón serrano (+50%/+54%), Banana Bread (+28% unidades),
  Benedict Eggs (+14% unidades/+16% ingreso).
- **Caídas reales a atender:** Tosta jamón ibérico (-39% unidades, la
  caída más fuerte de la carta de comida), CheeseCake (-26% ingreso,
  pese a seguir siendo top 5 en unidades), Sandwich Kimchi (-26%),
  Bagel Salmón (-23%), Croissant mermelada y Tosta Mermelada Casera
  (-19/-22% y -12/-15% respectivamente), Brownie (-15%), Bagel Verdura
  asada (-18%), Berry Bowl (-12,5% ingreso), Açai Bowl y Yogur Bowl
  (-15% y -10% unidades pese a seguir siendo top 10).

### 3.4 Arquitectura de la carta (qué papel juega cada bloque)

| Bloque | Papel en la carta | Referencias hoy top de este bloque |
|---|---|---|
| **Café (fuera de alcance de este documento, se respeta como está)** | Centro de la propuesta de marca | Escalones Geisha/Exclusivo/Leyenda + café con leche |
| **Vitrina / bollería y repostería** | Volumen, grab&go, acompañante universal, conversión de bajo compromiso | Croissant normal, CheeseCake, Carrot Cake, Banana Bread |
| **Tostas** | Puente entre vitrina y plato, ticket medio-bajo, pairing con café con leche | Tosta Aguacate, Tosta Jamón Serrano |
| **Bowls** | Captación del segmento experiencia/salud, formato visual | Açai Bowl, Yogur Bowl, Berry Bowl |
| **Plato (brunch/sandwich)** | Ticket medio alto, comida "de ocasión", pairing con zumos/americano | Benedict Eggs, Sandwich de pollo |
| **Compartible / ocasión (nuevo)** | Ticket medio alto, experiencia, fin de semana, hostess | — (hueco a cubrir, ver referencia candidata 12) |
| **Add-on / upsell (nuevo)** | Ticket medio sobre producto ya existente, sin nueva elaboración de base | — (hueco a cubrir, ver referencias candidatas 8, 13, 17) |

### 3.5 Desarrollo del producto — 20 referencias candidatas

**Criterio de priorización usado para llegar a estas 20** (a validar con
Andrea/Sergio y con el cliente, no es un hecho cerrado): se ha buscado (a)
anclar cada referencia en un dato de venta real — crecimiento a reforzar,
caída a atender, o pairing ya existente a formalizar —, (b) cubrir los dos
públicos objetivo declarados, (c) no proponer nada que exija una cocción
compleja en sala, y (d) dar variedad de función (conversión, ticket medio,
posicionamiento, recurrencia, captación) para que el recorte de 20 a 10 sea
una decisión informada del cliente, no una limitación nuestra. El SOW de
AR02 limita a 10 referencias finales; estas 20 son candidatas, no la
entrega final.

**Nota de identidad de producto (añadida 2026-10-22, a petición de
Andrea):** cada referencia de esta lista incorpora, a partir de hoy, un
criterio nuevo de identidad: son productos de tendencia (occidentales, ya
validados por el dato de venta real de Geisha) a los que se añade, donde
tiene sentido real, un matiz pequeño de especia, ingrediente o técnica
tradicional japonesa — coherente con el nombre Geisha. El matiz tiene que
sumar sabor e identidad, nunca ser decorativo, y nunca convertir la
referencia en un plato japonés completo ni en una reinterpretación de
fusión forzada: el cliente que ya pide un croissant o un Benedict Eggs tiene
que notar un detalle que solo existe en Geisha, no encontrarse con un menú
japonés. Se usan solo ingredientes/técnicas japonesas reales y ya habituales
en cafeterías de especialidad de tendencia — yuzu, matcha, miso, shichimi
togarashi, sésamo negro (goma), yuzu kosho, furikake, hojicha, kinako,
mirin/glaseado de soja, umeboshi, nori — no se inventan combinaciones
nuevas. Donde el matiz no aporta nada real a una referencia (porque ya
funciona bien sin él, o porque forzarlo sonaría gratuito), se dice
explícitamente y se deja la referencia igual que en el borrador original.
Esta capa no cambia qué problema de negocio resuelve cada referencia (eso
sigue anclado en el dato de venta, igual que antes) — cambia cómo sabe y se
diferencia.

---

**1. Mini bollería de acompañamiento ("Mini bite" de temporada)**
- *Por qué:* el croissant normal es el acompañante universal (13% de las
  unidades totales) pero implica un compromiso de plato completo; los
  clientes de espresso, frío especialidad y filtro llevan comida por
  debajo de la media (28-33% frente a 36,3%) — necesitan una entrada de
  comida de compromiso más bajo.
- *Función:* Conversión / captación de ticket pequeño.
- *Producción:* horneado en lote en producción (horno convectivo),
  enfriado y porcionado abajo; en sala solo emplatado, con calentado
  opcional en grill tostador.
- *Matiz Geisha (identidad):* un topping ligero de kinako (harina de soja
  tostada, sabor dulce a fruto seco) o un crumble de sésamo negro (goma)
  sobre la pieza — matiz pequeño, coherente con un formato de compromiso
  bajo, que no cambia el producto base ni el proceso. *Nota: añade un
  ingrediente nuevo a la lista de compra sin escandallo propio hoy —
  revisar coste con `culinary-development` junto al resto de huecos de
  food cost.*

**2. "Dupla Filtro + Repostería" (pairing formalizado en carta)**
- *Por qué:* el propio dato de pairing señala CheeseCake, Banana Bread y
  Carrot Cake como los platos que más acompañan al filtro, pero el filtro
  solo lleva comida el 33% de las veces — por debajo de la media. Hoy es
  un pairing real pero no comunicado.
- *Función:* Conversión + ticket medio (filtro ya es la bebida de mayor
  precio, 9,65€ de media).
- *Producción:* repostería ya horneada/cortada abajo; en sala, montaje
  conjunto en el momento de servir el filtro.
- *Matiz Geisha (identidad):* se deja sin matiz propio. Es la
  formalización en carta de un pairing de productos que ya tienen su
  propio matiz japonés en las referencias 14 (CheeseCake), 8 (Banana
  Bread) y 17 (Carrot Cake) — añadir algo aquí solo repetiría el mensaje
  sin sumar identidad nueva.

**3. Set "Espresso & Croissant Clásico"**
- *Por qué:* el espresso es la bebida con menor conversión a comida de
  toda la carta (28,3%); el croissant normal ya es su acompañante natural
  más frecuente. Formaliza un patrón que ya ocurre, bajando la fricción de
  decisión.
- *Función:* Conversión.
- *Producción:* croissant ya horneado abajo; montaje/calentado en grill
  tostador en sala.
- *Matiz Geisha (identidad):* se deja sin matiz, de forma explícita. El
  valor de esta pieza es precisamente formalizar un patrón de consumo ya
  clásico y sin fricción (espresso + croissant tal cual). Añadir un acento
  japonés aquí sonaría gratuito y rompería la lógica de "clásico" que es la
  razón de ser de la referencia.

**4. "Mermelada Artesana de Temporada" (sustituye Tosta Mermelada Casera y
absorbe el hueco que deja Croissant mermelada)**
- *Por qué:* ambas referencias de mermelada caen con fuerza (-15,1% y
  -11,6% en unidades/ingreso la tosta; -22,2%/-19,3% el croissant) en dos
  periodos seguidos — señal de fatiga de producto, no de falta de interés
  por el formato dulce.
- *Función:* Posicionamiento (sustituye una referencia en declive por una
  de mayor valor percibido) + ticket medio.
- *Producción:* mermelada elaborada en producción (cocción larga); pan
  tostado al momento en grill en sala.
- *Matiz Geisha (identidad):* se construye directamente sobre yuzu — una
  "Mermelada/Curd de Yuzu de Temporada" sustituye la mermelada genérica por
  un cítrico distinto al limón/naranja habitual, con identidad propia y
  mayor valor percibido, justo lo que necesita una referencia que cae por
  fatiga de producto. *Nota de coste: el yuzu es un cítrico de importación,
  más caro que la fruta de mermelada actual, sin escandallo propio hoy;
  esto ya cabe dentro de la cláusula de 3.6 que permite "precio levemente
  superior si el cambio de producto lo justifica" — no se modifica la
  estrategia de precio, solo se confirma que este es el caso que la
  justifica.*

**5. "Tosta Serrano Premium" (extensión de Tosta Jamón Serrano)**
- *Por qué:* es la tosta con mayor crecimiento de toda la carta (+49,9%
  unidades / +53,8% ingreso) — potenciarla con un extra (huevo poché,
  tomate semiseco) sube el ticket sobre un ganador real sin tocar la base.
- *Función:* Ticket medio (upsell sobre un ganador validado).
- *Producción:* huevo poché/elementos preparados abajo; montaje y tostado
  del pan en grill en sala. *(Pendiente validar con culinary-development
  si el huevo poché es viable en el flujo de producción-sala — ver su
  análisis técnico del 2026-10-22.)*
- *Matiz Geisha (identidad):* un toque ligero de shichimi togarashi
  espolvoreado sobre el huevo al servir — picante/sésamo suave que realza
  el jamón serrano sin tapar su sabor. Es solo un terminado en sala, así
  que no cambia nada del hueco técnico del huevo poché ya señalado por
  `culinary-development`: sigue pendiente de validación exactamente igual,
  con o sin este matiz.

**6. "Tosta Ibérico Reinventada" (reformulación de Tosta Jamón Ibérico)**
- *Por qué:* cae -38,9% en unidades, la caída más fuerte de toda la carta
  de comida — no se recomienda mantenerla igual, pero tampoco retirarla sin
  más: sigue siendo relevante para el público masculino 35-45 exigente. Se
  reformula en formato/foco de calidad, no en volumen.
- *Función:* Posicionamiento (coherencia con "mejor producto posible"),
  dirigida al segmento fiel.
- *Producción:* montaje en frío en sala (mesa refrigerada), sin cocción.
  `culinary-development` confirma que, técnicamente, esta referencia es
  viable sin ajuste — el hueco real es de food cost del ibérico, no de
  proceso.
- *Matiz Geisha (identidad):* un acento opcional de yuzu kosho (pasta de
  cítrico y chile), servido aparte en pequeña cantidad para que el cliente
  decida si lo añade — mantiene intacta la pureza del ibérico (clave para
  un segmento que valora "el mejor producto posible" sin que se tape) y
  aporta identidad sin mezclarse en el producto base. *Nota de coste: el
  yuzu kosho es un ingrediente adicional sin escandallo — se suma al mismo
  hueco de food cost ya señalado para esta referencia (precio/proveedor
  actual del jamón ibérico); revisar ambos a la vez con
  `culinary-development`.*

**7. "Sandwich de Pollo Deluxe" (extensión del Sandwich de Pollo)**
- *Por qué:* es el crecimiento más fuerte de toda la carta de comida
  (+101,6% unidades / +101,9% ingreso en dos periodos) — mantener el
  original como entrada de gama y sumar una versión ampliada capta ticket
  medio sobre el mayor momentum real disponible.
- *Función:* Ticket medio + tractor de tráfico.
- *Producción:* pollo cocinado/marinado en horno convectivo abajo; montaje
  y tostado del pan en grill tostador en sala.
- *Matiz Geisha (identidad):* el pollo se termina con un glaseado de mirin
  y soja en el horno convectivo de producción — combina de forma directa y
  natural con el pollo (técnica real y habitual, no una invención), y es la
  referencia donde este matiz tiene más sentido de toda la lista: es el
  mayor crecimiento real de la carta, así que reforzarlo con una identidad
  propia de sabor —no solo de tamaño ("Deluxe")— da una razón más fuerte
  para que siga siendo tractor de tráfico. No cambia el proceso ya
  validado (horno abajo, montaje/tostado en grill en sala): el glaseado se
  aplica en el mismo paso de cocción.

**8. "Banana Bread con topping" (mantequilla de frutos secos o mascarpone)**
- *Por qué:* Banana Bread crece +27,7% en unidades, el mayor crecimiento
  de la repostería de vitrina — un topping de pago opcional captura ticket
  medio adicional sin canibalizar el volumen base.
- *Función:* Ticket medio (upsell de bajo riesgo).
- *Producción:* banana bread ya horneado abajo; topping añadido en sala
  sin cocción.
- *Matiz Geisha (identidad):* se sustituye la opción genérica de
  "mantequilla de frutos secos" por un topping de kinako (harina de soja
  tostada) — alternativa real al praliné clásico, con sabor a fruto seco
  tostado que combina de forma natural con el plátano. El mascarpone se
  mantiene como segunda opción sin matiz, para quien prefiera lo clásico.

**9. "Benedict Eggs" — variante (ahumado o verde/espinaca)**
- *Por qué:* es el plato de mayor crecimiento entre la comida de plato
  (+13,9% unidades / +15,9% ingreso) y se asocia ya a zumos/smoothies, la
  bebida que más arrastra comida de toda la carta (66,2%). Una variante
  rotativa da una segunda razón de visita sin canibalizar el original.
- *Función:* Ticket medio + recurrencia.
- *Producción:* bases (salmón curado, espinaca salteada) preparadas y
  porcionadas abajo; montaje final (huevo poché + salsa) — ver nota de
  `culinary-development`, que corrige un error de equipamiento del
  borrador original (la salamandra es equipo de producción, no de sala) y
  propone dos soluciones: montaje completo en producción, o adaptación con
  el equipamiento real de sala (microondas/cazo de agua caliente en la
  placa de inducción). *Pendiente de cerrar cuál de las dos antes de
  estandarizar.*
- *Matiz Geisha (identidad):* un crumble ligero de furikake (sésamo, alga,
  sal) sobre el huevo/aguacate en el montaje — aporta un acento umami que
  combina de forma natural con huevo y aguacate, sin tapar la salsa ni el
  salmón de la variante ahumada. Es solo un terminado seco añadido en el
  montaje final, así que no afecta a ninguno de los huecos técnicos ya
  señalados (huevo poché, estabilidad de la salsa): siguen abiertos
  exactamente igual, con o sin este matiz.

**10. "Açai Bowl de Temporada" (rotación sobre el Açai Bowl actual)**
- *Por qué:* sigue siendo el 2º producto más vendido en unidades (8,1%) y
  top 3 en ingreso, pero cae -15,3% en unidades / -12,3% en ingreso —
  síntoma de fatiga de producto, no de pérdida de interés en el formato.
- *Función:* Tractor de tráfico + captación (segmento mujer 25-35).
- *Producción:* base y toppings cortados/porcionados abajo; montaje final
  en sala.
- *Matiz Geisha (identidad):* un topping rotativo de sésamo negro (goma)
  en crumble o praliné — textura tostada distinta a los toppings de bowl
  habituales (granola, coco), coherente con la propia lógica de "rotación
  de temporada" que ya tiene esta referencia.

**11. "Bowl de Temporada" (rotación unificada de Yogur Bowl y Berry Bowl)**
- *Por qué:* Yogur Bowl cae -10,2% en unidades y Berry Bowl -12,5% en
  ingreso — misma lógica de fatiga de producto que el Açai Bowl. Una
  arquitectura de "bowl base + rotación mensual" reduce la sensación de
  carta estática sin multiplicar referencias fijas.
- *Función:* Recurrencia + conversión (formato ligero, de bajo compromiso).
- *Producción:* toppings preparados abajo; montaje en sala.
- *Matiz Geisha (identidad):* una de las variantes de la rotación mensual
  puede incorporar una crema de matcha, o una granola de hojicha —el
  matcha funciona bien en formato bowl/cremoso (con moderación, no como
  sabor dominante) y el hojicha da una opción más tostada y menos amarga
  para quien no busque tanto matcha. *Nota de proceso: a diferencia del
  montaje en frío sin preparación que `culinary-development` ya validó
  para esta referencia, mezclar matcha u hojicha en polvo con la base de
  crema/yogur es un paso breve de preparación en producción, no solo
  montaje en sala — ajuste menor a confirmar con `culinary-development`,
  no cambia la viabilidad general de la referencia.*

**12. "Geisha Board" (tabla compartible, fin de semana)**
- *Por qué:* en el local nuevo crece más fuerte el cliente sin comida
  (+36% frente a +23% con comida) y el fin de semana (+39% tickets) —
  justo cuando hay hostess disponible. Un formato de mesa compartida da un
  motivo de alto ticket al momento de mayor afluencia nueva.
- *Función:* Ticket medio (mayor precio unitario de la carta propuesta) +
  captación (experiencia para el segmento mujer 25-35).
- *Producción:* componentes (mini bakes, fruta, repostería en porción,
  algo salado) preparados abajo; montaje final en sala, sin cocción
  compleja. `culinary-development` señala que el proceso es viable, pero
  que el food cost es la duda real — en particular porque "algo salado"
  no está definido todavía.
- *Matiz Geisha (identidad):* se propone que el componente salado
  pendiente de definir incorpore un matiz japonés concreto — por ejemplo,
  una galleta salada con sésamo negro, o un contraste de umeboshi con
  queso — y que el componente dulce incluya un toque de caramelo de miso,
  de tendencia actual en repostería y con la profundidad salada que pide
  un formato de tabla compartida. *Nota: esto no resuelve el hueco técnico
  ya señalado por `culinary-development` (qué es exactamente "algo salado"
  y su coste) — lo concreta con un criterio de identidad, pero sigue
  pendiente de validación de viabilidad y food cost antes de cerrarlo.*

**13. "Zumo/Smoothie de Temporada Premium" (con pairing explícito a
Benedict Eggs / Tosta Aguacate)**
- *Por qué:* zumos y smoothies son, de toda la carta de bebida, la que más
  arrastra comida (66,2% de sus tickets) y ya se asocian de forma natural
  a Benedict Eggs y Tosta Aguacate — formalizar el pairing con una versión
  de temporada a precio algo superior es ticket medio sobre un
  comportamiento que ya existe.
- *Función:* Ticket medio + conversión.
- *Producción:* fruta/ingredientes cortados y porcionados abajo;
  elaboración final en licuadora en sala (equipamiento ya disponible).
- *Matiz Geisha (identidad):* la versión de temporada puede construirse
  sobre yuzu — un cítrico distinto al de la fruta base habitual de la
  carta de zumos, que además refuerza el pairing ya existente con Tosta
  Aguacate y Benedict Eggs (referencias que ya llevan su propio matiz
  japonés, ver 9 y 15). Proceso igual al ya validado por
  `culinary-development` (fruta cortada abajo, elaboración en licuadora en
  sala).

**14. "CheeseCake de Temporada" (rotación de sabor)**
- *Por qué:* sigue siendo el plato que más acompaña al filtro (dato de
  pairing) y top 5 en unidades totales — no se recomienda retirarlo, pero
  la caída de dos periodos seguidos (-25,9% unidades / -26,4% ingreso) pide
  refresco. La rotación mantiene el rol de pairing sin añadir complejidad
  de producción.
- *Función:* Conversión (pairing con filtro) + recurrencia.
- *Producción:* horneado/montado abajo (ya existente, cambia sabor/
  decoración); porcionado y emplatado en sala.
- *Matiz Geisha (identidad):* entre los sabores de la rotación se incluye
  una variante de matcha y una de yuzu (curd de yuzu sobre la base de
  cheesecake) — ambas son combinaciones ya habituales en repostería de
  tendencia y encajan directamente con la lógica de "refresco de sabor sin
  más complejidad de producción" que ya pedía esta referencia.

**15. "Reformulación Bagel Salmón"**
- *Por qué:* cae -23,4% en unidades en dos periodos seguidos; el formato
  bagel en general pierde tracción (Bagel Verdura asada también cae
  -18,2%) frente a tostas y sandwiches que crecen. **No se recomienda
  retirarla solo con este dato** — puede ser un problema de ejecución o de
  percepción de precio, no de formato; se propone revisar calidad de
  salmón/aderezo antes de decidir retirada. Decisión a validar con el
  cliente.
- *Función:* Posicionamiento / a determinar tras validación.
- *Producción:* salmón curado/porcionado abajo; montaje en frío en sala,
  bagel tostado en grill tostador. `culinary-development` confirma que el
  proceso es correcto (curado es técnica en frío, no necesita fogón).
- *Matiz Geisha (identidad):* un crumble de nori o un toque de furikake
  sobre el salmón — combinación de sabor que ya existe de forma natural
  (salmón y alga combinan bien, sin que esto sea un giro hacia sushi o
  fusión), y da una razón de sabor diferenciado si la causa real de la
  caída es percepción de "bagel igual a cualquier otro", no solo precio o
  ejecución. No cambia el proceso ya validado.

**16. Nueva referencia salada ligera (sustituye Sandwich Kimchi y Queso)**
- *Por qué:* el Sandwich Kimchi tiene la peor evolución de la carta salada
  junto al Bagel Salmón (-26% unidades / -24,1% ingreso) — un sabor
  probablemente demasiado nicho para un cliente 60-70% turista/local
  "dispuesto a probar" pero no necesariamente buscando fermentados. Se
  propone cubrir el mismo hueco de "sandwich salado de formato medio" con
  una ejecución de atractivo más transversal.
- *Función:* Ticket medio / conversión.
- *Producción:* proteína cocinada en horno convectivo abajo; montaje y
  tostado en grill en sala. La proteína final todavía no está decidida —
  `culinary-development` señala que el proceso general (horno + grill) es
  viable, pero no puede confirmar el detalle fino sin ese dato.
- *Matiz Geisha (identidad):* sea cual sea la proteína final, se propone
  que el terminado incorpore un glaseado de miso o un toque de shichimi
  togarashi — ambos dan profundidad salada o un picante ligero sin
  convertir el sandwich en una receta japonesa. *Esto queda condicionado a
  que, una vez elegida la proteína, `culinary-development` confirme que el
  matiz es compatible con el proceso de cocción en horno convectivo.*

**17. "Carrot Cake con topping de queso crema" (upsell)**
- *Por qué:* Carrot Cake es la única referencia top 10 de repostería de
  vitrina que no cae en el último periodo (+1,3% unidades) y es uno de los
  acompañantes principales del café con leche caliente, la bebida de mayor
  volumen (50% del total). Reforzarlo con un extra opcional es ticket
  medio de bajo riesgo sobre la base más estable de la carta.
- *Función:* Ticket medio (upsell de bajo riesgo).
- *Producción:* carrot cake horneado abajo (ya existente); topping
  añadido en sala sin cocción.
- *Matiz Geisha (identidad):* el topping de queso crema incorpora un
  crumble de sésamo negro — aporta un contraste de textura tostada sobre
  la untuosidad del queso crema, sin cambiar el carrot cake base (la
  referencia más estable de la carta, según el propio dato de venta).

**18. "Brownie Reforzado" (con helado o salsa)**
- *Por qué:* cae de forma sostenida (-14,6% unidades / -14,1% ingreso) pero
  mantiene reconocimiento de producto; reforzarlo como "postre" (en lugar
  de competir como acompañante de café) abre una ocasión de consumo
  distinta (tarde, fin de semana) en vez de competir con el resto de la
  vitrina.
- *Función:* Posicionamiento (nueva ocasión de consumo) + ticket medio.
- *Producción:* brownie horneado abajo (ya existente); montaje con helado
  (congelador vertical en sala, equipo ya confirmado en la lista de sala)
  al momento. `culinary-development` pide confirmar espacio de congelador
  asignable sin desplazar lo que ya se guarda ahí.
- *Matiz Geisha (identidad):* se concreta la "salsa" genérica del borrador
  original como un caramelo de miso — de toda la lista de ingredientes de
  identidad, es la combinación de tendencia más directa con chocolate
  (profundidad salada sobre dulce, ya habitual en repostería de
  especialidad). *Nota técnica importante: hacer caramelo desde cero
  requiere normalmente fuego directo (fogón), y `culinary-development` ya
  señaló que no hay ningún fogón documentado en la cocina de producción.
  Este matiz, tal y como está planteado, necesita que
  `culinary-development` confirme si es viable elaborarlo en horno
  convectivo/microondas controlado, o si hace falta comprarlo ya elaborado
  a un proveedor, antes de estandarizarlo — no lo resuelvo yo.*

**19. Grab&go "Mini Viennoiserie de Vitrina" (formato individual económico)**
- *Por qué:* en los primeros días del local nuevo crece más el cliente sin
  comida (+36%) que con comida (+23% frente a la madurez) — ese flujo
  nuevo necesita una opción de comida de muy baja fricción antes de que se
  consolide el hábito de "aquí solo se toma café".
- *Función:* Captación + conversión (primera puerta de entrada a comida
  para el cliente nuevo del local).
- *Producción:* horneado en lotes abajo; expuesto en vitrina de sala, sin
  montaje adicional. `culinary-development` la señala como la más simple
  de las 20.
- *Matiz Geisha (identidad):* se deja sin matiz, de forma explícita. Es,
  por diseño, la opción más económica y de menor fricción de las 20,
  pensada para el cliente nuevo del local que todavía no tiene el hábito
  de pedir comida. Añadir un ingrediente de identidad —aunque sea
  pequeño— subiría el coste y la complejidad de compra de una pieza cuya
  única función es ser la puerta de entrada más simple y barata posible:
  iría en contra de su propio objetivo.

**20. "Ritual Semanal" — Tartaleta de Autor de edición limitada (producto
concreto, definido hoy a petición de Andrea)**
- *Por qué:* el público masculino 35-45 es, según el propio briefing,
  "exigente y fiel si la calidad no falla" — una pieza rotativa de alta
  ejecución y disponibilidad limitada da una razón de visita recurrente a
  ese público ya fiel, sin inflar el número de referencias permanentes de
  la carta. (Mismo razonamiento del borrador original; lo que faltaba era
  el producto.)
- *Producto concreto:* una tartaleta individual de base clásica (masa
  quebrada horneada en el horno convectivo de producción, técnica ya
  dominada hoy con el resto de la repostería de vitrina), con un relleno
  distinto cada semana — siempre construido sobre **un único matiz
  japonés de identidad**, nunca mezclando varios en la misma pieza, para
  que cada semana tenga una historia de sabor clara y reconocible. Cuatro
  fórmulas de relleno para rotar (no 52 recetas distintas al año, un
  repertorio que se repite con variaciones de temporada):
  1. Curd de yuzu con merengue tostado.
  2. Crema diplomática de matcha.
  3. Ganache de chocolate con caramelo de miso (mismo matiz que la
     referencia 18 — comparte el mismo hueco técnico de cómo elaborar el
     caramelo sin fogón, ver nota más abajo).
  4. Crema de hojicha con un acabado de sésamo negro en crumble.
- *Formato de venta:* lote limitado (tamaño a definir con el cliente y
  `culinary-development` según capacidad real de horno — ver el riesgo de
  saturación ya señalado en la validación técnica, sección 4.2), venta en
  sala hasta agotar stock, comunicado como "edición de la semana" con el
  nombre del matiz (p. ej. "Ritual Semanal: Yuzu"), no con un nombre
  genérico.
- *Función:* Recurrencia (dirigida al segmento fiel 35-45) + ancla de
  identidad de marca — es la pieza donde la capa japonesa de Geisha se
  expresa con mayor ejecución e intención, frente al resto de la carta
  donde el matiz es un acento discreto.
- *Producción:* masa quebrada y horneado de base en horno convectivo
  abajo; relleno preparado en producción (curd/crema/ganache, según la
  fórmula de la semana); montaje y acabado (merengue tostado, crumble)
  también en producción, porque es una pieza de mayor ejecución, no de
  montaje rápido en sala — coherente con cómo `culinary-development`
  resolvió la referencia 9 (montaje completo abajo cuando la elaboración
  es compleja).
- *Nota técnica obligatoria:* esta referencia es completamente nueva (no
  existía producto concreto hasta hoy, `culinary-development` lo señaló
  explícitamente como hueco en su validación del 2026-10-22), así que **no
  tiene todavía ninguna validación técnica** — a diferencia de las otras
  19, que ya pasaron por esa revisión. Antes de presentarla al cliente
  como candidata firme hay que pasarla por el mismo ejercicio de
  viabilidad/espacio/equipamiento y de food cost que el resto, incluyendo
  el mismo punto ya señalado para la referencia 18 (elaborar caramelo de
  miso sin fogón documentado) y la capacidad real del horno convectivo
  para un lote semanal adicional sobre el resto de producción diaria
  (riesgo de saturación ya advertido en la validación técnica).

---

**Resumen de la capa de identidad añadida (2026-10-22):** de las 20
referencias, 16 incorporan un matiz japonés concreto (1, 4, 5, 6, 7, 8, 9,
10, 11, 12, 13, 14, 15, 16, 17 y 18), y la referencia 20 pasa de no tener
producto a construirse directamente sobre esta misma identidad. Se deja
explícitamente sin matiz: la 2 (ya cubierto por las referencias que
agrupa), la 3 (su valor es precisamente ser clásica y sin fricción) y la 19
(su valor es ser la opción más barata y simple de toda la lista). Esta capa
es una capa de sabor e identidad sobre la misma arquitectura y los mismos
datos de venta ya descritos en 3.1-3.4 — no cambia qué referencia resuelve
qué problema de negocio, solo cómo sabe y se diferencia. Igual que el resto
del documento, ningún matiz debe tratarse como cerrado hasta que
`culinary-development` confirme viabilidad de los puntos señalados
explícitamente arriba — sobre todo: el caramelo de miso (referencias 18 y
20), el paso de preparación añadido en la 11, y la validación completa, de
cero, de la referencia 20.

---

### 3.6 Estrategia de precio

El objetivo de negocio es explícito: ticket medio de 10€ a 13-15€ **sin
subir precios**. Esto fija el criterio de precio para las 20 referencias
candidatas:

- **No se tocan los precios de las referencias existentes.** El movimiento
  de ticket viene del mix, no del pricing.
- Las referencias de **conversión** (1, 2, 3, 11, 16, 19) se posicionan en
  el rango de entrada más bajo posible — su función es bajar la fricción
  de decisión para el cliente de solo bebida, no maximizar margen por
  unidad.
- Las referencias de **ticket medio/upsell** (5, 7, 8, 9, 13, 17) se
  posicionan como extras de precio pequeño sobre una base ya existente —
  suman al ticket sin que el cliente perciba una subida de precio del
  plato base.
- Las referencias de **ocasión/experiencia** (12) se posicionan en el
  escalón más alto de la carta de comida, coherente con el perfil de la
  tabla compartida y el momento (fin de semana, hostess).
- Las reformulaciones de referencias en caída (4, 6, 10, 14, 15, 18) se
  proponen a precio similar al actual o levemente superior si el cambio de
  producto lo justifica — su objetivo es recuperar volumen, no capturar
  margen adicional.

**Nota sobre la capa de identidad japonesa añadida el 2026-10-22:** no se
modifica este criterio de precio. Los matices que añaden un ingrediente con
coste propio (yuzu en 4, 13 y 14; yuzu kosho en 6; miso en 12, 18 y 20;
kinako/sésamo negro en 1, 8, 10 y 17) caen, en su mayoría, dentro de
referencias que ya estaban clasificadas como "reformulación" o "ticket
medio/upsell" — es decir, la cláusula de precio "levemente superior si el
cambio de producto lo justifica" ya cubre este caso sin necesidad de
reescribir nada aquí. Lo que sigue pendiente, igual que antes, es el food
cost real de cada ingrediente nuevo: no hay escandallo ni proveedor
confirmado de yuzu, matcha, miso, hojicha, kinako, sésamo negro, furikake,
nori, yuzu kosho, shichimi togarashi ni mirin, así que ningún precio de
este documento (con o sin matiz japonés) debe tratarse como definitivo
hasta que `culinary-development` calcule food cost real.

**Importante:** estos rangos son posicionamiento relativo, no precios
finales. No hay escandallos actualizados (los últimos son de hace 6 años),
así que ningún precio de este documento debe tratarse como definitivo hasta
que `culinary-development` calcule food cost real — o se confirme con la
propiedad si existe un dato de coste más reciente que el declarado.

---

## Preguntas abiertas / datos a confirmar antes de cerrar estas secciones

1. **Brand Kit y Brand Book del cliente no se han leído en profundidad**
   (son PDFs grandes, ~35-37MB, en Drive, no incluidos en este repo). El
   posicionamiento gastronómico de la sección 2 se ha construido sobre la
   descripción textual del briefing, no sobre el documento de marca
   completo — confirmar que no hay matices de tono/identidad en el Brand
   Book que contradigan algo de este borrador antes de darlo por cerrado.
2. **`menu español (2).pdf` (carta actual) y
   `Geisha_Analisis_Productos_2021-2026_v5.xlsx`** tampoco se han revisado
   en detalle — el xlsx probablemente trae menu engineering y costes de
   materia prima más finos que el resumen ejecutivo de ventas usado aquí.
   Revisarlo puede afinar o corregir alguna de las 20 referencias
   propuestas, especialmente las reformulaciones (4, 6, 10, 14, 15, 18).
3. **Escandallos/food cost actual:** el cliente respondió "ya conocidas.
   NA" de forma ambigua. Confirmar con Juan si existe food cost reciente
   o si se trabaja sin él — condiciona directamente la estrategia de
   precio final y el trabajo de `culinary-development`.
4. **Viabilidad técnica de las referencias marcadas explícitamente en este
   documento** (5, 6, 9 — huevo poché, ibérico de calidad, salsa
   holandesa en sala) necesita validación de `culinary-development` antes
   de presentarlas como candidatas firmes al cliente. (Actualización: esa
   validación ya se hizo el 2026-10-22; quedan huecos puntuales detallados
   arriba en cada referencia y en los puntos 9-11 de esta lista.)
5. **Criterio de recorte de 20 a 10**: este documento no decide cuáles de
   las 20 son las 10 finales — eso corresponde al cliente, con
   Andrea/Sergio mediando. Conviene acordar con Andrea si se presenta la
   lista completa de 20 al cliente para que elija, o si TBNB preselecciona
   un subconjunto recomendado antes de la reunión.
6. **Referencias 6 y 15** (Tosta Ibérico, Bagel Salmón) se proponen como
   reformulación, no como retirada — confirmar con el cliente si hay
   contexto adicional (motivo real de la caída: precio, ejecución,
   proveedor) que cambie esa recomendación.
7. **Sección "Product Strategy" (punto 4 de la plantilla)** pedirá
   clasificar estas referencias por territorio/familia de producto de
   forma más formal — pendiente de construir en la siguiente pasada, una
   vez el cliente haya recortado de 20 a 10.
8. **Confirmar si el equipamiento de cocina sigue vigente tras la mudanza
   de octubre** (fotos/vídeos originales son de julio 2026, antes del
   cambio de local) — Andrea ya lo dio por vigente con los matices del
   grill tostador y la inducción pequeña, pero no hay vídeo/foto del local
   nuevo que lo confirme visualmente; si el equipamiento real difiere, hay
   que revisar la columna de producción de cada referencia.
9. **Capa de identidad japonesa (añadida 2026-10-22, a petición de
   Andrea):** no hay proveedor ni escandallo hoy de ninguno de los
   ingredientes usados en los matices (yuzu, matcha, miso, hojicha,
   kinako, sésamo negro, furikake, nori, yuzu kosho, shichimi togarashi,
   mirin) — antes de dar por cerrado cualquier matiz concreto hay que
   confirmar disponibilidad real de proveedor y coste.
10. **Caramelo de miso (referencias 18 y 20):** necesita que
    `culinary-development` confirme cómo se elabora un caramelo sin fogón
    documentado en producción (horno convectivo, comprarlo ya elaborado a
    un proveedor, u otra técnica) antes de estandarizarlo en ninguna de
    las dos referencias.
11. **Referencia 20 ("Ritual Semanal"):** ahora tiene producto concreto,
    pero no ha pasado todavía por ninguna validación técnica de
    `culinary-development` (viabilidad, espacio, food cost, capacidad real
    de horno para un lote semanal adicional) — necesita una pasada
    completa, igual que las otras 19, antes de presentarla como candidata
    firme al cliente.
12. **Nivel de identidad japonesa deseado por el cliente:** este borrador
    aplica un criterio de "matiz pequeño y discreto" en la mayoría de
    referencias y uno "de autor, con más protagonismo" solo en la
    referencia 20 — conviene confirmar con Juan si ese reparto es el tono
    que tiene en mente, o si prefiere un nivel distinto (más discreto en
    todas, o más marcado en alguna otra), antes de llevarlo a diseño de
    carta.

# Desarrollo Concepto Gastronómico — Geisha Specialty Coffee

**Servicio:** AR02 — Desarrollo gastronómico (BAR Method, fase Architecture)
**Estado del documento:** COMPLETO — las 7 secciones de la plantilla AR02
(Resumen Ejecutivo, Estrategia Gastronómica, Arquitectura de la oferta,
Product Strategy, Estrategia Económica, Recomendaciones para Diseño de
Carta, Siguientes pasos) están redactadas. Pendiente de revisión de
Andrea/Sergio antes de cualquier envío al cliente — ver la lista de
preguntas abiertas al final del documento, que no se cierra con esta
pasada.
**Autoría:** `chef-ejecutivo` (TBNB), sobre dato real de cliente y sobre la
validación técnica de `culinary-development` (`culinary-development-validacion-tecnica.md`,
2026-10-22, incluida su ampliación sobre la capa de identidad japonesa y la
referencia 20). Pendiente de revisión por Andrea/Sergio antes de cualquier
envío al cliente.
**Fecha:** 2026-10-15. **Última actualización: 2026-10-22** — se añaden las
secciones 4 a 7 (Product Strategy, Estrategia Económica, Recomendaciones
para Diseño de Carta, Siguientes pasos), construidas sobre las 20
referencias ya validadas técnicamente (incluida la capa de identidad
japonesa y el producto definitivo de la referencia 20). Las secciones 1-3
no se modifican de fondo en esta pasada.

---

## 1. Resumen Ejecutivo

Geisha Specialty Coffee tiene un problema de negocio concreto: **el café
funciona, la comida se está quedando atrás.** El ticket medio sube cada año
(7,20€ en 2022 a 9,75€ ahora) tirado casi solo por el café — sobre todo por
el filtro, que crece +27% en unidades y ya es el 15% del ingreso de bebida
con solo el 6% de las unidades —, mientras la comida cae (-7% en unidades,
-5% en euros en el último año) y el % de tickets con comida baja de 41% a
37% (34-36% en el local nuevo). De los ~47.800 tickets anuales, unos
**29.500 son hoy de solo bebida**: ese es el público objetivo de este
desarrollo.

La palanca ya está validada por el propio dato: un ticket con comida
factura 14,39€ frente a 7,11€ sin ella. El objetivo del cliente — subir el
ticket medio de 10€ a 13-15€ **sin tocar precios** — se resuelve con mix de
producto y conversión a comida, no con pricing.

Este documento no inventa un posicionamiento nuevo: parte del que Geisha ya
tiene (el café es el centro, la comida acompaña sin perder calidad) y lo
traduce en **20 referencias candidatas**, cada una anclada en un dato real
de venta y validada técnicamente por `culinary-development`, incluida una
capa de identidad japonesa (matices de especia o técnica tradicional,
coherentes con el nombre Geisha) que hoy toca a 16 de las 20. El cliente y
Andrea/Sergio seleccionarán de estas 20 las 10 que entran en el alcance de
AR02. Las secciones 4 a 7 organizan estas referencias en territorios de
producto, las sitúan frente al mercado con el dato disponible, las traducen
en recomendaciones de diseño de carta y dejan un plan de siguientes pasos
antes de pasar a RU06.

**Aviso de carácter consultivo:** esta propuesta es dirección estratégica y
de producto, no garantía de resultado comercial. La viabilidad técnica ya
está validada; el food cost depende de escandallos desactualizados (6 años)
y de ingredientes nuevos sin proveedor ni escandallo todavía. Ningún precio
ni referencia debe darse por cerrado hasta resolver esos huecos.

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
- *Matiz Geisha (identidad) — dos opciones, a elegir una o mantener ambas en
  rotación:*
  1. **Kinako** (harina de soja tostada) — topping fino en polvo, dulce,
     sabor a fruto seco tostado; combina mejor sobre una base neutra o
     mantecosa.
  2. **Sésamo negro (goma)** — crumble con más textura y un punto
     tostado/amargo; combina mejor sobre una base con algo de dulzor propio
     (p. ej. un toque de miel o mantequilla).

  Matiz pequeño en los dos casos, coherente con un formato de compromiso
  bajo, que no cambia el producto base ni el proceso. *Nota: cualquiera de
  las dos añade un ingrediente nuevo a la lista de compra sin escandallo
  propio hoy — revisar coste con `culinary-development` junto al resto de
  huecos de food cost.*

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
  tostador en sala. `culinary-development` recomienda probar en RU06 si
  conviene regenerar el croissant ya caliente desde producción y solo
  tostar el corte en el grill, en vez de recalentar la pieza entera (el
  grill está pensado para producto plano, no para una pieza 3D).
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
- *Producción:* mermelada elaborada en producción, por reducción/asado de
  fruta en horno convectivo (no hay fogón documentado en producción, así
  que la cocción larga tradicional al cazo debe adaptarse a esta técnica,
  según confirma `culinary-development` — es una receta nueva a
  estandarizar y probar, no una conversión directa); pan tostado al
  momento en grill en sala.
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
- *Producción:* `culinary-development` confirma que el escalfado clásico
  "a la minuta" no es viable sin fogón; la alternativa viable es cocción en
  lote a baja temperatura en el horno convectivo de producción (si tiene
  función de vapor/humedad — por confirmar) y regeneración breve en sala en
  un cazo de agua caliente sobre la placa de inducción pequeña. **Dato
  pendiente de mayor impacto:** confirmar cómo se escalfa hoy realmente el
  huevo del Benedict Eggs actual (producto que ya funciona a volumen) antes
  de diseñar un proceso nuevo desde cero.
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
  y tostado del pan en grill tostador en sala. `culinary-development`
  confirma que esta técnica (asado/escalfado al horno) es correcta y
  coherente con no tener fogón.
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
  estandarizar.* La salsa (asumida como holandesa, sin confirmar) necesita
  una base estabilizada para tolerar servicio continuo sin baño maría
  dedicado — receta a probar en RU06.
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
  para quien no busque tanto matcha. `culinary-development` confirma que
  mezclar matcha u hojicha en polvo con la base de crema/yogur es un paso
  breve de preparación en producción (tamizado y disolución previa en
  líquido templado), no un montaje puro en sala — ajuste menor que no
  cambia la viabilidad general ya validada de esta referencia.

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
  `culinary-development` solo señala una nota operativa (no bloqueante):
  vigilar el tiempo de uso de una sola licuadora si varias referencias
  nuevas se lanzan juntas en pico de fin de semana.
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
  especialidad). `culinary-development` confirma que un caramelo clásico
  de fogón no es viable (no hay fogón en producción), pero sí hay una vía
  de adaptación: recomienda, en orden de preferencia, (1) un "dulce de
  leche al horno" con el miso incorporado, cocido al baño maría dentro del
  horno convectivo — la opción más fiable con el equipamiento real; (2)
  caramelo con glucosa/azúcar invertido al microondas en tandas cortas,
  como plan B si la textura de (1) no convence, pero exige más práctica y
  riesgo de fallo; (3) comprarlo ya elaborado a un proveedor e infusionar
  el miso después, recomendación a valorar, no un hecho confirmado (no se
  sabe si existe hoy proveedor ni su coste). A probar en RU06.

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
  dominada hoy con el resto de la repostería de vitrina — `culinary-development`
  la confirma como viable sin ninguna duda), con un relleno distinto cada
  semana — siempre construido sobre **un único matiz japonés de
  identidad**, nunca mezclando varios en la misma pieza, para que cada
  semana tenga una historia de sabor clara y reconocible. Cuatro fórmulas
  de relleno para rotar (no 52 recetas distintas al año, un repertorio que
  se repite con variaciones de temporada):
  1. Curd de yuzu con merengue tostado. `culinary-development` confirma
     que el curd es viable al microondas en tandas cortas o al baño maría
     en el horno, y que el merengue se tuesta con la salamandra de
     producción (sustituto correcto del soplete) — viable sin comprar
     nada nuevo, aunque suma un uso más a un equipo (salamandra) que ya
     puede ser cuello de botella si la referencia 9 también lo usa en la
     misma franja.
  2. Crema diplomática de matcha. Viable al microondas en tandas cortas,
     con el matcha tamizado y disuelto previamente — mismo tipo de paso de
     preparación que el de la referencia 11.
  3. Ganache de chocolate con caramelo de miso (mismo matiz que la
     referencia 18 — comparte exactamente el mismo hueco técnico de cómo
     elaborar el caramelo sin fogón; aplica la misma solución recomendada
     en 18).
  4. Crema de hojicha con un acabado de sésamo negro en crumble. Viable
     sin ajuste de equipamiento, misma lógica que el relleno 2 y que los
     crumbles ya usados hoy en la vitrina.
- *Formato de venta:* lote limitado (tamaño a definir con el cliente y
  `culinary-development` según capacidad real de horno — el riesgo de
  saturación es menor que el de las referencias 5/9 porque es una carga
  semanal, no diaria, pero debe fijarse dentro de la franja de producción
  ya ajustada, no de forma independiente), venta en sala hasta agotar
  stock, comunicado como "edición de la semana" con el nombre del matiz
  (p. ej. "Ritual Semanal: Yuzu"), no con un nombre genérico.
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
- *Nota técnica:* a diferencia de las otras 19 referencias (que ya tenían
  validación técnica desde el borrador original), la referencia 20 no
  tenía producto concreto hasta hoy. `culinary-development` ya realizó su
  validación completa en la actualización del 2026-10-22 (ver
  `culinary-development-validacion-tecnica.md`, sección 7.1): es viable
  con dos puntos pendientes de resolver antes de estandarizar — el
  caramelo de miso del relleno 3 (mismo hueco que la referencia 18) y el
  tamaño del lote semanal frente a la capacidad real del horno. Ningún
  otro punto queda abierto a nivel de proceso.

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

## 4. Product Strategy

### 4.1 Territorios de producto

Más allá de las 20 referencias sueltas, la propuesta se organiza en cuatro
territorios de producto, cada uno resolviendo un problema de negocio
distinto, y un quinto territorio transversal:

1. **Pairing de conversión.** Referencias que no son "comida nueva" en el
   sentido tradicional, sino la formalización en carta de un consumo que ya
   existe hoy (filtro + repostería, espresso + croissant, zumos/smoothies +
   Benedict Eggs/Tosta Aguacate). Ataca directamente el hueco de conversión
   de los ~29.500 tickets de solo bebida, con prioridad en filtro (33% con
   comida), espresso (28,3%) y frío especialidad (28,0%) — las tres bebidas
   peor convertidas. Referencias: 1, 2, 3, 13.
2. **Plato con entidad.** Comida de ocasión completa, ticket medio alto,
   construida sobre los dos mayores crecimientos reales de la carta
   (Sandwich de pollo +102%, Benedict Eggs +14-16%) más una sustitución del
   peor comportamiento salado (Sandwich Kimchi). Referencias: 7, 9, 16; y,
   en su vertiente de tosta "de plato", 5 y 6.
3. **Vitrina viva.** Repostería y bollería de autoservicio en rotación de
   sabor o formato, para que el bloque de mayor volumen de la carta (el que
   hoy sostiene el grab&go) no se perciba como estático mientras varias de
   sus referencias top caen por fatiga de producto (CheeseCake -26%, Açai
   Bowl -15%, Berry Bowl -12,5%). Referencias: 4, 8, 10, 11, 14, 15, 17, 18,
   19, 20.
4. **Ocasión compartida.** Un único territorio, de momento, dirigido al
   pico de afluencia del local nuevo (+39% tickets en fin de semana) y al
   segmento mujer 25-35 que busca experiencia más que producto. Referencia:
   12.
5. **Transversal — Acento Geisha (identidad japonesa).** No es un bloque de
   carta ni compite con los cuatro anteriores: es un eje de sabor y
   narrativa que atraviesa 16 de las 20 referencias, en los cuatro
   territorios a la vez. **Este eje es, en sí mismo, un territorio de
   producto que diferencia a Geisha de sus tres competidores directos de
   café (Nubra, The Fix, Davob)** — ninguno de ellos tiene, hasta donde
   se sabe por el propio briefing del cliente, una propuesta de comida
   articulada alrededor de una identidad propia; de hecho, el cliente ya
   señaló que, salvo The Fix, ninguno trabaja comida en serio. El territorio
   japonés no solo cierra el hueco de conversión: le da a la comida de
   Geisha una razón de ser distinta a "croissant y bowls como cualquier
   otra cafetería de especialidad", coherente con el propio nombre de la
   marca.

### 4.2 Familias de producto — Producto → Función principal

Las funciones de negocio (Conversión, Ticket medio, Recurrencia, Captación,
Posicionamiento, Tractor de tráfico) ya se asignaron a cada referencia en la
sección 3.5; aquí se organizan por familia de carta (las mismas de la
arquitectura 3.4) para que la lectura estratégica sea directa de cara al
diseño de carta (sección 6) y a la decisión de recorte de 20 a 10.

**Familia: Vitrina / Bollería y Repostería** (volumen, grab&go, rotación)

| Producto | Función principal |
|---|---|
| 1. Mini bollería de acompañamiento | Conversión / captación de ticket pequeño |
| 8. Banana Bread con topping | Ticket medio (upsell de bajo riesgo) |
| 14. CheeseCake de Temporada | Conversión (pairing filtro) + Recurrencia |
| 17. Carrot Cake con topping | Ticket medio (upsell de bajo riesgo) |
| 18. Brownie Reforzado | Posicionamiento (nueva ocasión) + Ticket medio |
| 19. Mini Viennoiserie de Vitrina | Captación + Conversión |
| 20. Ritual Semanal (Tartaleta de Autor) | Recurrencia + ancla de identidad de marca |

**Familia: Tostas** (puente vitrina-plato, ticket medio-bajo)

| Producto | Función principal |
|---|---|
| 4. Mermelada Artesana de Temporada | Posicionamiento + Ticket medio |
| 5. Tosta Serrano Premium | Ticket medio (upsell sobre ganador validado) |
| 6. Tosta Ibérico Reinventada | Posicionamiento (segmento fiel 35-45) |
| 15. Reformulación Bagel Salmón | Posicionamiento / a determinar con el cliente |

**Familia: Bowls** (captación experiencia/salud, formato visual)

| Producto | Función principal |
|---|---|
| 10. Açai Bowl de Temporada | Tractor de tráfico + Captación |
| 11. Bowl de Temporada (Yogur/Berry) | Recurrencia + Conversión |

**Familia: Plato (brunch/sandwich)** (ticket medio alto, comida de ocasión)

| Producto | Función principal |
|---|---|
| 7. Sandwich de Pollo Deluxe | Ticket medio + Tractor de tráfico |
| 9. Benedict Eggs — variante | Ticket medio + Recurrencia |
| 16. Nueva referencia salada ligera | Ticket medio / Conversión |

**Familia: Compartible / Ocasión** (ticket medio alto, fin de semana)

| Producto | Función principal |
|---|---|
| 12. Geisha Board | Ticket medio + Captación |

**Familia: Add-on / Upsell — pairing formalizado** (sin nueva elaboración de base)

| Producto | Función principal |
|---|---|
| 2. Dupla Filtro + Repostería | Conversión + Ticket medio |
| 3. Set Espresso & Croissant Clásico | Conversión |
| 13. Zumo/Smoothie de Temporada Premium | Ticket medio + Conversión |

**Lectura de conjunto:** de las seis funciones de negocio, **ninguna
referencia se diseñó pensando en el café** (fuera de alcance, como ya fija
la sección 2.3) — las seis funciones se reparten entre comida y pairing. El
mayor volumen de referencias (7 de 20) está en Vitrina, coherente con que es
el bloque de mayor volumen real de la carta; el territorio de Pairing de
conversión (familia Add-on/Upsell, 3 referencias) es el de menor número de
referencias pero el de mayor palanca directa sobre el problema central del
documento (conversión de los 29.500 tickets de solo bebida), porque ataca
exactamente las tres bebidas peor convertidas.

---

## 5. Estrategia Económica

### 5.1 Benchmark competitivo

El cliente ha nombrado dos conjuntos de competidores: en general, Ambu,
Alchemy y The Fix; específicamente en café, Nubra, The Fix y Davob. Sobre
estos seis negocios, **el único dato real disponible es el nombre y una
observación estratégica propia del cliente** —no hay carta, precios, menu
engineering ni dato de venta de ninguno de ellos en el intake de este
proyecto—, así que este benchmark es, por fuerza, cualitativo y se apoya en
el conocimiento directo que el cliente tiene de su propio mercado, no en
investigación de mercado de TBNB.

La observación del propio Juan, ya validada y usada como base de este
documento: *"en comida, salvo The Fix los otros no tocan comida... estamos
igual o más especializados (seguramente más) en café que cualquiera de los
3. La comida puede ser nuestra ventaja competitiva."* Lo que el dato propio
de Geisha sí confirma, y que refuerza esa observación: la estrategia de café
de filtro (el eje de la marca) funciona con fuerza real (+27% unidades,
+31% ingreso, ya 15% del ingreso de bebida con solo 6% de las unidades), así
que la base sobre la que se construye la ventaja ("más especializados en
café") tiene respaldo de dato, aunque el "más que los otros 3" sea una
afirmación del cliente, no verificada por TBNB.

**Hueco de información explícito, no a inventar:** no se dispone de ningún
dato real de carta, precio, volumen o posicionamiento de Ambu, Alchemy, The
Fix, Nubra o Davob. Cualquier afirmación sobre "cómo es su comida" o "cuánto
cobran" sería inventada y no se incluye aquí. Esto es candidato a una
investigación de mercado futura (visita de producto/mystery guest a estos
cinco negocios, fuera del alcance actual de AR02 — el SOW de este servicio
no incluye mystery guest) si Andrea/Sergio y el cliente lo priorizan antes
de cerrar pricing final de las referencias que entren en las 10 finales.

**Conclusión del benchmark, con el dato real que sí existe:** la comida es
el único terreno donde el cliente percibe que la categoría de café
especializado de su zona no está jugando en serio (salvo The Fix) — y es
exactamente el terreno donde este documento concentra el desarrollo. El
territorio de identidad japonesa (sección 4.1) añade una segunda capa de
diferenciación que, hasta donde se sabe por el propio briefing, ningún
competidor nombrado tiene. Ninguna de estas dos afirmaciones garantiza
resultado comercial: son una lectura de oportunidad sobre el dato
disponible, no una previsión de cuota de mercado.

### 5.2 Conclusiones estratégicas

El objetivo de negocio que ancla todo este documento es concreto: subir el
ticket medio de **9,75€ a 13-15€, sin subir precios**. El propio dato de
venta ya da la palanca y su valor:

- **29.500 tickets anuales son hoy de solo bebida** — el público objetivo
  real de las 20 referencias candidatas, y en particular de las 3 de
  pairing de conversión (2, 3, 13) y de las 2 de entrada de bajo compromiso
  (1, 19).
- **Cada punto de conversión recuperado equivale a ~480 tickets con comida
  al año.** Con la diferencia real de ticket (14,39€ con comida frente a
  7,11€ sin ella, +7,28€ por ticket), esto es, de forma aproximada, **unos
  3.500€ de facturación adicional al año por cada punto de conversión**
  recuperado — cálculo ilustrativo sobre el dato ya existente, no una
  proyección comprometida: asume que el ticket convertido se comporta como
  la media actual de tickets con comida, lo que no está garantizado.
- A modo de ejemplo, **recuperar los ~5 puntos perdidos entre 2024 (41% de
  tickets con comida) y el local nuevo (34-36%)** equivaldría, con el mismo
  cálculo aproximado, a unos 2.400 tickets con comida adicionales al año (
  ~17.500€ de facturación adicional). De nuevo: un escenario ilustrativo
  sobre el dato real, no un compromiso de resultado.
- La **palanca de mix** (dentro de los tickets que ya llevan comida) se
  ataca con los upsells de bajo riesgo (5, 7, 8, 9, 13, 17) y con la
  referencia de mayor ticket unitario de las 20 (12, Geisha Board) — mueve
  gasto hacia arriba sin tocar precio base.

**Cómo atacan las 20 referencias + la capa de identidad japonesa este
objetivo concreto:** la mitad de las 20 referencias está diseñada para
convertir (familias Add-on/Upsell y las entradas de bajo compromiso de
Vitrina), la otra mitad para subir el ticket dentro de lo que ya se vende.
La capa de identidad japonesa no cambia esta arquitectura — la sección 3.6
ya deja dicho que los matices con coste propio encajan en la cláusula de
"precio levemente superior si el cambio de producto lo justifica" sin tocar
la estrategia general de no subir precios base. Su función económica es
distinta: sostener la percepción de valor (y, con ella, la disposición del
cliente a aceptar ese "levemente superior") a través de una diferenciación
real frente a la categoría de café especializado, no sustituir la palanca
de conversión/mix por una de pricing.

**Límite real de esta sección, explícito:** todo lo anterior es una palanca
de **ingreso** (ticket medio, conversión), no de **margen**. Sin food cost
actualizado — los escandallos son de hace 6 años, y los ingredientes nuevos
de la capa de identidad japonesa (yuzu, matcha, miso, hojicha, kinako,
sésamo negro, furikake, nori, yuzu kosho, shichimi togarashi, mirin) no
tienen ni proveedor ni escandallo hoy — **no se puede calcular ni proyectar
un margen bruto real para ninguna de las 20 referencias**. Esta sección se
cierra, por tanto, con la cifra de ingreso que el propio dato de venta ya
permite defender, y deja explícitamente fuera cualquier afirmación de
rentabilidad hasta que `culinary-development` tenga datos de coste reales.
Esto es, además, un servicio de carácter consultivo: ni esta estrategia
económica ni el documento completo garantizan el resultado comercial
descrito — son la dirección mejor fundamentada posible con el dato
disponible hoy.

---

## 6. Recomendaciones para Diseño de Carta

Estas recomendaciones son para quien diseñe la pieza física/visual de carta
(no para este documento en sí) — se entregan ahora porque dependen
directamente del trabajo de las secciones 2 a 5, pero **el diseño gráfico
de la carta no es un entregable de TBNB dentro de AR02** (confirmado por
Andrea, 2026-10-22): esta sección da el contenido y el criterio de
jerarquía/organización para que Geisha (o quien ellos encarguen el diseño)
lo ejecute, no la pieza gráfica final.

1. **Organización de categorías — seguir la arquitectura de 4 papeles
   (sección 2.3) y las familias de producto (sección 4.2), no las
   categorías tradicionales de desayuno/brunch/postre.** Se propone un
   orden de lectura: Café (protagonista, intacto) → "Para acompañar tu
   café" (familia Add-on/Upsell: 2, 3, 13, más las entradas de bajo
   compromiso de Vitrina: 1, 19) → "De plato" (familia Plato: 7, 9, 16, y
   las tostas de mayor entidad: 5, 6) → "De vitrina" (resto de Vitrina y
   Tostas: 4, 8, 10, 11, 14, 15, 17, 18, 20) → "Para compartir" (12, solo
   fin de semana). Este orden sigue la lógica de conversión del propio
   dato: lo primero que ve el cliente de solo bebida es la opción de menor
   fricción, no el plato más caro.
2. **Dar visibilidad a las referencias de mayor función estratégica sin
   romper "el café manda, la comida acompaña".** No usar fotografías a
   toda página ni tamaños de letra que compitan con la sección de café. Se
   recomienda un sistema de señalización discreto y textual (p. ej. un
   pequeño marcador junto al nombre del producto) para las referencias
   tractoras de tráfico (7, 10) y la de recurrencia/identidad (20) — no un
   destacado visual grande, sino una nota breve que explique por qué
   importa (p. ej., junto al Sandwich de Pollo Deluxe: "el más pedido de
   nuestra cocina"). El Geisha Board (12), por ser la pieza de mayor
   ticket y de ocasión específica, puede tener su propio recuadro aparte
   (carta de fin de semana o inserto), coherente con que solo está
   disponible cuando hay hostess.
3. **Comunicar el matiz de identidad japonesa sin que suene a "carta de
   fusión" ni a gimmick.** Se recomienda: (a) una nota breve una sola vez,
   al principio del bloque de comida, explicando el criterio en una frase
   (p. ej. "pequeños guiños a la tradición japonesa que da nombre a
   Geisha, en dosis justas, nunca para tapar el producto") — así el cliente
   entiende el porqué antes de leer el primer ingrediente; (b) nombrar el
   ingrediente concreto en la descripción de cada plato, nunca una
   categoría genérica tipo "toque oriental" o "fusión asiática" (p. ej.
   "con un velo de yuzu kosho" en vez de "con un toque exótico"); (c) dejar
   sin ningún lenguaje de identidad las tres referencias que ya se
   decidió dejar sin matiz (2, 3, 19), precisamente para que el acento no
   se perciba como obligatorio en todo; (d) dar a la referencia 20 su
   propio tratamiento editorial — nombre semanal visible ("Ritual Semanal:
   Yuzu"), porque es la pieza donde la identidad tiene más protagonismo
   por diseño (sección 3.5, referencia 20) y conviene que se note en la
   carta, no solo en el producto.
4. **Pairing explícito en el propio texto de la carta**, formalizando el
   comportamiento de consumo ya documentado en 3.3: filtro + repostería
   (nota corta junto a la descripción del filtro, señalando CheeseCake,
   Banana Bread o Carrot Cake de temporada); espresso + croissant (el Set
   3, ya pensado como combo de carta, clásico y sin acento añadido);
   zumos/smoothies + Benedict Eggs/Tosta Aguacate (nota junto a la sección
   de zumos, dado que es el pairing de mayor conversión real y el menos
   explotado hoy, 66,2% de sus tickets ya llevan comida). Estas notas deben
   leerse como sugerencia, no como venta forzada — coherente con el tono
   "honesto y transparente" de la misión declarada del cliente.

---

## 7. Siguientes pasos

1. **Presentar las 20 referencias candidatas a Juan** para que el cliente
   recorte a las 10 del alcance contratado de AR02, con Andrea/Sergio
   mediando en la conversación — el criterio de priorización usado para
   llegar a estas 20 (sección 3.5) se explica al cliente como punto de
   partida, no como decisión ya tomada por TBNB.
2. **Confirmar con el cliente el nivel de identidad japonesa deseado** —
   este documento aplica un matiz discreto en la mayoría de referencias y
   uno con más protagonismo en la referencia 20 (Ritual Semanal); falta
   validar con Juan si ese reparto es el tono que tiene en mente, antes de
   llevarlo a diseño de carta.
3. **Cotizar con proveedores de producto japonés/asiático** (yuzu, matcha,
   miso, hojicha, kinako, sésamo negro, furikake, nori, yuzu kosho,
   shichimi togarashi, mirin) — idealmente comparando 2-3 distribuidores
   dado el rango de calidad/precio del matcha y el yuzu en particular —
   antes de cerrar pricing real de cualquier referencia con matiz.
4. **Confirmar con la propiedad si existe food cost más reciente** que el
   de hace 6 años, sobre todo de ibérico y salmón (materia prima local ya
   comprada hoy) — la respuesta previa del cliente ("ya conocidas. NA")
   sigue siendo ambigua y condiciona toda la estrategia de precio final.
5. **Confirmar si el equipamiento de cocina documentado sigue vigente**
   tras la mudanza de octubre — no hay foto ni vídeo del local nuevo que lo
   confirme visualmente; si difiere, hay que revisar la validación técnica
   completa antes de estandarizar ninguna receta.
6. **Probar en RU06 (2 jornadas presenciales) las técnicas marcadas como "a
   validar en práctica"**: el caramelo de miso (dulce de leche al horno,
   primera opción recomendada, referencias 18 y 20), el huevo poché/
   regeneración en placa pequeña (referencias 5 y 9), y el merengue tostado
   a la salamandra (referencia 20) — ninguna debe estandarizarse en carta
   sin esta prueba.
7. **Revisar el Brand Kit/Brand Book del cliente en profundidad** (todavía
   no leídos línea a línea, solo la descripción textual del briefing) antes
   de la presentación final, para confirmar que el tono de identidad
   japonesa no choca con ningún matiz de marca ya definido por el cliente.

---

## Preguntas abiertas / datos a confirmar antes de cerrar este documento

1. **Brand Kit y Brand Book del cliente no se han leído en profundidad**
   (son PDFs grandes, ~35-37MB, en Drive, no incluidos en este repo). El
   posicionamiento gastronómico de la sección 2 se ha construido sobre la
   descripción textual del briefing, no sobre el documento de marca
   completo — confirmar que no hay matices de tono/identidad en el Brand
   Book que contradigan algo de este documento antes de darlo por cerrado
   (ver también siguiente paso 7).
2. **`menu español (2).pdf` (carta actual) y
   `Geisha_Analisis_Productos_2021-2026_v5.xlsx`** tampoco se han revisado
   en detalle — el xlsx probablemente trae menu engineering y costes de
   materia prima más finos que el resumen ejecutivo de ventas usado aquí.
   Revisarlo puede afinar o corregir alguna de las 20 referencias
   propuestas, especialmente las reformulaciones (4, 6, 10, 14, 15, 18).
3. **Escandallos/food cost actual:** el cliente respondió "ya conocidas.
   NA" de forma ambigua. Confirmar con Juan si existe food cost reciente
   (de un trabajo previo de TBNB con este cliente, por ejemplo) o si se
   trabaja sin él — condiciona directamente la estrategia de precio final
   y el cálculo de margen de la sección 5.2, que hoy queda explícitamente
   sin resolver.
4. **Criterio de recorte de 20 a 10**: este documento no decide cuáles de
   las 20 son las 10 finales — eso corresponde al cliente, con
   Andrea/Sergio mediando (ver siguiente paso 1).
5. **Referencias 6 y 15** (Tosta Ibérico, Bagel Salmón) se proponen como
   reformulación, no como retirada — confirmar con el cliente si hay
   contexto adicional (motivo real de la caída: precio, ejecución,
   proveedor) que cambie esa recomendación.
6. **Confirmar si el equipamiento de cocina sigue vigente tras la mudanza
   de octubre** (fotos/vídeos originales son de julio 2026, antes del
   cambio de local) — Andrea ya lo dio por vigente con los matices del
   grill tostador y la inducción pequeña, pero no hay vídeo/foto del local
   nuevo que lo confirme visualmente (ver siguiente paso 5).
7. **Capa de identidad japonesa:** no hay proveedor ni escandallo hoy de
   ninguno de los ingredientes usados en los matices (yuzu, matcha, miso,
   hojicha, kinako, sésamo negro, furikake, nori, yuzu kosho, shichimi
   togarashi, mirin) — antes de dar por cerrado cualquier matiz concreto
   hay que confirmar disponibilidad real de proveedor y coste (ver
   siguiente paso 3).
8. **Caramelo de miso (referencias 18 y 20):** necesita que
   `culinary-development` y RU06 confirmen cómo se elabora un caramelo sin
   fogón documentado en producción (dulce de leche al horno recomendado
   como primera opción, microondas con glucosa como plan B, o compra a
   proveedor como alternativa) antes de estandarizarlo en ninguna de las
   dos referencias.
9. **Referencia 20 ("Ritual Semanal"):** ya tiene producto concreto y ya
   pasó por la validación técnica completa de `culinary-development`
   (2026-10-22); quedan dos puntos abiertos específicos (caramelo de miso
   del relleno 3, y tamaño del lote semanal frente a capacidad de horno) a
   cerrar antes de RU06.
10. **Nivel de identidad japonesa deseado por el cliente:** este documento
    aplica un criterio de "matiz pequeño y discreto" en la mayoría de
    referencias y uno "de autor, con más protagonismo" solo en la
    referencia 20 — conviene confirmar con Juan si ese reparto es el tono
    que tiene en mente (ver siguiente paso 2).
11. **Benchmark competitivo real** (sección 5.1): no hay dato de carta,
    precio o venta de Ambu, Alchemy, The Fix, Nubra o Davob más allá del
    nombre y la percepción propia del cliente — queda marcado como hueco de
    información, candidato a una investigación de mercado futura (mystery
    guest/visita de producto), fuera del alcance actual de AR02, a
    priorizar o no con Andrea/Sergio y el cliente.
12. **Margen bruto proyectado** (sección 5.2): no es calculable hasta tener
    food cost real de materia prima base y de los ingredientes japoneses
    nuevos — este documento solo puede argumentar la palanca de ingreso
    (ticket medio, conversión), no la de margen, y lo deja dicho de forma
    explícita en las conclusiones estratégicas.
13. **Alcance del diseño gráfico de la carta — resuelto (2026-10-22).**
    Confirmado por Andrea: TBNB no crea la pieza gráfica final. La
    sección 6 da contenido y criterio de jerarquía/organización; la
    ejecución visual corresponde a Geisha o a quien ellos encarguen el
    diseño.

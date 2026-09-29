# Maquetación Elementor — "Abrir un bar o restaurante" (`/abrir-restaurante-bar/`)

**Rol:** `web-maquetacion-elementor`. **Fecha:** 2026-09-29.

**Entradas:**
- `pagina-web/paginas/abrir-restaurante-bar-copy.md` (copy final — no se
  cambia ni una palabra aquí).
- `pagina-web/seo-briefs/abrir-restaurante-bar.md` (indicaciones de
  maquetación del SEO).
- `pagina-web/diseno-visual-tbnb.md` (paleta y los 11 patrones reales de
  `/bar-method/`).

**Nota de método sobre tipografía:** `diseno-visual-tbnb.md` describe la
tipografía observada solo como "sans-serif de peso bold/black" (titulares)
y "sans-serif regular" (cuerpo) — **no nombra familias tipográficas
concretas** (ni Epilogue ni Helvetica Neue aparecen en esa fuente). Por
tanto, en todo este documento la tipografía se indica como "sans-serif
bold/black (titulares) / sans-serif regular (cuerpo), familia exacta a
confirmar contra el kit real de Elementor del sitio" — no se da Epilogue
ni Helvetica Neue por definitivo porque no está confirmado en la fuente
visual.

**Nota de método sobre color:** los colores de fondo que sí están
confirmados en `diseno-visual-tbnb.md` se citan por nombre (red bar,
tangerina, lemon icon, lilacocktail, le bleu, negro, blanco/gris claro).
Para cualquier bloque de esta página que no tenga un equivalente exacto
entre los 11 patrones documentados, se marca explícitamente como "a
confirmar contra el kit real de Elementor" en vez de asumir un color.

---

## Ajustes de página (no son un widget)

- **Title, Description, URL:** sin cambios respecto al brief SEO — se
  configuran en los campos de SEO del plugin del sitio (Yoast/RankMath),
  no en un widget de Elementor. Reproducir tal cual está en el copy final.

---

## Bloque 1 — Hero (H1 + intro + CTA)

**1. Tipo de sección/widget:** Sección Hero a doble columna (texto +
botón a la izquierda / elemento visual a la derecha). Corresponde al
**Patrón 3** de `/bar-method/` ("Hero split — fondo negro, izquierda H1 +
párrafo + botón, derecha tarjeta visual"). Recomiendo reutilizar la
misma plantilla/sección global de Elementor del hero de `/bar-method/` si
existe como bloque guardado, cambiando solo el contenido.

**2. Contenido exacto:**
- H1: "Asesoría y guía para abrir un bar o restaurante con éxito"
- Párrafo 1: "Poner en marcha un bar o restaurante es de las decisiones
  más intensas que vas a tomar — y de las que menos margen dan para
  improvisar. Si has llegado hasta aquí porque quieres abrir un
  restaurante o montar un bar sin dejarte el capital (ni la cabeza) por
  el camino, no hace falta que inventes nada: existe un método con
  nombre y apellido, el **BAR Method** — Breakdown, Architecture, Run —
  y lo aplicamos contigo, no en tu lugar."
- Párrafo 2: "En esta página te contamos los pasos críticos para
  arrancar y cómo estructuramos tu proyecto desde cero, para que al
  decidir montar tu negocio no dependas de la suerte ni de haberlo visto
  en un vídeo."
- Botón: "QUIERO ABRIR MI NEGOCIO" — destino: "formulario de contacto /
  agenda de 15 min — mismo flujo ya existente en el sitio, no uno nuevo"
  (tal cual indica el copy). **A confirmar contra el sitio real:** cuál
  es la URL/ancla exacta que usa hoy el botón equivalente de
  `/bar-method/` ("AGENDAR CITA"), para apuntar este botón al mismo
  destino.

**3. Notas de diseño:**
- Fondo: **negro** (`#0B0B0B` aprox.), como en el Patrón 3.
- Botón CTA: **red bar** (`#E94A4B`) — coherente con el uso confirmado
  de ese color para CTAs principales en el sitio.
- Párrafo: gris claro sobre fondo negro (mismo patrón que en
  `/bar-method/`).
- Tipografía: H1 en sans-serif bold/black; párrafos en sans-serif
  regular (familia exacta a confirmar contra el kit).

**4. Recurso visual necesario:** en `/bar-method/` el lado derecho del
hero lleva 3 cuadrados decorativos de color + una tarjeta con overlay
"CASO DE ÉXITO". Para esta página, sugiero mantener los cuadrados
decorativos (elemento de marca ya existente, sin coste de producción) y,
si se quiere un elemento adicional, una foto real de una apertura de
TBNB (obra en curso o inauguración) — a conseguir del archivo de
proyectos, no a generar aquí.

---

## Bloque 2 — H2 "Pasos a seguir para abrir un negocio de hostelería sin quemar tu capital"

**1. Tipo de sección/widget:** No corresponde exactamente a ninguno de
los 11 patrones documentados (no es un hero, ni tarjetas BAR, ni
checklist con CTA). Sugiero una sección de contenido con **5 bloques
numerados** tipo "Icon Box" o "Image Box" en columna única (número grande
+ H3 + texto), o alternativamente un widget de **Toggle/Accordion** si el
kit real del sitio ya usa ese patrón en otras páginas — el brief SEO no
pide expresamente un acordeón, así que la opción por defecto es la lista
numerada visible (no plegada), para no esconder contenido que es central
para el SEO on-page. Confirmar contra el kit real cuál de las dos
variantes ya existe como bloque reutilizable.

**2. Contenido exacto:**
- H2: "Pasos a seguir para abrir un negocio de hostelería sin quemar tu
  capital"
- Intro: "No es una lista de tareas de manual. Es el orden real en el
  que se cae —o en el que se levanta— un proyecto de hostelería. Lo
  hemos visto pasar muchas veces, y casi siempre se puede evitar a
  tiempo."
- H3 1: "1. Define el concepto (y asegúrate de que tiene mercado)" +
  texto: "El mercado no necesita otra copia. Antes de pensar en la carta
  o en la decoración, hay que responder algo más incómodo: qué vas a
  ofrecer, a quién, y por qué te van a elegir a ti y no al bar de la
  esquina. Eso significa mirar de verdad el barrio, la competencia y las
  tendencias — no rellenar una presentación de intenciones."
- H3 2: "2. Elabora tu [plan de viabilidad financiera](/abrir-restaurante-bar/plan-de-negocio/)"
  + texto: "Aquí es donde se le va la fuerza a muchos proyectos que
  empiezan con toda la ilusión del mundo. En nuestra experiencia, no
  suele fallar la ambición: falla el control — el food cost calculado a
  ojo, el stock que se lleva por intuición y no por número, los
  márgenes que se diluyen en cuanto el negocio empieza a crecer. Nuestro
  plan de viabilidad financiera pone cifras reales encima de la mesa
  antes de que las pongas tú con el negocio ya abierto: estructura de
  costes, previsión de ventas y el punto exacto en el que empiezas a
  ganar dinero de verdad." El enlace "plan de viabilidad financiera" va
  como texto ancla dentro del H3, apuntando a
  `/abrir-restaurante-bar/plan-de-negocio/` (URL sin verificar en el
  sitio en vivo — pendiente ya señalada en `BRIEF.md`).
- H3 3: "3. La búsqueda de local y el papeleo" + texto: "No te enamores
  del primer local que veas — pasa más de lo que crees. Antes de firmar
  nada hay que revisar lo que no se ve a simple vista: salidas de humos,
  aforo, insonorización, licencias municipales. Un alquiler bonito con
  un problema de aforo no es una oportunidad, es una persiana bajada con
  gastos."
- H3 4: "4. Interiorismo y ejecución de obra" + texto: "El concepto
  tiene que respirar en las paredes, no quedarse en una presentación. La
  obra tiene que cumplir con sanidad y accesibilidad sin renunciar a la
  atmósfera que hace que alguien quiera quedarse a la segunda copa."
- H3 5: "5. Escandallos, proveedores y equipo" + texto: "La carta se
  costea al céntimo, no a ojo. Fichas técnicas, negociación real con
  proveedores, selección y formación del equipo que va a estar delante
  del cliente cuando tú no puedas estar. No es el capítulo aburrido: es
  el que decide si el negocio también da de comer a quien lo lleva."

**3. Notas de diseño:**
- Fondo: **blanco o gris claro**, alternando con el hero negro anterior
  (siguiendo la nota general de `diseno-visual-tbnb.md`: "cada sección
  grande tiende a tener un color de fondo dominante... alternando con
  secciones en blanco"). No hay un patrón de los 11 que fije un color
  concreto para este tipo de bloque de pasos — **a confirmar contra el
  kit real**.
- H2/H3: sans-serif bold/black; cuerpo: sans-serif regular.
- El enlace interno dentro del H3 2 en **red bar**, como color de enlace
  de marca (coherente con el uso de ese color para elementos
  interactivos/CTA en el resto del sitio) — a confirmar contra el kit si
  el sitio usa otro color de enlace por defecto.

**4. Recurso visual necesario:** un icono por paso (5 iconos: bombilla o
diana para "concepto", gráfico/calculadora para "viabilidad", llave o
plano para "local y papeleo", brocha/interiorismo para "obra", báscula o
lista para "escandallos y equipo"). No hay iconos de este tipo
documentados en `diseno-visual-tbnb.md` — a conseguir o confirmar contra
la librería de iconos ya usada en el sitio.

---

## Bloque 3 — H2 "¿Qué se necesita y qué requisitos exige abrir un bar o restaurante?"

**1. Tipo de sección/widget:** Párrafo intro + **Icon List** (5 ítems)
para los trámites + párrafo de cierre. No hay un patrón exacto entre los
11 documentados; el más cercano en espíritu es el **Patrón 6** ("Bloque
de confianza/checklist sobre fondo negro, con lista de puntos y CTA
final"), pero aquí no hay CTA al final de este bloque concreto (el CTA
de 15 min llega más abajo, en su propio H2) — por eso no lo copio
literal, solo tomo prestada la idea de "lista de puntos sobre fondo
oscuro" como opción, marcada como sugerencia, no como patrón confirmado
para este bloque exacto.

**2. Contenido exacto:**
- H2: "¿Qué se necesita y qué requisitos exige abrir un bar o
  restaurante?"
- Intro: "Aquí es donde se te puede ir el dinero sin que abras la
  persiana ni un solo día: un local no abre hasta que el ayuntamiento y
  sanidad dicen que sí, y ese camino tiene más trampas de las que parece
  a simple vista. No hace falta asustarte con esto — hace falta que lo
  tengas controlado desde el primer día, y que sepas con quién cuentas
  para cada trámite."
- Etiqueta de lista: "Trámites que pueden paralizar tu proyecto:"
- Ítems de la Icon List:
  - "Licencia de actividad y obras (proyecto técnico visado)."
  - "Gestión de la salida de humos (normativas municipales, filtros de
    carbón activo, permisos de comunidad de vecinos)."
  - "Estudios de insonorización y acústica."
  - "Certificaciones e inspecciones OCA (revisiones eléctricas de baja
    tensión obligatorias)."
  - "Permisos de terraza y aforo (impactan directamente en tu capacidad
    de facturación)."
- Cierre: "Te acompañamos en cada uno de estos pasos, coordinando con
  los técnicos y gestores adecuados para que nada se quede parado por un
  papel que falta."

> **Nota para `web-redaccion` (no se resuelve aquí):** el copy final ya
> incluye su propia nota inline indicando que el verbo "coordinamos con"
> es deliberado hasta que se resuelva la pregunta abierta 1
> (tramitación directa vs. coordinación externa). Esto no afecta a la
> maquetación — el campo de texto es el mismo campo tanto si el verbo
> final es "coordinamos" como "gestionamos"; solo aviso de que, si el
> verbo cambia, hay que actualizar el contenido de este mismo campo, no
> la estructura del bloque.

**3. Notas de diseño:**
- Fondo: sección alterna — si el Bloque 2 usa blanco, este puede ir en
  **gris claro** (`#EDEDED` aprox.), siguiendo el patrón general de
  alternancia. A confirmar contra el kit real si existe ya una sección
  de este tipo con color fijo.
- Iconos de la Icon List: si se opta por la variante "sobre fondo
  negro" inspirada en el Patrón 6, los iconos irían en **red bar** o
  **lemon icon** (colores de acento ya usados sobre fondo negro en el
  sitio) — a confirmar cuál de los dos encaja mejor visualmente contra
  el kit.
- Tipografía: H2 sans-serif bold/black; lista y párrafos sans-serif
  regular.

**4. Recurso visual necesario:** un icono por trámite (documento con
sello para "licencia de actividad", chimenea/humo para "salida de
humos", onda sonora para "insonorización", enchufe/rayo para "OCA",
sombrilla o mesa de terraza para "permisos de terraza"). A conseguir de
la librería de iconos del kit de Elementor del sitio.

---

## Bloque 4 — H2 "Nuestro Plan Integral: ¿Por qué no deberías hacerlo solo?"

**1. Tipo de sección/widget:** El candidato natural es el **Patrón 5**
("Bloque de 3 tarjetas de color — BAR method: Breakdown/rojo,
Architecture/naranja, Run/amarillo — sobre fondo negro, tarjetas tipo
nota adhesiva"), ya que el copy organiza explícitamente cada punto por
fase del BAR Method. **Aviso importante:** el copy final trae **4
puntos**, no 3 — "Legalizaciones" y "Branding" están ambos etiquetados
como *(Architecture)*. Esto no encaja de forma automática en el Patrón 5
tal cual está documentado (una tarjeta por fase, 3 tarjetas en total).
Dos opciones de maquetación, a decidir antes de construir (no es una
cuestión de copy, así que no se traslada a `web-redaccion`):
  - **Opción A:** mantener 3 tarjetas (Breakdown / Architecture / Run) y,
    dentro de la tarjeta naranja de Architecture, incluir "Legalizaciones"
    y "Branding" como dos sub-puntos dentro de la misma tarjeta.
  - **Opción B:** usar una grid de **4 tarjetas** (Image Box / Info Box),
    rompiendo el patrón exacto de "3 notas adhesivas", pero manteniendo
    el código de color por fase (Breakdown rojo, Architecture naranja ×2
    tarjetas, Run amarillo).
  Recomiendo la Opción A por fidelidad al patrón visual ya existente en
  `/bar-method/`, pero lo dejo como decisión abierta — **a confirmar
  contra el kit real** cuál encaja mejor con el bloque de tarjetas ya
  construido.

**2. Contenido exacto:**
- H2: "Nuestro Plan Integral: ¿Por qué no deberías hacerlo solo?"
- Intro: "No es una lista de servicios sueltos. Es un método con tres
  fases y un solo objetivo: que no lo hagas solo."
- Ítem 1 — **Modelo económico** *(Breakdown)*: "Diagnosticamos la
  estructura real de tu proyecto antes de que gastes el primer euro:
  protegemos tu inversión desde el papel, no después del primer mes
  malo."
- Ítem 2 — **Legalizaciones** *(Architecture)*: "Te acompañamos en la
  tramitación de las licencias técnicas y en la relación con el
  ayuntamiento, para que el proyecto avance sobre papel antes de tocar
  ladrillo."
- Ítem 3 — **Branding** *(Architecture)*: "Tu concepto tiene que
  respirar en la carta y en el espacio, no vivir solo en un logo bonito.
  Coordinamos el diseño visual con lo que de verdad vas a servir."
- Ítem 4 — **Operativa** *(Run)*: "Carta de comida y bebida, equipo
  formado y un negocio listo para el día de la apertura, no para el día
  después."

**3. Notas de diseño:**
- Fondo: **negro**, igual que en el Patrón 5.
- Tarjeta "Modelo económico" (Breakdown): **red bar**.
- Tarjeta(s) "Legalizaciones" / "Branding" (Architecture): **tangerina**.
- Tarjeta "Operativa" (Run): **lemon icon**.
- Tipografía: eyebrow de fase en mayúsculas con letter-spacing amplio
  (mismo tratamiento que "TU SITUACIÓN"/"NUESTRO MÉTODO" documentado);
  título del ítem en sans-serif bold/black; texto en sans-serif regular.

**4. Recurso visual necesario:** ninguno nuevo — reutilizar las letras
grandes B/A/R y el estilo de "nota adhesiva con muesca" ya existentes en
el bloque BAR Method de `/bar-method/`.

---

## Bloque 5 — H2 "No lo decimos, lo demostramos" (Proyectos destacados)

**1. Tipo de sección/widget:** Grid de **Image Box** (2 columnas por
ahora, con espacio para crecer a 3-4 si se añaden más proyectos
verificados — el brief SEO pedía "3-4 tarjetas", pero el copy final solo
incluye 2 porque son los únicos proyectos con ficha verificada según
`BRIEF.md`). No es exactamente el Patrón 7 ("Caso de éxito" — sección de
color sólido con cifras grandes y una sola cita), porque aquí no hay
cifras ni una única tarjeta protagonista, sino dos tarjetas de proyecto
en paralelo — por eso sugiero Image Box/Info Box en grid en vez de
replicar el Patrón 7 completo. Si en el futuro se dispone de una cifra
verificada para alguno de los dos proyectos (ver nota del copy), esa
tarjeta concreta sí podría subir de nivel al formato completo del Patrón
7.

**Nota de consistencia:** `pagina-web/paginas/marketing-gastronomico-maquetacion.md`
especifica este mismo bloque (con el mismo nombre de H2, "No lo decimos,
lo demostramos", y los mismos dos proyectos) para la otra página nueva, y
señala que el brief/copy de esa página sugiere que **puede que ya exista
un bloque reutilizable de "Proyectos Destacados"** en el sitio. Si ese
bloque global existe, lo coherente es que esta página lo reutilice
también (mismo formato visual), cambiando solo el texto introductorio de
cada página. Confirmarlo contra la librería de Elementor antes de
construir nada nuevo en cualquiera de las dos páginas.

**2. Contenido exacto:**
- H2: "No lo decimos, lo demostramos"
- Intro: "Las palabras convencen poco en este sector. Los proyectos
  reales, algo más."
- Tarjeta 1 — **Religion Coffee**: "De concepto a negocio en marcha:
  estructuramos el modelo, cuidamos cada detalle de marca y de
  operativa para que el proyecto funcionara en el día a día, no solo
  sobre el papel." Enlace: "Ver el caso completo →" → `/proyectos/`.
- Tarjeta 2 — **Eat My Trip**: "Un concepto con identidad propia que
  necesitaba un negocio capaz de sostenerlo detrás: le dimos estructura,
  números y una operativa real desde el primer día." Enlace: "Ver el
  caso completo →" → `/proyectos/`.

> Nota heredada del copy: sin cifras porque no están verificadas — no se
> añade ninguna aquí. URL `/proyectos/` genérica para ambos enlaces
> (pendiente de verificar si cada proyecto tiene ficha propia con URL
> distinta, ver `BRIEF.md`).

**3. Notas de diseño:**
- Fondo: **blanco**, alternando con el negro del bloque anterior.
- Eyebrow de tarjeta (p. ej. "CASO DE ÉXITO" o el nombre del proyecto):
  color **tangerina**, coherente con el uso de ese color para "sección
  de caso de éxito" en el resto del sitio.
- Botón/enlace "Ver el caso completo →": **red bar**, igual que el botón
  equivalente del Patrón 7.
- Tipografía: título de tarjeta sans-serif bold/black; texto sans-serif
  regular.

**4. Recurso visual necesario:** foto real de cada proyecto (Religion
Coffee, Eat My Trip) — a conseguir de la ficha ya publicada de cada uno
en `/proyectos/` (o `/en/religion-coffee/` y `/en/eat-my-trip/`, según
`BRIEF.md`), no a generar aquí. Alt-text sugerido: "Interior/local de
Religion Coffee, proyecto de apertura de The Bar N' Bar" y
"Interior/local de Eat My Trip, proyecto de apertura de The Bar N' Bar"
— a ajustar con la foto real que se use.

---

## Bloque 6 — H2 "¿Tienes un proyecto en mente? Hablemos de realidad" (CTA de 15 min)

**1. Tipo de sección/widget:** **CTA banner**, correspondiente al
**Patrón 9** ("CTA final — fondo amarillo, titular + párrafo + botón,
con elemento gráfico"). Este es literalmente el mismo CTA de 15 minutos
ya confirmado como "estrella polar" del sitio (ver
`diseno-visual-tbnb.md`) — **recomiendo reutilizar el bloque/sección
global guardado de Elementor que ya existe en `/bar-method/` para este
CTA**, cambiando como mucho el H2 si hace falta, en vez de reconstruirlo
desde cero. (`marketing-gastronomico-maquetacion.md` hace la misma
recomendación para su propia página — coherente entre ambas.)

**2. Contenido exacto:**
- H2: "¿Tienes un proyecto en mente? Hablemos de realidad"
- Texto: "Una conversación de 15 minutos. Sin compromiso. Para entender
  dónde estás, qué te está frenando y si tiene sentido que trabajemos
  juntos en la apertura de tu negocio. Si creemos que podemos ayudarte,
  te decimos cómo. Y si no, también te lo decimos."
- Botón: "AGENDAR REUNIÓN GRATUITA DE 15 MINUTOS" (variante de texto de
  botón permitida por `diseno-visual-tbnb.md`; el mensaje de fondo es el
  mismo que "AGENDAR CITA" de `/bar-method/`).

**3. Notas de diseño:**
- Fondo: **lemon icon** (`#FCE312`), igual que el Patrón 9.
- Botón: a confirmar contra el kit real qué color de botón usa hoy el
  CTA de `/bar-method/` sobre fondo amarillo (en la descripción del
  patrón no se especifica el color exacto del botón, solo del fondo).
- Tipografía: H2 sans-serif bold/black; texto sans-serif regular.

**4. Recurso visual necesario:** ninguno nuevo — reutilizar el elemento
gráfico ya existente (sticker "HELLO", forma orgánica) del CTA de
`/bar-method/` si se reutiliza el bloque global.

---

## Bloque 7 — H2 "¿Solo necesitas ayuda en un área? Servicios a la carta para tu apertura"

**1. Tipo de sección/widget:** Grid de **4 tarjetas** (Image Box / Icon
Box), tal como pide explícitamente el brief SEO ("bloque de
cross-selling — grid de 4 tarjetas"). No corresponde a ninguno de los 11
patrones de `/bar-method/` documentados tal cual (no hay un bloque de
cross-selling de 4 columnas entre los observados) — **a confirmar contra
el kit real** si ya existe un bloque reutilizable de este tipo en otra
página de servicios del sitio. `marketing-gastronomico-maquetacion.md`
usa el mismo tipo de widget (grid de 4 tarjetas) para su bloque
equivalente — mismo criterio en ambas páginas.

**2. Contenido exacto:**
- H2: "¿Solo necesitas ayuda en un área? Servicios a la carta para tu
  apertura"
- Intro: "No todo el mundo necesita el menú completo. Si ya tienes el
  resto resuelto y solo te falta una pieza, aquí tienes las que servimos
  por separado:"
- Tarjeta 1: "Una carta que también cuadra en caja" → enlace "Diseño de
  carta y gastronomía" → `/consultoria-gastronomica/`
- Tarjeta 2: "Un lanzamiento que se nota desde el primer servicio" →
  enlace "Marketing de lanzamiento" → `/marketing-gastronomico/`
- Tarjeta 3: "Un equipo que se queda, no que rota" → enlace "Selección y
  equipo" → `/servicios/consultoria-rrhh-hosteleria/`
- Tarjeta 4: "Un TPV y una digitalización que no dan dolores de cabeza"
  → enlace "Digitalización y TPV" →
  `/servicios/consultoria-tecnologica-hosteleria/`

> Nota heredada del copy: URLs sin verificar en el sitio en vivo —
> pendiente ya señalada en `BRIEF.md`, no se resuelve en esta fase.
> Ojo: el enlace 2 de este bloque apunta a `/marketing-gastronomico/`,
> mientras que la URL confirmada del brief SEO de esa página y en
> `pagina-web/BRIEF.md` es `/marketing-gastronomico-restaurantes/` — no
> lo corrijo aquí porque no es una decisión de maquetación (es una URL
> del copy final), pero lo señalo para que se verifique junto con el
> resto de URLs antes de publicar.

**3. Notas de diseño:**
- Fondo: **blanco o gris claro** — a confirmar contra el kit real.
- Título de cada tarjeta en sans-serif bold/black; enlace en **red bar**
  (color de enlace/CTA de marca).
- Tipografía de cuerpo: sans-serif regular.

**4. Recurso visual necesario:** un icono por servicio (carta/menú para
"Diseño de carta", megáfono para "Marketing de lanzamiento",
personas/equipo para "Selección y equipo", pantalla/TPV para
"Digitalización y TPV") — a conseguir de la librería de iconos del kit.

---

## Bloque 8 — H2 "Operamos donde está el negocio"

**1. Tipo de sección/widget:** **Icon List** o grid pequeño de 3 ítems
(silos locales), en línea con la indicación del SEO ("bloque de
enlazado a silos locales, para SEO geolocalizado"). No corresponde a un
patrón visual específico de los 11 documentados — sugerido como bloque
simple de enlaces con icono de ubicación, **a confirmar contra el kit
real**. `marketing-gastronomico-maquetacion.md` propone el mismo tipo de
bloque (texto + Icon List) para su silo local equivalente.

**2. Contenido exacto:**
- H2: "Operamos donde está el negocio"
- Intro: "Trabajamos donde tú vas a abrir la persiana. Hoy eso significa
  Barcelona, nuestra casa, y Madrid. Si tu proyecto está en otra ciudad
  o país, hablamos igual — la primera conversación no cambia."
- Ítem 1: "Aperturas en Barcelona" → `/consultoria-hosteleria-barcelona/`
- Ítem 2: "Aperturas en Madrid" → `/consultoria-hosteleria-madrid/`
- Ítem 3: "Para otras ciudades o países, hablamos aquí." → `/contacto/`

> Nota heredada del copy: texto sin diferenciar "sede" vs. "también"
> entre Barcelona y Madrid — pendiente para Andrea/Sergio (ver copy
> final, bloque 9). No afecta a la estructura de este widget: si el
> texto cambia, es el mismo campo, no una reestructuración.
> Adicionalmente, URLs sin verificar en el sitio en vivo (misma
> pendiente general de `BRIEF.md`).

**3. Notas de diseño:**
- Fondo: **gris claro**, para cerrar la página en una sección neutra
  antes del footer — a confirmar contra el kit real.
- Iconos de ubicación (pin) en **red bar** o negro — a confirmar.
- Tipografía: H2 sans-serif bold/black; lista sans-serif regular.

**4. Recurso visual necesario:** iconos de ubicación/pin (Barcelona,
Madrid, "otras ciudades"). Opcional: mini-mapa o ilustración
geolocalizada, no imprescindible.

---

## Anexo — Enlace/tarjeta desde `/bar-method/` hacia esta página

Según `pagina-web/BRIEF.md` ("Decisiones ya confirmadas por Andrea"),
`/bar-method/` necesita un enlace o tarjeta hacia esta página nueva
(y, por separado, hacia `/marketing-gastronomico-restaurantes/`).

**Ya existe una propuesta hermana para la otra página:**
`pagina-web/paginas/marketing-gastronomico-maquetacion.md` ya especifica
cómo enlazar `/bar-method/` con `/marketing-gastronomico-restaurantes/`,
reutilizando el **Patrón 10** ("Banner de marquesina", hoy usado para
"traspasos" y documentado explícitamente en `diseno-visual-tbnb.md` como
"patrón reutilizable para destacar otro servicio"). Esa propuesta ya
razona por qué descarta el Patrón 4 para un enlace de *servicio*: "está
pensado para contrastar dos situaciones de diagnóstico del cliente, no
para listar servicios". Para no contradecir esa decisión ni duplicar
mecanismos distintos sobre la misma página, alineo mi propuesta para
esta página con el mismo patrón como opción principal, y dejo el Patrón
4 solo como alternativa justificada de forma distinta (no como
"servicio", sino como "perfil de cliente").

**Propuesta principal — Patrón 10 ("Banner de marquesina"), igual que en
la página hermana.**

Justificación: esta página también es, en esencia, "otro servicio" desde
el punto de vista de `/bar-method/` (aperturas, como marketing
gastronómico, es una línea de servicio con página propia) — el mismo
criterio que ya se aplicó al proponer el banner para
`/marketing-gastronomico-restaurantes/` aplica aquí sin necesidad de
inventar un mecanismo distinto. Usar el mismo patrón para ambas páginas
nuevas evita que `/bar-method/` termine con dos soluciones visuales
distintas (una marquesina y una sección de comparativa nueva) para un
mismo tipo de necesidad (enlazar a una página de servicio nueva).

**Cómo encajaría:**
- Si `marketing-gastronomico-maquetacion.md` ya propone convertir el
  banner de traspasos en un carrusel/rotación de 2-3 mensajes, añadir
  aquí un tercer mensaje al mismo carrusel en vez de crear una franja
  nueva: algo como "¿VAS A ABRIR UN NEGOCIO? →" enlazando a
  `/abrir-restaurante-bar/` (texto exacto a validar por `web-redaccion`,
  no lo redacto yo aquí).
- Mismo tratamiento visual que el resto del banner: franja **red bar**
  (`#E94A4B`), texto en movimiento horizontal, full-width — sin inventar
  un color nuevo para este tercer mensaje.

**Alternativa — Patrón 4 ("Comparativa de situación / ¿De dónde
partimos?"), como sección nueva y adicional, sin tocar la sección ya
existente con ese mismo patrón.**

`diseno-visual-tbnb.md` describe este patrón como "reutilizable para dos
perfiles de cliente (ideal para diferenciar, por ejemplo, quien quiere
abrir vs. quien ya tiene el negocio)" — es, literalmente, el escenario de
"abrir" vs. "ya tiene el negocio en marcha". A diferencia del enlace de
`/marketing-gastronomico-restaurantes/` (que es un enlace a un
*servicio*, donde el Patrón 4 no encaja según ya razonó la maquetación
hermana), aquí el encaje sería distinto: no como lista de servicios, sino
como contraste de **situación de partida del visitante**. Si se opta por
esta vía, sería una sección nueva colocada después del checklist/CTA
(Patrón 6) y antes de "Caso de éxito" (Patrón 7), con columna izquierda
"¿Todavía no has abierto?" → `/abrir-restaurante-bar/`, y columna derecha
con un segundo perfil a definir (no necesariamente
"marketing gastronómico", para no solapar con el mecanismo ya elegido
para esa página). No reescribo el texto de "¿De dónde partimos?"
existente — sería una sección adicional, no una sustitución.

**Recomendación:** Patrón 10 (marquesina/carrusel) como opción principal,
por consistencia con la propuesta ya hecha para
`/marketing-gastronomico-restaurantes/` y para evitar que `/bar-method/`
acumule mecanismos de enlace distintos para necesidades equivalentes. El
Patrón 4 queda documentado como alternativa con encaje conceptual fuerte,
pero implica una decisión de diseño mayor (sección nueva completa) que
debería tomarse una sola vez, para ambas páginas a la vez, no de forma
independiente por cada maquetación. Confirmar con Andrea/Sergio antes de
construir, ya que implica cambios en una página que no es esta.

---

## Resumen de pendientes trasladados desde el copy (no se resuelven aquí)

Se mantienen las mismas 4 preguntas abiertas listadas en
`abrir-restaurante-bar-copy.md` (verbo de tramitación directa vs.
coordinada; dato de mercado francés; cifra verificada de Religion
Coffee/Eat My Trip; verificación de URLs internas), más las decisiones de
maquetación específicas señaladas arriba:

1. Bloque 4 (Plan Integral): Opción A (3 tarjetas, Architecture con 2
   sub-puntos) vs. Opción B (grid de 4 tarjetas) — a decidir antes de
   construir.
2. Bloque 1 y Bloque 6: confirmar contra el sitio real si existen
   bloques/secciones globales guardados en Elementor para el hero y el
   CTA de 15 min que se puedan reutilizar tal cual, en vez de
   reconstruirlos.
3. Bloque 5: confirmar si "Proyectos Destacados" ya existe como bloque
   global reutilizable — si es así, usarlo igual en esta página y en
   `/marketing-gastronomico-restaurantes/`.
4. Bloque 7: el copy enlaza a `/marketing-gastronomico/`, mientras que la
   URL confirmada en `BRIEF.md` para esa página es
   `/marketing-gastronomico-restaurantes/` — verificar y corregir antes
   de publicar (no es una decisión de maquetación, es una URL a
   confirmar).
5. Anexo: confirmar con Andrea/Sergio si el enlace desde `/bar-method/`
   hacia esta página se resuelve con el Patrón 10 (mismo mecanismo que
   ya se propuso para `/marketing-gastronomico-restaurantes/`) o con la
   alternativa de Patrón 4 — decisión que conviene tomar una sola vez
   para ambas páginas nuevas, no por separado.
6. Varios colores/fondos marcados como "a confirmar contra el kit real"
   en los bloques 2, 3, 7 y 8, por no tener un patrón exacto entre los
   11 ya documentados.

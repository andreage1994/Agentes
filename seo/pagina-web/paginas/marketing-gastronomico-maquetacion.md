# Maquetación Elementor — "Marketing gastronómico"

**Página:** `/marketing-gastronomico-restaurantes/`
**Fuentes:** `seo/pagina-web/paginas/marketing-gastronomico-copy.md` (copy final,
sin tocar una palabra) + `seo/pagina-web/seo-briefs/marketing-gastronomico.md`
(indicaciones de maquetación del SEO) + `seo/pagina-web/diseno-visual-tbnb.md`
(paleta, tipografía y los 11 patrones reales de `/bar-method/`).

**Aviso general:** todo lo de este documento es una propuesta de
especificación a partir de una grabación de pantalla y un libro de marca
para documentos internos — antes de construir nada, hay que abrir el
editor de Elementor real del sitio y comprobar si alguno de estos bloques
ya existe como sección/global guardado reutilizable (sobre todo el bloque
de "Proyectos Destacados" y el CTA de 15 minutos, que según
`diseno-visual-tbnb.md` ya viven en `/bar-method/`).

**Elementos globales de página (no se maquetan aquí):** barra de anuncio
(patrón 1), header (patrón 2) y footer (patrón 11) — se asume que son
plantillas globales de Elementor ya aplicadas en todo el sitio; confirmar
que están activadas también en esta URL nueva.

---

## Bloque 1 — H1 + intro + CTA

**Tipo de sección/widget:** Hero de una columna (o Hero split si se
reutiliza el patrón 3 de `/bar-method/`) — sección de ancho completo,
fondo sólido oscuro, título + párrafos + botón.

**Contenido exacto:**
- H1: "Marketing gastronómico para restaurantes, bares y más"
- Párrafo 1: "Tener la mejor carta del barrio no sirve de nada si la sala
  se queda vacía. En The Bar N' Bar unimos el marketing digital con los
  números reales de tu negocio: el mismo equipo que monta tu campaña es
  el que entiende de márgenes, ticket medio y ocupación. Así tu
  comunicación deja de ser un gasto a ciegas y se convierte en algo que
  se puede medir."
- Párrafo 2: "No hacemos marketing de adorno ni campañas desconectadas de
  la realidad de tu local. Diseñamos e implementamos estrategias de
  marketing gastronómico con un objetivo muy concreto: con esto llenamos
  mesas, no publicamos por publicar. Subimos el ticket medio, sí — pero
  sobre todo conseguimos que la gente se acuerde de ti a la hora de
  decidir dónde comer."
- Botón: "QUIERO LLENAR MI RESTAURANTE" → enlace a formulario de contacto
  / agenda de 15 min (URL exacta a confirmar — el copy no la fija).

**Notas de diseño:**
- Fondo **negro** (`#0B0B0B` aprox.), igual que el hero de `/bar-method/`
  (patrón 3).
- H1 en blanco; párrafos en gris claro (mismo tratamiento que el hero de
  referencia).
- Botón en **red bar** (`#E94A4B`) — es el color confirmado para CTAs
  principales en toda la web.
- Título en tipografía de titulares (peso bold/black, según
  `diseno-visual-tbnb.md`); el nombre exacto de la fuente ("Epilogue")
  no está confirmado en ese documento — verificar contra el kit real de
  Elementon antes de darlo por definitivo. Cuerpo en la tipografía
  regular sans-serif del sitio ("Helvetica Neue" es la propuesta del
  equipo, también pendiente de confirmar contra el kit).
- **Decisión a tomar:** el hero de `/bar-method/` incluye a la derecha
  una tarjeta-carrusel de "CASO DE ÉXITO". Esta página ya tiene su propio
  bloque de proyectos destacados más abajo (Bloque 5) — para no duplicar
  el mismo contenido dos veces en la misma página, se sugiere una versión
  **simplificada** del hero (columna única, sin la tarjeta de caso de
  éxito) o, si se reutiliza el split completo, sustituir la tarjeta
  derecha por una imagen genérica de local/servicio en marcha. A
  confirmar cuál de las dos variantes ya existe como plantilla en el
  sitio.

**Recurso visual sugerido:** si se opta por el hero split, una foto real
de sala llena o servicio en marcha (no stock genérico). Alt-text
sugerido: "Sala de restaurante llena durante el servicio — marketing
gastronómico The Bar N' Bar" (ajustar la descripción a la foto real que
se use).

---

## Bloque 2 — H2 "Especialistas en marketing y publicidad que conocen la hostelería desde dentro"

**Tipo de sección/widget:** Icon List / 3 Icon Box en columna o fila
(icono + texto). No hay un patrón idéntico entre los 11 documentados para
una lista simple de 3 puntos en fondo claro — el más cercano es el
"bloque de confianza/checklist" (patrón 6), que en `/bar-method/` va
sobre fondo negro. Aquí se sugiere fondo **blanco o gris claro** para
alternar con el negro del Bloque 1, siguiendo la regla general de "un
color de fondo dominante por sección, alternando con blanco".

**Contenido exacto:**
- H2: "Especialistas en marketing y publicidad que conocen la hostelería
  desde dentro"
- Ítem 1: "**Protección del margen real** — Priorizamos los platos y las
  franjas horarias que de verdad te dejan margen, no solo los que quedan
  bonitos en redes."
- Ítem 2: "**La campaña no rompe el servicio** — Una promo que llena la
  sala un jueves y deja a la cocina ahogada no es un éxito, es un
  problema disfrazado. Diseñamos la publicidad al ritmo que tu cocina
  puede sacar platos, no al revés."
- Ítem 3: "**Lo que se promete en redes se cumple en la mesa** — Si la
  foto de Instagram promete algo que el plato no cumple, el marketing no
  ha servido de nada. Conectamos lo que se ve fuera con lo que pasa
  dentro."

**Notas de diseño:**
- Fondo gris claro (`#EDEDED`) o blanco (`#FFFFFF`) — ambos están en la
  paleta confirmada como fondos de sección alterna/tarjetas neutras.
- Icono de acento en **red bar**, coherente con el resto del sitio.
- H2 en tipografía de titular; el texto en negrita al inicio de cada
  ítem (ya viene así en el copy) debe respetarse tal cual en el campo de
  texto del widget, no separarlo en un campo de "título de icono" +
  "descripción" si eso obliga a partir la frase de forma distinta a como
  está redactada.

**Recurso visual sugerido:** 3 iconos simples (línea o outline) que
representen: margen/dinero, cocina/servicio, y confianza/coherencia de
marca. A confirmar contra la librería de iconos ya usada en
`/bar-method/` para mantener el mismo estilo de trazo.

---

## Bloque 3 — H2 "Un plan de marketing integral adaptado a hostelería"

**Tipo de sección/widget:** Grid de 4 tarjetas (Info Box / Icon Box),
numeradas 1-4, en 2x2 o 4 en fila según el ancho.

**Nota importante de diseño:** el patrón más parecido de los 11
documentados es el patrón 5 ("3 tarjetas de color" Breakdown/rojo,
Architecture/naranja, Run/amarillo, tipo nota adhesiva). **No se
recomienda reutilizar exactamente ese estilo ni esos 3 colores** para
este bloque: esos colores y esa forma están asociados en todo el sitio a
las siglas del BAR Method (B-A-R), y este bloque no tiene relación con
esa metodología — reutilizarlos generaría confusión de marca (el
visitante podría pensar que estos 4 puntos son parte del BAR Method).
Se sugiere una versión neutra: 4 tarjetas con fondo blanco o gris claro,
número grande como elemento decorativo, sin los colores reservados al
método. A confirmar contra el kit real si existe ya un estilo de tarjeta
neutra numerada en el sitio.

**Contenido exacto:**
- H2: "Un plan de marketing integral adaptado a hostelería"
- Tarjeta 1 — H3: "1. Posicionamiento de marca, branding y concepto" —
  Texto: "El marketing no empieza en el anuncio: empieza en si tu marca
  cuenta una historia que se sostiene. Trabajamos el nombre, el ambiente
  y la carta como una misma pieza, porque un logo bonito con una carta
  que no cuenta nada se nota a la legua."
- Tarjeta 2 — H3: "2. Publicidad y captación de clientes" — Texto:
  "Montamos campañas en Meta Ads y Google Ads pensadas para que la gente
  reserve, llame o venga a tu evento — no para acumular "me gusta". Y si
  tu local todavía no está listo para recibir más gente porque la
  operativa no aguanta, te lo decimos antes de encender un solo anuncio."
- Tarjeta 3 — H3: "3. Redes sociales y producción de contenido" — Texto:
  "Nada de vídeos genéricos de manual. Mostramos lo que de verdad pasa en
  tu local: el proceso, la cocina, el equipo. Gestionamos tus perfiles y
  buscamos la complicidad con prescriptores locales que ya conectan con
  tu público."
- Tarjeta 4 — H3: "4. SEO local, GEO (visibilidad en IA) y reputación
  digital" — Texto: "Trabajamos tu ficha de Google, tu posicionamiento en
  búsquedas locales y tu reputación online. Y estamos construyendo algo
  más nuevo: que cuando alguien le pregunte a ChatGPT o a Gemini dónde
  cenar, tu nombre tenga opciones de salir. Es terreno todavía joven — te
  contamos siempre en qué punto está, sin venderte magia de IA que hoy no
  existe."

**Notas de diseño:**
- Fondo de sección: blanco o gris claro (alternando con el bloque
  anterior si ese usó gris, este va en blanco, o viceversa).
- H3 en tipografía de titular, cuerpo en tipografía regular.
- Icono por tarjeta en red bar o en negro, no en los colores B-A-R
  (ver nota arriba).

**Recurso visual sugerido:** 4 iconos temáticos — identidad de marca,
megáfono/anuncio, cámara/contenido, y lupa/IA — a confirmar estilo
contra la librería de iconos del sitio.

**Nota para `web-redaccion` (no se toca aquí):** la tarjeta 3 usa el
verbo "Mostramos" y "Gestionamos" de forma deliberadamente ambigua sobre
si la producción es interna o con colaboradores externos (ver nota de
trazabilidad 1 del copy) — esto no afecta a la maquetación, pero si más
adelante se decide mostrar un logo o crédito de un partner externo en
esta tarjeta, habrá que revisar el texto con `web-redaccion` antes.

---

## Bloque 4 — H2 "Estrategias de marketing a medida para activar tus ventas y crecer"

**Tipo de sección/widget:** Icon List / 3 Icon Box, mismo tratamiento que
el Bloque 2, para mantener coherencia entre los dos bloques de "lista de
3 puntos" de la página.

**Contenido exacto:**
- H2: "Estrategias de marketing a medida para activar tus ventas y
  crecer"
- Ítem 1: "**Lanzamientos y reaperturas** — Generamos expectación antes
  de abrir la puerta, para que el primer servicio no empiece de cero."
- Ítem 2: "**El día de la semana que no levanta cabeza** — Todo local
  tiene una franja floja. Trabajamos acciones concretas para esos turnos,
  en vez de dejarlos a su suerte."
- Ítem 3: "**Fidelización y recurrencia** — Montamos la base de datos y
  los canales de contacto para que el cliente que vino una vez tenga un
  motivo real para volver."

**Notas de diseño:**
- Fondo alterno respecto al Bloque 3 (si Bloque 3 es blanco, este va gris
  claro `#EDEDED`, o viceversa) para mantener el patrón de alternancia de
  toda la página.
- Icono de acento en red bar.

**Recurso visual sugerido:** 3 iconos — cohete/lanzamiento,
calendario/día flojo, y corazón o repetición/fidelización.

---

## Bloque 5 — H2 "No lo decimos, lo demostramos" (Proyectos Destacados)

**Tipo de sección/widget:** el copy y el brief SEO indican explícitamente
"bloque visual de Proyectos Destacados ... sin cambios", lo que sugiere
que **ya existe un bloque reutilizable** en el sitio (usado también en la
página de aperturas). Antes de construir nada nuevo, comprobar la
librería de Elementor por un bloque guardado de "Proyectos Destacados".
Si no existe, el tipo más adecuado es una galería/grid de 2 Image Box (o
Portfolio widget), cada una enlazando a su ficha de proyecto o al listado
general.

**Contenido exacto:**
- H2: "No lo decimos, lo demostramos"
- Párrafo: "Religion Coffee y Eat My Trip son proyectos reales en los que
  hemos puesto las manos — no casos de estudio sacados de una plantilla.
  Así trabajamos el marketing cuando lo unimos a la consultoría de
  negocio."
- Tarjetas: Religion Coffee, Eat My Trip (imagen + nombre, según el
  bloque visual ya existente).
- Enlace/CTA del bloque: "Ver proyectos →" enlazando a `/proyectos/`.

**Notas de diseño:**
- **No usar el formato de "cifras grandes destacadas" del patrón 7**
  ("Caso de éxito", p. ej. "+100.000 € de facturación en 6 meses"): el
  copy final deja este bloque deliberadamente sin cifra ni campaña
  concreta (ver nota de trazabilidad 3 del copy — "a la espera de que se
  confirme si hay algo citable"). Usar el formato más simple de tarjetas
  de proyecto, no el de caso de éxito con estadística.
- Color de fondo: a confirmar contra el bloque ya existente en el sitio
  (si se reutiliza tal cual, hereda su propio color; si se construye
  nuevo, blanco o gris claro es lo más neutro según la paleta
  documentada).

**Recurso visual sugerido:** captura o foto real de Religion Coffee y de
Eat My Trip (ya tienen ficha propia en `/en/religion-coffee/` y
`/en/eat-my-trip/` según `BRIEF.md` — reutilizar esas imágenes si ya
existen). Alt-text sugerido: "Proyecto Religion Coffee, cliente de The
Bar N' Bar" / "Proyecto Eat My Trip, cliente de The Bar N' Bar".

---

## Bloque 6 — H2 "¿Tienes problemas para llenar tu local o quieres crecer? Hablemos de números"

**Tipo de sección/widget:** CTA banner. Este es el CTA de 15 minutos que
`diseno-visual-tbnb.md` describe como "estrella polar" del sitio, ya
operativo en `/bar-method/` (patrón 9, fondo amarillo/lemon icon). Se
recomienda **reutilizar el bloque/sección global ya construido en
Elementor** para este CTA en vez de reconstruirlo desde cero, para
garantizar que el mensaje y el comportamiento (enlace, tracking, etc.)
sean exactamente los mismos que en el resto del sitio.

**Contenido exacto:**
- H2: "¿Tienes problemas para llenar tu local o quieres crecer? Hablemos
  de números"
- Párrafo: "Si las mesas no se llenan como deberían o quieres dar el
  siguiente paso, hablemos con números encima de la mesa, no con
  promesas. Una conversación de 15 minutos, sin compromiso, para entender
  dónde estás, qué te está frenando y si tiene sentido que trabajemos
  juntos. Si creemos que podemos ayudarte, te decimos cómo. Y si no, te
  lo decimos también."
- Botón: "AGENDAR REUNIÓN GRATUITA DE 15 MINUTOS"

**Notas de diseño:**
- Fondo **lemon icon** (`#FCE312`), igual que el patrón 9 de
  `/bar-method/`.
- Color del botón: el patrón de referencia no especifica el color exacto
  del botón "AGENDAR CITA" sobre fondo amarillo — a confirmar contra el
  kit real (candidatos razonables por contraste: negro o red bar).
- Si se reutiliza el bloque global, el texto de botón real en
  `/bar-method/` es "AGENDAR CITA"; el brief SEO propone "AGENDAR REUNIÓN
  GRATUITA DE 15 MINUTOS" para esta página nueva. Ambas variantes están
  confirmadas como aceptables por `diseno-visual-tbnb.md" — mantener la
  que ya trae el copy final ("AGENDAR REUNIÓN GRATUITA DE 15 MINUTOS")
  salvo que Andrea/Sergio prefieran unificar el texto de botón en todo
  el sitio.

**Recurso visual sugerido:** si se construye nueva (no reutilizada), el
elemento gráfico tipo sticker "HELLO" / forma orgánica que usa el patrón
9 en `/bar-method/`, para mantener coherencia visual del CTA en todo el
sitio.

---

## Bloque 7 — H2 "¿Solo necesitas ayuda en un área? Servicios a la carta para tu negocio"

**Tipo de sección/widget:** Grid de 4 tarjetas (Info Box / Image Box),
como indica explícitamente el brief SEO ("grid de 4 tarjetas").

**Contenido exacto:**
- H2: "¿Solo necesitas ayuda en un área? Servicios a la carta para tu
  negocio"
- Tarjeta 1 — Título: "Diseño de Carta y Gastronomía" → enlace a
  `/consultoria-gastronomica/`. Texto: "Si el problema empieza en la
  carta, aquí es donde se arregla: escandallos, márgenes y una propuesta
  que cuente algo."
- Tarjeta 2 — Título: "Aperturas y Proyectos" → enlace a
  `/abrir-restaurante-bar/`. Texto: "¿Vas a abrir o a reformar? Te
  acompañamos desde el concepto hasta la primera comanda."
- Tarjeta 3 — Título: "Selección y Equipo" → enlace a
  `/servicios/consultoria-rrhh-hosteleria/`. Texto: "Un buen marketing
  lleva gente a la puerta. Que se quede depende del equipo que la reciba
  dentro."
- Tarjeta 4 — Título: "Digitalización y TPV" → enlace a
  `/servicios/consultoria-tecnologica-hosteleria/`. Texto: "TPV,
  reservas, comandas: que la tecnología trabaje para ti, no al revés."

**Notas de diseño:**
- Fondo blanco o gris claro, alternando con el bloque anterior (CTA
  amarillo del Bloque 6).
- Icono o pequeña imagen por tarjeta — a definir un estilo consistente
  (todas icono, o todas foto) para no mezclar dos lenguajes visuales en
  el mismo grid.

**Recurso visual sugerido:** 4 iconos temáticos — carta/menú, obra/llave
(apertura), personas/equipo, y pantalla/TPV.

**Pendiente (nota de trazabilidad 4 del copy):** verificar antes de
publicar que las 4 URLs de destino existen tal cual en el sitio en vivo,
sobre todo `/servicios/consultoria-rrhh-hosteleria/` y
`/servicios/consultoria-tecnologica-hosteleria/` que tienen un prefijo
`/servicios/` distinto al de las otras páginas de este proyecto.

---

## Bloque 8 — H2 "Llevamos el marketing gastronómico donde está el negocio"

**Tipo de sección/widget:** el brief SEO lo marca como "bloque de
enlazado a silos locales" — se sugiere un bloque simple de texto +
Icon List de enlaces (no necesita el formato de tarjeta grande de los
Bloques 5 o 7), ya que es una lista corta de ciudades/enlaces.

**Contenido exacto:**
- H2: "Llevamos el marketing gastronómico donde está el negocio"
- Párrafo: "No estamos "en todas partes" — eso nos sonaría a mentira.
  Tenemos un sitio real en Gràcia, Barcelona, y desde ahí trabajamos
  también con Madrid. ¿Tu negocio está en otra ciudad? Hablamos igual,
  por videollamada."
- Enlace 1: "Marketing gastronómico en Barcelona" →
  `/consultoria-hosteleria-barcelona/`
- Enlace 2: "Marketing gastronómico en Madrid" →
  `/consultoria-hosteleria-madrid/`
- *(placeholder del copy: "Si se crean el resto de páginas, añadir
  'Marketing gastronómico en XXXX' — sin cambios" — no maquetar todavía,
  dejar el grid/lista preparada para añadir ítems futuros sin rehacer la
  sección)*
- Enlace 3: "¿En otro punto del mapa? Hablemos." → `/contacto/`

**Notas de diseño:**
- Fondo blanco, sección de cierre antes del footer.
- Los enlaces de ciudad en formato de lista o de mini-tarjeta con icono
  de ubicación (pin) en red bar.

**Recurso visual sugerido:** icono de ubicación/pin para cada enlace de
ciudad; no hace falta foto.

**Pendiente (nota de trazabilidad 4 del copy):** verificar que
`/consultoria-hosteleria-barcelona/` y `/consultoria-hosteleria-madrid/`
existen ya en el sitio en vivo con esa URL exacta antes de enlazar.

---

## Propuesta de enlace desde `/bar-method/` hacia esta página

`BRIEF.md` pide proponer dónde y cómo encajaría, dentro de los 11
patrones ya documentados de `/bar-method/`, un enlace o tarjeta hacia
esta página nueva (y, por separado, hacia `/abrir-restaurante-bar/`).

**Propuesta: reutilizar el patrón 10 — banner de marquesina.**

`diseno-visual-tbnb.md` describe este patrón así: "Banner de marquesina
(franja roja con texto en movimiento horizontal) para una llamada a la
acción secundaria (en este caso, traspasos) — **patrón reutilizable para
destacar otro servicio**." Es el único de los 11 patrones que el propio
documento marca explícitamente como pensado para este uso exacto
(promocionar otro servicio desde `/bar-method/`), así que no hace falta
inventar un patrón nuevo.

**Cómo encajaría:**
- Añadir un segundo banner de marquesina (o convertir el banner existente
  en un carrusel/rotación de 2-3 mensajes: traspasos, marketing
  gastronómico, aperturas) justo donde ya vive el banner de traspasos
  (patrón 10, después del bloque de "Quiénes somos" y antes del footer).
- Texto sugerido para el banner (a validar por `web-redaccion`, no lo
  redacto yo aquí): un mensaje corto tipo "MARKETING GASTRONÓMICO →" que
  enlace a `/marketing-gastronomico-restaurantes/`.
- Mismo tratamiento visual que el banner de traspasos: franja **red bar**
  (`#E94A4B`), texto en movimiento horizontal, full-width.

**Por qué esta opción y no otra:**
- El patrón 4 ("comparativa de situación", 2 columnas) está pensado para
  contrastar dos *situaciones de diagnóstico* del cliente, no para listar
  servicios — forzar un enlace de servicio ahí rompería su lógica.
- El patrón 5 (tarjetas BAR method) está reservado a las siglas
  Breakdown/Architecture/Run — añadir una cuarta tarjeta de "marketing"
  generaría la misma confusión de marca señalada en el Bloque 3 de esta
  página.
- El patrón 7 (caso de éxito) y el patrón 9 (CTA final) ya tienen un
  propósito fijo (mostrar un resultado concreto / cerrar con el CTA de 15
  minutos) — añadir un enlace de servicio ahí los sobrecargaría.
- El patrón 10 es, según la propia documentación, el único diseñado para
  "destacar otro servicio" — es la opción de menor riesgo y la que ya
  tiene precedente de uso real en el sitio.

**A confirmar antes de construir:** si en el sitio real ya existe algún
mecanismo de rotación/carrusel para ese banner (para alternar entre
"traspasos" y "marketing gastronómico" sin necesitar dos franjas fijas
apiladas), revisarlo en el editor de Elementor antes de añadir una
segunda franja fija.

---

## Notas generales pendientes (no resueltas por esta maquetación)

1. **Tipografía exacta:** `diseno-visual-tbnb.md` describe el estilo de
   la tipografía (peso, mayúsculas en eyebrows, etc.) pero no confirma
   nombres de fuente. "Epilogue" (títulos) y "Helvetica Neue" (cuerpo) se
   usan aquí como sugerencia de partida — confirmar contra el kit real de
   Elementon antes de darlos por definitivos.
2. **Colores de botón sobre fondos de color** (p. ej. botón del CTA
   amarillo del Bloque 6) no están especificados con hex exacto en
   `diseno-visual-tbnb.md` — a confirmar contra el kit real.
3. **Verificación de URLs internas** (Bloques 7 y 8, y el botón del
   Bloque 1): pendiente desde el copy final (nota de trazabilidad 4) y
   desde `BRIEF.md` — ninguna se ha confirmado como existente en el sitio
   en vivo con esa URL exacta.
4. **Bloque de Proyectos Destacados (Bloque 5) y CTA de 15 minutos
   (Bloque 6):** revisar primero la librería de Elementor por si ya
   existen como secciones globales/guardadas reutilizables, antes de
   reconstruirlos desde cero.
</content>

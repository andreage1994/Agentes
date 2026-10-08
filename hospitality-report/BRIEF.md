# Hospitality Report — Brief del proyecto

**Qué es:** una publicación editorial semestral de The Bar N' Bar sobre tendencias,
datos y movimientos que están transformando la hostelería. No es un informe de
consultoría al uso: es una pieza de posicionamiento de marca.

**Objetivo:** posicionar a TBNB como marca de autoridad en el sector, aportar valor
real (no repetir lo que ya dicen otros informes) y ofrecer una visión propia y nueva
del mercado.

**Origen:** el proceso ya existía en Google Drive antes de este proyecto en GitHub
(carpeta "7. I+D"): una plantilla de 11 secciones y una matriz temática viva donde se
registran fuentes y se detectan patrones/tensiones. Este proyecto lo trae aquí para
seguir nutriéndolo con el equipo de especialistas de Claude Code.

## Tono de marca para este proyecto

**Autoridad, investigadores, reveladores del sector.** No sonamos a consultora
genérica ni a agregador de noticias. Reglas de tono, extraídas de la propia plantilla
ya existente:

- Frases cortas y declarativas. Ejemplo real de la plantilla: *"Antes de cambiar los
  restaurantes, cambian las personas."*
- Afirmamos, no especulamos con hedging vacío. Ejemplo: *"No queremos llenar páginas
  de datos. Queremos encontrar los datos que cuentan una historia."*
- Cada dato lleva un "TBNB TAKE" — no basta con citar la fuente, hay que decir qué
  pensamos nosotros de ella.
- Distinguimos siempre **TREND** (cambio estructural) de **MOMENT** (pasajero) de
  **NOISE** (se habla mucho, pero no significa tanto) — nunca presentamos ruido como
  tendencia.
- Nunca inventamos datos ni cifras. Toda afirmación de mercado lleva fuente citada.
- Revelamos: conectamos puntos entre fuentes distintas que nadie más ha conectado
  (ver "Backlog de síntesis" y "Tensiones y contradicciones" en la matriz temática) —
  eso es lo que nos distingue de simplemente resumir informes ajenos.

## Cadencia

Semestral (H1 / H2), según el departamento de Marketing y Comunicación de TBNB
(investigación, producción y distribución semestral), con implicación de I+D en la
parte de investigación.

## El equipo

Cinco especialistas (`.claude/agents/`), cada uno con una fase del proceso:

1. **`hospitality-investigador`** — alimenta la matriz temática con fuentes nuevas
   (usa la lista de medios de referencia en `fuentes-inspo.md`), detecta patrones y
   tensiones entre fuentes. Solo investiga, no redacta ni decide postura editorial.
2. **`hospitality-estrategia`** — decide qué tendencias importan de verdad para el
   posicionamiento de TBNB, define el ángulo "TBNB TAKE" de cada sección, elige la
   pregunta de "ONE QUESTION", y vigila que el reporte aporte una visión propia y no
   repita lo que ya dicen las fuentes originales.
3. **`hospitality-innovacion`** — reta los ángulos ya decididos por estrategia (y los
   borradores de redacción) para que no se queden en la lectura segura: busca
   conexiones cruzadas con otras industrias, propone hipótesis propias arriesgadas y
   afila la pregunta de ONE QUESTION si es demasiado fácil. No decide qué entra ni
   escribe el texto final — presiona la originalidad de lo que ya existe.
4. **`hospitality-redaccion`** — escribe el contenido final de cada sección con el
   tono de marca definido arriba, a partir del trabajo de investigación, estrategia
   e innovación.
5. **`hospitality-marketing`** — convierte el reporte terminado en un plan de
   distribución: qué se publica en RRSS, email marketing, web, y en qué orden, para
   maximizar el posicionamiento de marca del lanzamiento.

**Por qué un cuarto rol además de los tres que pediste originalmente:** sin
investigación propia y rigurosa, un reporte "de autoridad" se cae — sería solo
opinión sin respaldo. La matriz temática ya existente demuestra que este equipo
cuida mucho el sourcing (cada dato con fecha, fuente y fecha de publicación);
separar la investigación de la redacción y la estrategia asegura que ese rigor no
se pierda al meter velocidad de producción.

**Por qué un quinto rol de innovación (pedido por Andrea, 2026-10-02):**
`hospitality-estrategia` ya comprueba que un ángulo no repita literalmente a otros
informes del sector — pero "no es una copia" y "es realmente interesante" son dos
preguntas distintas. Sin un rol dedicado a presionar específicamente por
originalidad, el riesgo real en un reporte producido con velocidad es que cada
sección sea correcta, bien sourceada y aun así previsible. Este rol existe para
que esa pregunta se haga siempre, en vez de depender de que estrategia o redacción
se la hagan a sí mismos de pasada.

## Cómo está organizada esta carpeta

- `BRIEF.md` — este documento.
- `plantilla-indice.md` — estructura fija de las 11 secciones del reporte, para
  reutilizar en cada edición.
- `matriz-tematica.md` — documento vivo de fuentes clasificadas (traído de Drive).
- `fuentes-inspo.md` — medios y fuentes de referencia para la investigación.
- `estado.md` — en qué fase va la edición en curso.
- `ediciones/<año>-<H1|H2>/` — el reporte redactado de cada edición semestral.
- `retroplanning-2026-h2.md` — calendario operativo hacia atrás desde el
  lanzamiento de la edición H2 2026: qué falta entre el texto ya redactado y
  el PDF publicado (diseño, gate de email, distribución), y quién lo tiene
  asignado hoy.

**Nota para Andrea:** he traído la matriz temática y la plantilla desde Drive como
punto de partida. A partir de ahora, ¿prefieres que este repositorio sea la versión
"viva" que vamos actualizando (y Drive quede como archivo), o seguimos actualizando
ambos sitios en paralelo? Dímelo para dejarlo anotado aquí.

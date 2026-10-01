# Revisión de índices del BAR Method — octubre 2026

**Pedido por Andrea, 2026-10-01.** Fuente: `BAR_METHOD_2026_1.xlsx`, hoja
`Cronograma_BAR Method`, columna "CONTENIDO DOCUMENTOS ENTREGABLES". Objetivo:
comprobar que ningún índice se repite en información y que el conjunto tiene
coherencia interna.

## Resumen del sistema (21 entregables + 8 servicios complementarios sin índice)

**BREAKDOWN** (diagnóstico, 7): Experiencia y hospitalidad · Diagnóstico de
concepto gastronómico · Análisis operativo y de equipo · Diagnóstico de
rentabilidad y modelo de negocio · Cumplimiento documental y normativo ·
Estudio de viabilidad de concepto y mercado · Análisis de ubicación y
viabilidad.

**ARCHITECTURE** (diseño, 7): Concepto y narrativa de marca · Desarrollo
gastronómico · Proyección financiera y viabilidad de negocio · Estrategia y
modelo operativo · Estrategia de espacio · Estrategia de marca y
comunicación · Hospitalidad y cultura de servicio.

**RUN** (implementación, 7): Operations controller · Tecnología y sistemas
operativos · Optimización operativa y rentabilidad · Implementación operativa
y SOPs · Cumplimiento operativo y normativo · Implementación gastronómica ·
Construcción de equipo.

**Servicios Complementarios** (8, con partners): ninguno tiene índice
definido todavía (fiscal/financiera, laboral/administrativa, marketing
digital, branding/dirección creativa, oportunidades y traspasos,
inteligencia de negocio, licencias y viabilidad, interiorismo). No es un
error de este documento — simplemente no hay contenido que revisar ahí
todavía.

## Conclusión general

**El sistema es coherente de fondo.** La lógica Breakdown → Architecture →
Run funciona como lo que debería ser: diagnosticar el estado actual → diseñar
el estado futuro → implementarlo y monitorizarlo. No encontré ningún
documento que sea un duplicado literal de otro. Lo que sí hay son temas que
cruzan las tres fases con vocabulario muy parecido, lo cual es normal (es el
mismo negocio) pero tiene puntos donde conviene aclarar el límite entre
documentos — tanto para que el equipo no se pise al redactar como para poder
explicarle a un cliente por qué no le estáis cobrando dos veces por "lo
mismo".

## Hallazgos

### 1. Error de contenido real: línea pegada por error (fila 8)

La fila 8, **"Estudio de Viabilidad de Concepto y Mercado"** (BREAKDOWN),
empieza su índice con la línea:

> "Auditoria Cumplimiento Normativo x TBNB"

...antes de "Resumen ejecutivo" y todo el contenido real de ese documento
(market landscape, competencia, consumer insights...). Esa línea es el
nombre del archivo plantilla que cierra el índice de la fila anterior (7,
Cumplimiento documental y normativo). Parece un corta-y-pega que se quedó
pegado al principio del índice equivocado. **Recomendación: borrar esa línea
suelta en la fila 8 del Excel** — no aporta nada a ese documento y genera
confusión si alguien lo usa como plantilla.

### 2. Mismo archivo de referencia en dos fases (filas 7 y 23)

El archivo **"Auditoria Cumplimiento Normativo x TBNB"** aparece como
documento de referencia tanto en la fila 7 (BREAKDOWN — Cumplimiento
documental y normativo) como en la fila 23 (RUN — Cumplimiento operativo y
normativo). Puede ser intencional (reutilizáis la misma plantilla de
auditoría en el diagnóstico inicial y en el seguimiento continuo), pero tal
y como está en el índice no queda explícito. Si es intencional, merece una
nota en ambos índices tipo "mismo formato de auditoría que en Breakdown,
aplicado aquí como seguimiento periódico" — así un cliente que reciba el
mismo nombre de archivo dos veces en su proyecto entiende por qué, y el
equipo no se pregunta si es un error.

### 3. El tema que más se repite en vocabulario: Menu Engineering / pricing / rentabilidad de carta

Aparece en tres fases distintas:
- **Fila 4** (BREAKDOWN, Diagnóstico de concepto gastronómico) → sección 4
  "Rendimiento de la oferta": Pricing, Menu Engineering, Rentabilidad,
  Escandallos.
- **Fila 12** (ARCHITECTURE, Desarrollo gastronómico) → "Arquitectura de la
  carta", "Estrategia de precio", "Estrategia económica".
- **Fila 21** (RUN, Optimización operativa y rentabilidad) → el documento
  entero se titula internamente **"MENU ENGINEERING ANALYSIS"**, con matriz
  Stars/Puzzles/Plow Horses/Dogs y estrategia de pricing propia.

Esto no es duplicación real: la fila 4 diagnostica la carta **que ya existe**,
la fila 12 **diseña** la carta nueva dentro del concepto de Architecture, y
la fila 21 **vuelve a analizar** la carta ya en marcha, de forma periódica,
una vez el negocio opera. Es exactamente la lógica Breakdown → Architecture
→ Run aplicada a un mismo tema. El riesgo no es de contenido sino de
percepción: es el tema con el vocabulario más repetido letra por letra
("Menu Engineering", "Pricing", "Escandallos") de los 21 documentos, así que
es el más fácil de que un cliente (o alguien nuevo en el equipo) pregunte
"¿esto no lo habíamos hecho ya?". Vale la pena que cada entregable que toque
este tema diga explícitamente, en una línea, qué momento del negocio está
mirando (carta actual / carta nueva diseñada / carta ya en marcha).

### 4. "Customer journey" mapeado cuatro veces en Architecture, cada vez desde un ángulo distinto

- Fila 11 (Concepto y narrativa de marca): "Recorridos de cliente" dentro de
  la Arquitectura experiencial.
- Fila 14 (Estrategia y modelo operativo): "Customer journey operativo" —
  touchpoints, momentos de verdad, ritmo de servicio.
- Fila 15 (Estrategia de espacio): "Customer journey espacial" — llegada,
  recepción, circulación, baños, salida.
- Fila 16 (Estrategia de marca y comunicación): "Customer communication
  journey" — descubrimiento, consideración, reserva, visita, recompra.

Cuatro documentos de Architecture mapean el mismo recorrido del cliente,
cada uno desde su disciplina (marca, operación, espacio, comunicación). Tiene
sentido que cada especialista lo mire desde su ángulo — pero tal y como está
el índice, nada indica que son lecturas del mismo recorrido y no cuatro
ejercicios independientes. Dos opciones, no excluyentes: (a) que el
"recorrido de cliente" general se fije una vez (en el documento de Concepto y
narrativa, que es el primero cronológicamente) y los otros tres lo citen y
lo amplíen en su disciplina en vez de re-derivarlo desde cero; o (b) dejarlo
como está pero añadir en cada uno una línea tipo "ver journey general en
Concepto y narrativa de marca, sección X" para que se perciba como un
sistema y no como trabajo repetido.

### 5. La dependencia real: "Concepto y narrativa de marca" (fila 11) no está marcada como fundacional, pero lo es

Esto conecta directo con el problema operativo que planteas más abajo. El
índice de la fila 11 no lo dice explícitamente, pero si se lee el contenido
de las filas 12, 14, 15 y 16, **los cuatro asumen que el concepto ya está
decidido**:
- Fila 12 (Desarrollo gastronómico) parte de un "posicionamiento
  gastronómico" y una "arquitectura global" que vienen de la Plataforma de
  Marca de la fila 11.
- Fila 15 (Estrategia de espacio) parte de "el rol del espacio dentro del
  concepto".
- Fila 16 (Estrategia de marca y comunicación) parte del "territorio
  comunicativo" y la "voz" de marca, que son una extensión directa de la
  Plataforma de Marca (Propósito/Visión/Misión/Valores) que define la fila
  11.
- Incluso la fila 13 (Proyección financiera) asume un modelo de negocio ya
  definido por el concepto.

Es decir: **Concepto y narrativa de marca no es "un documento más" de
Architecture, es la base de la que dependen al menos otros cuatro.** Eso es
justo lo que hace tan caro un cambio de idea a mitad de camino: no es solo
rehacer un documento, es que cualquier trabajo ya empezado en los otros
cuatro (si se empezó en paralelo o justo después) puede quedar construido
sobre una base que ya no existe. El índice actual no refleja esta
dependencia en ningún sitio — sería razonable que el índice de la fila 11
cerrara con una nota tipo "documento base: 12, 14, 15 y 16 parten de la
Plataforma de Marca y la Dirección Estratégica definidas aquí", para que
quede escrito en el sistema y no solo en la cabeza del equipo.

### Lo que no es un problema

- **"Resumen ejecutivo" al abrir y "Roadmap / Plan de acción / Próximos
  pasos" al cerrar** aparecen en casi todos los 21 documentos. No es
  contenido repetido, es una estructura de casa consistente — está bien que
  se mantenga así.
- Rentabilidad (fila 6, diagnóstico actual) vs. Proyección financiera (fila
  13, proyección futura) vs. Optimización operativa (fila 21, seguimiento):
  mismo patrón Breakdown/Architecture/Run que el punto 3, coherente.
- Operación (fila 5, diagnóstico) vs. Estrategia y modelo operativo (fila
  14, diseño) vs. Operations controller + Implementación operativa y SOPs
  (filas 19 y 22, ejecución y seguimiento): mismo patrón, coherente. Única
  nota menor: la fila 19 (Operations controller) mide "Cumplimiento de
  estándares — SOPs" que la fila 22 (Implementación operativa y SOPs) es la
  que los crea — conviene que 22 esté hecho (o al menos avanzado) antes de
  que 19 empiece a medir, si no hay SOPs todavía contra qué medir.
- Equipo: diagnóstico (fila 5) → diseño de organigrama/roles (fila 14,
  sección 6) → contratación (fila 25, Construcción de equipo): coherente,
  sin solape de contenido.

---

## Sobre el problema de Concepto y Narrativa de Marca

El hallazgo 5 de arriba es la raíz del problema que planteas: no es que el
equipo no sepa reaccionar cuando un cliente cambia de idea, es que el
sistema no tiene un punto marcado donde esa idea queda "cerrada" antes de
que el resto de Architecture empiece a construir sobre ella. Mientras no
exista ese punto, cualquier cambio del cliente es, por definición, "a mitad
de desarrollo" — porque nunca hubo un momento formal de "hasta aquí hemos
cerrado, a partir de aquí construimos".

**No creo que la solución sea elegir entre tu disyuntiva (avisar al cliente
de que el riesgo es suyo vs. seguir absorbiendo el tiempo).** Las dos
opciones, solas, tienen el mismo problema de fondo: ninguna de las dos fija
el momento en el que el concepto se da por cerrado, así que en ambas el
cliente puede seguir cambiando de idea indefinidamente y vosotros seguís sin
saber si estáis "dentro de lo pactado" o no. Decir "el riesgo es tuyo" sin
haber definido cuándo empieza ese riesgo es difícil de sostener con un
cliente real y choca con el tono honesto y no agresivo con el que trabajáis.

**Propuesta: un gate formal de aprobación del concepto, dentro del propio
documento de Concepto y Narrativa de Marca, antes de pasar a las fases que
dependen de él.**

Veo que ya usáis la palabra "GATE" en otro contexto (el agente de
investigación de mercado referencia un "GATE 1" antes de pasar de la
investigación inicial a la plataforma de marca). Si ese gate ya existe como
concepto interno, la propuesta es simplemente formalizarlo y comunicarlo:

1. El propio documento de Concepto y Narrativa de Marca se divide, tal y
   como ya está estructurado su índice, en un primer bloque de
   diagnóstico/dirección (Observaciones Estratégicas → Territorio
   Competitivo → Oportunidad Estratégica) y un segundo bloque de
   construcción (Plataforma de Marca → Diseño del ecosistema → Comunidad →
   Aplicación → Hoja de ruta).
2. Entre los dos bloques hay un punto de aprobación explícito con el
   cliente: "esta es la dirección estratégica y la oportunidad que vamos a
   desarrollar — confírmanos que es la idea sobre la que construimos el
   resto". Eso es el GATE.
3. **Antes del gate**, los cambios de idea del cliente son parte normal del
   proceso — es exactamente para eso que existe ese primer bloque, y no
   cuesta nada extra porque nada posterior se ha construido todavía.
4. **Después del gate**, un cambio de concepto deja de ser "una corrección"
   y pasa a ser un cambio de alcance: se vuelve a esa fase, se recalculan las
   horas de ese tramo (y de cualquier documento de Architecture que ya
   hubiera arrancado sobre la base anterior — en particular 12, 14, 15 y 16,
   por la dependencia del hallazgo 5), y se comunica como tal, no como un
   castigo. Algo como: "las ideas evolucionan y es normal — lo que hacemos
   cuando pasa después de confirmar la dirección es recalcular el tiempo de
   ese tramo, igual que haríamos con cualquier otro cambio de alcance",
   mantiene vuestro tono honesto sin dejar de proteger el tiempo del equipo.
5. Esto también resuelve la segunda parte del problema que mencionas (la
   falta de claridad afecta a la calidad del entregable): un gate explícito
   le da al cliente un momento concreto en el que tiene que decidir en
   serio, en vez de ir dando feedback de forma difusa durante todo el
   proceso — lo cual normalmente mejora la calidad de lo que decide, no solo
   protege vuestro tiempo.

Esto es una propuesta, no una decisión tomada — lo lógico es que la validéis
Sergio y tú, y que si se adopta, se añada como nota explícita en el índice
de la fila 11 del Excel (y quizá como plantilla de email/mensaje para
comunicarlo a clientes en `plantillas/`).

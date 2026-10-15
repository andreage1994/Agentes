# Estado — Casa Clementina

**Fecha de arranque de la carpeta:** 2026-10-15.

## Quién es la clienta y qué nos pide

**Casa Clementina Café SL**, interlocutoras Fuensanta Casanova Pujante y
Lucia (contacto principal: casaclementinacafe@gmail.com). El negocio es
una cafetería/restaurante en Calle Hierro (Madrid), todavía sin abrir —
la obra está hecha pero no terminada del todo, y los socios están
**paralizados** decidiendo entre seguir invirtiendo lo que falta para
abrir, o traspasar el proyecto. Nos piden un informe de viabilidad del
negocio que les ayude a tomar esa decisión.

## Servicio contratado (fuente: SOW firmado)

Un único servicio: **AR03 — Proyección financiera y viabilidad de
negocio** (fase **Architecture** del BAR Method). No hay ningún
servicio de Breakdown contratado — confirmado también porque la
carpeta `03_BAR METHOD - INTERNO/01_BREAKDOWN` en Drive está vacía. Es
decir: vamos directos a Architecture sin diagnóstico previo formal de
TBNB. Esto importa porque, según la propia revisión de índices del BAR
Method (`bar-method-interno/revision-indices-2026-10.md`, hallazgo 5),
el servicio de Proyección Financiera **asume un modelo de negocio ya
definido por el concepto** — y aquí no hay ningún AR01 (Concepto y
narrativa de marca) desarrollado por TBNB. Las hipótesis comerciales
(ticket medio, mix de ventas, aforo...) van a tener que apoyarse en lo
que el cliente ya tiene decidido/operando, no en un concepto validado
por nosotros. **Vale la pena que Andrea lo tenga presente en la
reunión** — no es un bloqueante, pero sí condiciona cuánta solidez
pueden tener algunas hipótesis del informe.

Condiciones relevantes del SOW:
- Fechas: inicio previsto 07/10/2026, fin previsto 27/10/2026 (~20 días).
- 4 sesiones de 1 hora incluidas. Sin visitas presenciales. Sin mystery
  guest.
- 3 revisiones incluidas, 5 días hábiles de plazo cada una.
- Honorarios: 1.650€ + IVA en total, repartidos en 3 pagos (50%/25%/25%).
- Las proyecciones tienen carácter orientativo (hipótesis razonables,
  no garantía de resultados) — esto ya está recogido en el propio SOW,
  bien para dejarlo claro en el informe también.

## Estructura real en Drive (ya existe, no hay que crearla)

`1.2 ON GOING / 08_CASA CLEMENTINA I LUCIA - FUEN X TBNB /`
- `00_ADMIN - INTERNO`
- `01_GESTIÓN PROYECTO - INTERNO` (Briefing, Retroplanning, Notas y
  reuniones, Work in progress)
- `02_DOCUMENTACIÓN CLIENTE - INTERNO` → `Documentación recibida del
  cliente (Originales)` — aquí vive todo lo que ha compartido el
  cliente, sin tocar.
- `03_BAR METHOD - INTERNO` → `01_BREAKDOWN` (vacía), `02_ARCHITECTURE`
  → `01_Proyección_Financiera_Casa_Clementina` (plantillas de hoy, ver
  abajo), `03_RUN` (vacía, no toca todavía).
- `04_CLIENTE - COMPARTIDO` (Documentación Cliente, Reuniones,
  Entregables, Presentaciones, Información del proyecto — vacías,
  pendiente de usar).
- `05_CIERRE - INTERNO`

## Lo que ya sabemos del negocio (dato real, de los documentos del cliente)

**Inversión y pagos — ojo, hay tres cifras distintas circulando, hay
que fijar una sola antes de construir el modelo (ver Gap 1):**
- Inversión ya realizada en obra y materiales: **190.961,60€** (IVA
  incl.) — KIPER constructora 148.111,23€, ventanas DIPO 25.840€,
  estantería 6.700€, campana extractora 700,89€, materiales aparte
  9.609,48€. El presupuesto inicial de obra era 127.370€ con IVA — se
  disparó por partidas no previstas (estudio unifilar, cuadro eléctrico
  trifásico).
- Importe total pagado hasta hoy (incluye obra + fianza 4 meses +
  alquiler 4 meses + licencias + arquitectos + máquina de café, etc.):
  **239.561,25€**.
- Importe pendiente de pago, según el desglose actualizado del cliente
  (`Casa_Clementina_pagos_pendientes_actualizado.docx`): **61.014€**,
  con partidas concretas (mobiliario 7.000€, pequeños electrodomésticos
  3.500€, final de obra 15.000€, software 1.500€, alarma 500€, wifi
  400€, food cost inicial 3.000€, alquiler de octubre 1.800€, sueldos
  6.000€, "Hostel Markt" pendiente 9.000€ — coincide con la mitad
  pendiente de la maquinaria de cocina/barra que menciona el cliente
  aparte — y otras partidas menores).
- El archivo `Casa_Clementina_Abierto_Todos_Los_Dias.xlsx` (que ya trae
  un primer modelo de escenarios, ver más abajo) usa una **cuarta
  cifra** de inversión inicial: 276.125€, que no coincide exactamente
  con ninguna de las tres anteriores.

**Alquiler y traspaso:**
- Renta escalonada: 1.800€ (años 1-2) → 1.900€ (año 3) → 2.000€ (año 4)
  → 2.100€ (año 5) → 2.100€ + IPC después. Contrato de **25 años**.
- Es un **subarriendo**: el arrendatario principal es un tercero
  ("Panadario"), que tiene esos mismos 25 años. **Cualquier cesión o
  traspaso del local tiene que aprobarlo Panadario — y, a fecha de hoy,
  la clienta confirma que todavía no han hablado con él de esto.** Esto
  es un riesgo real y central para el escenario de "traspasar" que
  menciona Andrea — no es solo una decisión de los socios, depende de
  un tercero no consultado todavía.

**Equipamiento y mobiliario:**
- Maquinaria de cocina y barra: ~15.000€, mitad pendiente (~8.000€), **no
  entregada todavía**.
- Cafetera (Marzocco) + 2 molinos: ~15.000€, ya pagado.
- Mobiliario: prácticamente nada comprado (solo espejo/apliques de baño
  275€ y lámpara de barra 700€). Falta invertir ~14.220€ para amueblar
  el local entero + ~3.500€ estimados para terminar de montar cocina.
- Instalaciones: sonido instalado pero sin configurar (sin wifi
  todavía). Faltan wifi, alarma y TPV.

**Acústica:** Absotec ha hecho un estudio de acondicionamiento acústico
para KIPER (la constructora), no un proyecto cerrado — **no hay coste
visible en el documento compartido** (puede estar en una tabla/imagen
no extraída). Pendiente de precio real si se decide ejecutar.

**Licencias:** memoria de la licencia ya presentada, a la espera del
certificado de conformidad. Hay documentos de Declaración Responsable y
Comunicación Previa ya registrados (`DR REGISTRADA.pdf`, `CC
REGISTRADO.pdf`) y un proyecto técnico de actividad completo (`PROYECTO
ACTIVIDAD CAFEBAR C SODIO 3A.pdf`). Dos salidas de humos: una ya
conectada a la extracción de cocina, la otra sin preinstalación (se
consideró innecesaria) — vale la pena confirmar que esto no genera un
problema con la licencia antes de dar por cerrado ese punto.

## Plantillas BAR Method ya copiadas hoy en Drive (vacías, sin datos)

Andrea ya ha copiado en `02_ARCHITECTURE/01_Proyección_Financiera_Casa_Clementina`
los tres documentos maestros de TBNB para este servicio — los tres
están **completamente vacíos**, son el esqueleto, no contenido:

1. **`Casa_Clementina_BUSINESS VIABILITY REPORT X TBNB.pptx`** — el
   informe final. Índice real de 9 secciones: Executive Summary,
   Business Assumptions, Revenue Model, Cost Structure, Financial
   Projections (P&L 12 meses, EBITDA, margen, beneficio neto, cash
   flow, KPIs), Investment Plan, Viability Analysis (break-even, ROI,
   payback), Risk Assessment (escenarios, sensibilidad), Strategic
   Recommendations. **Nota:** dentro de la sección 8 hay una frase suelta
   sin terminar ("Esta parte aporta muchísimo valor como") que parece
   un apunte de Andrea a medio escribir, no contenido del índice —
   conviene que lo revise/borre antes de usar la plantilla con el
   cliente.
2. **`Casa_Clementina_Proyección_Financiera`** (Google Sheet) — el
   modelo maestro completo: Instrucciones, Inversiones, Inversión
   inicial, Datos (supuestos), Ventas (supuestos), Cuenta de Resultados
   (año 1/2/3), Tesorería (año 1/2/3), IVA, Amortizaciones, Plan de
   Financiación, Financiación (simulador), Break-Even, Turnos, Tabla
   Salarial, Proyecciones, Menú márgenes y precio unitario,
   Distributors Prices. **Hallazgo de higiene de plantilla:** la
   pestaña "Menu Margenes y Precio Unitario" trae encabezados en
   italiano (Prezzo Unitario, Costo Unitario, Margine bruto...) — parece
   una plantilla heredada de otro cliente sin limpiar del todo, igual
   que se detectó antes en plantillas RUN de otro proyecto. Lo señalo,
   no lo corrijo por mi cuenta.
3. **`Casa_Clementina_P&L`** (Google Sheet) — Dashboard + P&L + Budget +
   Comparativa P&L vs Budget. También vacío.

## Un borrador real que ya existe y hay que reconciliar

**`Casa_Clementina_Abierto_Todos_Los_Dias.xlsx`** — a diferencia de las
plantillas de arriba, este archivo **sí tiene números reales
calculados**: un escenario "abierto todos los días" con visitas/día y
ticket medio mes a mes (arrancando en 82 visitas/7€ en noviembre, hasta
110 visitas/8,50€ en julio), COGS al 35%, gastos fijos de 10.900€/mes,
EBITDA mensual, y una proyección a 6 años con tres escenarios
(conservador +3%, base +5%, expansivo +8% de crecimiento anual) que
calculan cuándo se recupera la inversión inicial (usando la cifra de
276.125€ mencionada arriba). También separa unos "ingresos
complementarios" (despensa/regalos, talleres, arte/comisiones) fuera
del núcleo de cafetería.

**No sabemos quién construyó este archivo ni con qué validación** — si
es un primer boceto exploratorio de TBNB, una hipótesis que ya manda el
propio cliente, o un ejercicio previo de otra fase. Antes de usarlo
como base del informe oficial, hay que confirmarlo.

## Gap analysis original (para la reunión de hoy) — estado tras la reunión

1. **Fijar una única cifra de inversión.** Sigue sin fijarse una cifra
   única; además, Andrea pide expresamente que **TBNB calcule, por su
   cuenta, qué falta y qué no se ha tenido en cuenta** en los números
   del cliente (no solo preguntar). Ver análisis propio más abajo.
2. **Traspaso.** Andrea confirma que es "una dependencia súper
   importante" y que se preguntará directamente al cliente qué hacer
   con esto en la reunión. Sigue sin resolver — pendiente de la propia
   reunión.
3. **El archivo `Abierto_Todos_Los_Dias.xlsx`.** **Resuelto:** es un
   borrador que **comparte el propio cliente**, no un ejercicio de
   TBNB. Valoración de Andrea: **no es viable como base — le falta
   mucha información.** No se usa como punto de partida del modelo
   oficial (ver nota más abajo sobre sus supuestos, que además quedan
   contradichos por las cifras reales que da Andrea en el punto 6).
4. **Precio del proyecto acústico de Absotec.** Se solicitará al
   cliente. Sigue pendiente.
5. **Pacto de socios / reparto de capital.** Se preguntará al cliente
   qué hacer con esta partida en la reunión. Sigue pendiente.
6. **Hipótesis comerciales — resuelto con nuevos datos de Andrea:**
   - Aforo: **44 pax** confirmado (coincide con el cálculo ya hecho a
     partir del plano de mesas), pero **queda pendiente confirmar el
     aforo de la terraza por separado, y si ya está aprobado/confirmado**
     (no solo contado, sino con el visto bueno que corresponda).
   - Horario y días: **abierto los 7 días de la semana**, pero **en
     horario de cafetería, no de restaurante — aprox. 8:00 a 18:00h**.
     Esto es distinto de lo que asumía el borrador del cliente (que no
     especificaba horario, solo días).
   - Ticket medio: **horquilla de 10-15€**, muy por encima del 7€→8,50€
     progresivo que usaba el borrador del cliente — confirma que ese
     borrador infravalora el ticket medio real esperado.
   - Estacionalidad: **julio y agosto son los peores meses en Madrid**
     (ya lo son estructuralmente, no una hipótesis a validar). Esto es
     opuesto a lo que podría asumirse por tener terraza, y también
     contradice al borrador del cliente, que marcaba julio como uno de
     los meses más fuertes (110 visitas/día, el ticket medio más alto
     de toda la tabla) — otra razón más para no partir de ese archivo.
7. **Personal.** TBNB calculará la plantilla y los costes salariales
   sobre una tabla salarial propia, para los puestos: **manager,
   barista, camareros, ayudante de camarero, cocinero y ayudante de
   cocina.** Las tablas salariales concretas se confirman con el
   cliente en la propia reunión, para no ir y venir por email.
8. **Higiene de plantilla (pestaña en italiano, frase suelta en el
   pptx).** Se corrige más adelante, en el momento de completar el
   documento real — no ahora.

## Análisis propio de TBNB: qué falta por invertir que el cliente no ha
## contemplado del todo (punto 1, calculado por nosotros)

Cruzando la lista oficial de pagos pendientes
(`Casa_Clementina_pagos_pendientes_actualizado.docx`, total 61.014€)
contra las propias respuestas del cliente
(`Numeros Casa Clementina.pdf`), aparecen dos huecos concretos y
cuantificables que la lista de pendientes no recoge bien, más dos
puntos a confirmar:

1. **Mobiliario — falta presupuesto por ~7.220€.** La lista de
   pendientes presupuesta "Muebles" en **7.000€**. Pero el propio
   cliente dice textualmente que amueblar la cafetería entera
   "necesitaríamos invertir unos 14.220 euros (IVA incluido)" y añade
   que **esta cifra, a diferencia de otras, es exacta** ("lo de los
   muebles sí es cifra exacta"). Es decir: la lista oficial de
   pendientes **se queda corta en mobiliario por 7.220€** frente al
   propio dato del cliente. (Los pequeños electrodomésticos de cocina
   sí cuadran: 3.500€ en ambos sitios.)
2. **TPV: coste no presupuestado en ningún sitio.** El cliente dice
   explícitamente "faltaría wifi, alarma y TPV". La lista de pendientes
   sí incluye alarma (500€) y wifi (400€), pero **no tiene ninguna
   línea para el TPV** — coste real pendiente de estimar, no solo de
   confirmar.
3. **Proyecto acústico de Absotec: 0€ presupuestado**, coste
   desconocido (ver punto 4 del gap analysis).
4. **A confirmar, no necesariamente un error:** la partida "Final de
   obra: 15.000€" de la lista de pendientes — ¿es el saldo que queda
   por pagar a KIPER sobre los 190.961,60€ de coste final de obra, o
   una partida aparte? El cliente dice que el total pagado hasta hoy
   (239.561,25€) ya incluye "todas las licencias, pagos a arquitectos,
   la máquina de café, etc.", pero no dice explícitamente si la obra
   está 100% pagada dentro de esa cifra. Conviene preguntarlo
   directamente para no arrastrar una posible doble cuenta (o un hueco)
   al modelo.
5. **Recomendación, no solo hallazgo:** la obra ya se desvió un ~50%
   sobre su presupuesto inicial (127.370€ → 190.961,60€ final), por
   partidas no previstas (estudio unifilar, cuadro eléctrico
   trifásico). Dado ese historial, tiene sentido recomendar en el
   informe un **margen de contingencia** sobre las partidas todavía sin
   cerrar del todo — sobre todo mobiliario y la maquinaria de
   cocina/barra, que sigue sin entregarse.
6. **Nota aparte, no es un hueco de capital:** de los 61.014€ de
   pendientes, 2.600€ son un reembolso interno de la SL a Fuensanta (lo
   que ella adelantó de su bolsillo), no una necesidad de capital
   externo nuevo — conviene distinguir esta partida de las demás en el
   Investment Plan, aunque sea correcto incluirla en el total de
   obligaciones de la SL.
7. **Riesgo de calendario no capitalizado:** la lista de pendientes
   solo incluye un mes de alquiler ("Alquiler de octubre: 1.800€"). Si
   la apertura se retrasa más allá de octubre, cada mes adicional suma
   ~1.800-1.900€ de alquiler no presupuestado — vale la pena señalarlo
   como coste de la propia indecisión entre socios.

## Equipo de especialistas creado para este servicio

A petición de Andrea, se crean tres agentes especializados en
`.claude/agents/` para apoyar el desarrollo de AR03 en este y futuros
proyectos de Proyección Financiera y Viabilidad de Negocio:

- **`financiero-modelizacion`** — construye el modelo financiero
  (Business Assumptions, Revenue Model, Cost Structure, Financial
  Projections) a partir de datos reales del cliente, sin inventar
  cifras.
- **`financiero-viabilidad`** — construye el análisis de viabilidad
  (Investment Plan, break-even, ROI, payback, escenarios, Risk
  Assessment) y las recomendaciones estratégicas finales.
- **`financiero-contable-revision`** — revisión de control: concilia
  las cifras del modelo contra los documentos reales (facturas,
  contratos, presupuestos), detecta inconsistencias como las cuatro
  cifras de inversión de este proyecto, y vigila el tratamiento
  correcto de IVA y de los números antes de que lleguen al informe
  final.

## Próximos pasos

1. En la reunión de hoy, además de las preguntas ya identificadas
   (traspaso/Panadario, pacto de socios, precio Absotec), trasladar al
   cliente los dos huecos cuantificados por TBNB: el mobiliario
   infrapresupuestado (~7.220€) y el TPV sin coste estimado — y aclarar
   si "Final de obra: 15.000€" es saldo de KIPER o partida aparte.
2. Confirmar con el cliente, en la propia reunión, las tablas
   salariales de los 6 puestos (manager, barista, camareros, ayudante
   de camarero, cocinero, ayudante de cocina).
3. Con el aforo, horario (8-18h, 7 días), ticket medio (10-15€) y
   estacionalidad (jul-ago flojos) ya confirmados por Andrea, empezar a
   rellenar el modelo maestro de Proyección Financiera con
   `financiero-modelizacion` — **no** partiendo del borrador
   `Abierto_Todos_Los_Dias.xlsx` del cliente, que Andrea ya descarta
   como base.
4. Construir el Business Viability Report con `financiero-viabilidad`
   una vez el modelo tenga números reales y validados, incluyendo el
   margen de contingencia recomendado sobre partidas todavía abiertas.
5. Pasar todo por `financiero-contable-revision` antes de entregar nada
   al cliente — en particular, reconciliar la cifra única de inversión
   total (sigue sin fijarse, punto 1 del gap analysis) y el saldo real
   de obra pendiente.

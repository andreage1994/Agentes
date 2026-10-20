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

## 2026-10-19 — Datos reales tras la reunión con el cliente

Andrea aporta los datos definitivos de la reunión de hoy. Esto **sustituye** las
cifras provisionales que arrastraba el gap analysis anterior allí donde
hay conflicto (lo marco explícitamente).

**Inversión y pagos — cifra única ya fijada (resuelve el Gap 1 de arriba):**
- Importe total pagado a día de hoy: **240.000€** (coincide, redondeado,
  con los 239.561,25€ ya documentados).
- Importe pendiente de pago: **solo 8.000€**, correspondientes al resto
  de la maquinaria de cocina/barra (coincide con la mitad pendiente de
  ~15.000€ ya documentada). Andrea es explícita: esto es lo único que
  falta pagar **de lo que ya estaba valorado y presupuestado** dentro de
  la obra — no incluye las partidas nuevas de abajo.

**Partidas nuevas de inversión para abrir (no estaban pagadas, fuera del
presupuesto de obra ya cerrado):**
- Software (instalación/licencia inicial): **cifra pendiente** — Andrea
  la dará cuando se le pida, no inventar un número.
- Mobiliario (mesas, sillas, bancos): **~15.000€** — actualiza la cifra.
  Confirma el hallazgo propio de TBNB (el mobiliario estaba
  infrapresupuestado en la lista oficial de pendientes en ~7.220€ frente
  al dato exacto del cliente de 14.220€) — la cifra de hoy (15.000€) es
  consistente con ese hallazgo, no con los 7.000€ de la lista oficial.
- Pequeños electrodomésticos: **~3.500€** (confirma la cifra ya
  documentada).
- Food cost inicial: **5.000€** (actualiza los 3.000€ de la lista
  oficial de pendientes).
- Alquiler de octubre: **1.800€** (confirma la cifra ya documentada).
- Sueldos: **se calculan cuando saquemos las necesidades de personal**
  (no es una cifra cerrada todavía — depende del modelo de turnos).

**Gastos fijos mensuales recurrentes (antes aparecían como pagos únicos
en la lista de pendientes — Andrea los reclasifica hoy como recurrentes,
corrige el tratamiento anterior):**
- Alarma: **50€/mes** (antes figuraba como pago único de 500€ — se
  corrige: es cuota mensual, no inversión puntual).
- Wifi: **50€/mes** (antes figuraba como pago único de 400€ — misma
  corrección: es cuota mensual).
- TPV: **300€** (hardware, pago único) **+ software del TPV: 80€/mes**
  — **a confirmar contra presupuesto real de Square** ("o presupuesto de
  Square" — Andrea da estas cifras como aproximación, no como cifra
  cerrada; usar la cotización real de Square si llega antes de cerrar el
  informe).
- Renta escalonada (1.800€ años 1-2 → 1.900€ año 3 → 2.000€ año 4 →
  2.100€ año 5 → 2.100€ + IPC después): se incorpora a la proyección
  multianual cuando corresponda (años 3+), no solo al mes 1.

**Proyecto acústico de Absotec — resuelto (Gap 4 cerrado):** el cliente
confirma que su coste **ya está incluido dentro de la obra** (dentro de
los 190.961,60€/240.000€ ya pagados). No hay partida aparte que añadir.

**Aforo y terraza — resuelto:** 44 pax confirmados (solo interior). La
terraza **no está aprobada todavía** y su licencia puede tardar mucho —
**se excluye de la proyección por completo**, no se contabiliza su
aforo ni sus ingresos.

**Hipótesis comerciales actualizadas:**
- Horario y días: 7 días abiertos (confirma lo ya documentado).
- Ticket medio: **11-14€** (estrecha la horquilla de 10-15€ ya
  documentada).
- Estacionalidad: julio y agosto, **-60% sobre la proyección del resto
  del año** (cuantifica la hipótesis cualitativa ya documentada de que
  son los meses más flojos en Madrid).

**Personal — tabla salarial real confirmada (en NETO, calcular coste de
empresa con +33% de Seguridad Social sobre el bruto):**

| Puesto | Salario neto/mes | SS empresa |
|---|---|---|
| Manager | 1.800€ | +33% |
| Barista | 1.500€ | +33% |
| Camarero/a | 1.400€ | +33% (según convenio) |
| Ayudante de camarero/a | 1.400€ | +33% (según convenio) |
| Cocinero/a | 1.400€ | +33% (según convenio) |
| Ayudante de cocina | 1.400€ | +33% (según convenio) |
| Jefe/a de cocina | 1.600€ | +33% |

Nota de Andrea: estamos en Madrid, no Barcelona — tenerlo presente al
calcular (no aplicar por defecto ningún criterio usado en proyectos de
Barcelona). El cálculo de coste de empresa a partir de neto exige
convertir neto→bruto (vía retención de IRPF), que depende de la
situación personal de cada trabajador y no tiene una fórmula única real
— se documentará como una hipótesis explícita y editable dentro del
modelo (tipo de retención asumido), nunca como un dato exacto inventado.
Turnos: 7 días abiertos, 8h de jornada, plantilla ajustada lo más
posible a la necesidad real por franja (no sobredimensionada).

**Plazo:** Andrea pide dar forma profesional a las tres plantillas
maestras (Business Viability Report, Proyección Financiera, P&L) una por
una, para entregarlo todo correctamente **mañana** (solo con margen para
pequeñas correcciones después). El borrador `Abierto_Todos_Los_Dias.xlsx`
del cliente se descarta definitivamente como base (confirmado de nuevo).

## 2026-10-19 (cont.) — Primer modelo financiero real construido

**Limitación técnica encontrada:** el conector de edición de Google
Sheets no está activo en esta sesión de trabajo (solo lectura de Drive),
así que no se puede escribir directamente en las plantillas maestras
reales (`Casa_Clementina_Proyección_Financiera`, 18 pestañas,
confirmadas vacías por lectura directa). Para no bloquear el plazo de
mañana, se construye el modelo completo en local
(`run/Casa_Clementina_Modelo_Financiero_TBNB.xlsx`), con fórmulas reales
(nunca cifras calculadas a mano), siguiendo todos los datos reconciliados
arriba. **Pendiente: traspasar estos números a las plantillas reales de
Drive** — Andrea/Sergio deciden si lo hacen ellos o si activan el
conector de Sheets para que lo haga TBNB directamente.

Pestañas del modelo: Supuestos, Plan de Inversión, Personal (coste de
empresa), Costes Fijos, Punto de Equilibrio, Cuenta de Resultados Año 1
(mensual) y Preguntas Abiertas. Validado con `recalc.py` (0 errores,
163 fórmulas) y revisado visualmente diapositiva a diapositiva.

**Resultados reales del modelo:**
- Inversión pendiente para abrir: **33.600€** (8.000€ de cocina ya
  valorada + 15.000€ mobiliario + 3.500€ electrodomésticos + 5.000€ food
  cost inicial + 1.800€ alquiler octubre + 300€ TPV — software todavía
  sin cifra).
- Coste de personal: con un headcount de ejemplo (8 personas: 1 manager,
  1 barista, 2 camareros, 1 ayudante de camarero, 1 cocinero, 1 ayudante
  de cocina, 1 jefe de cocina — **marcado en amarillo, pendiente del plan
  real de turnos**), el coste de empresa total es **18.620€/mes**
  (223.440€/año), calculado neto→bruto con un 15% de IRPF estimado
  (asunción editable, a validar con gestoría) + 33% de Seguridad Social
  dado por Andrea.
- Punto de equilibrio: **20.600€/mes** de costes totales (con el COGS al
  30%, de referencia, no confirmado) exige **29.428€/mes** de ventas —
  entre 69 y 88 visitas/día según el ticket medio (11-14€), frente a una
  capacidad teórica de referencia de 132 visitas/día (44 pax × 3 turnos).
- **Hallazgo real sobre estacionalidad:** si las visitas se mantienen en
  el nivel de equilibrio todo el año, julio y agosto generan solos una
  pérdida combinada de **-24.720€** en el año, porque los costes fijos no
  bajan aunque las ventas caigan un 60% — el resto de los meses, la
  cuenta de resultados queda exactamente en cero (es el comportamiento
  esperado del marcador neutro, no una proyección real todavía).

**Lo que falta para que la Cuenta de Resultados deje de ser un marcador
neutro y pase a ser una proyección real** (recogido también en la propia
pestaña "Preguntas Abiertas" del archivo):
1. Visitas/día o facturación objetivo esperada — el dato que más cambia
   el resultado, todavía sin confirmar.
2. Headcount real por puesto, según el plan de turnos.
3. Coste real del software (instalación/licencia inicial).
4. Presupuesto real de Square (TPV + software mensual).
5. COGS % real sobre ventas corrientes.
6. Suministros (luz/agua/gas) y seguro del local.
7. IRPF real aplicable a cada contrato (validar con gestoría).
8. Si "Final de obra: 15.000€" de la lista de pendientes antigua es
   saldo de KIPER o partida aparte (pregunta heredada, sigue abierta).
9. Traspaso/Panadario y pacto de socios (pendientes de la propia
   reunión, gap analysis original).

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

## 2026-10-20 — Conector de Google Sheets activado; trabajo directo en el Sheet real

Andrea activa el conector de edición de Google Sheets en esta sesión.
A partir de ahora Andrea dicta, hoja a hoja, qué construir en el Sheet
real (`Casa_Clementina_Proyección_Financiera`), y se ejecuta directamente
ahí — ya no se trabaja sobre el Excel local
(`run/Casa_Clementina_Modelo_Financiero_TBNB.xlsx`, que queda como
primer borrador de referencia, no como entregable final).

**Hallazgo grave antes de empezar a escribir:** la plantilla real
**no estaba vacía** — tenía la lógica y los números completos de un
proyecto de **otro cliente** (un concepto de comida a domicilio en
Barcelona, tipo panzerotti, con comisión Glovo, canales Delivery/
In-Store/"Tardeo", benchmarks de marcas reales de Barcelona, tabla
salarial con sueldos y retenciones reales de ese cliente, e incluso
fórmulas rotas `#REF!` del archivo original de ese cliente). Esto
afecta a las hojas `Datos`, `Tabla Salarial`, `Inversiones`, `Ventas`,
`Turnos`, `Break-Even` y `Cuenta Resultados`. Es un problema de higiene
de datos más serio que el ya detectado en `Menu Margenes y Precio
Unitario` (cabeceras en italiano) — hay datos reales de un cliente
distinto circulando en una plantilla reutilizada entre proyectos.
**Recomendación: revisar el resto de plantillas maestras del equipo por
el mismo motivo.**

**Hojas 1 y 2 completadas con datos reales (`Inversiones` e `Inversión
inicial`), más la parte ya necesaria de `Plan de Financiación`:**

- `Inversiones` (categorías contables clásicas — estructura reutilizable,
  solo se han sustituido los números del cliente anterior): Inmovilizado
  material 215.261,60€ (Instalaciones = obra completa 190.961,60€, con
  el proyecto acústico de Absotec ya incluido; Mobiliario 15.000€;
  Maquinaria 8.000€ — solo el saldo pendiente; Equipamientos
  informáticos 1.300€ = TPV 300€ + impresoras/handhelds 1.000€).
  Inmovilizado inmaterial 9.450€ (Marcas y patentes 600€; Depósitos y
  fianzas 7.200€ = 4 meses × 1.800€/mes; Estudios previos 1.650€ =
  honorarios de consultoría AR03 de TBNB, coincide con el SOW firmado).
  Circulante 20.000€ (Provisión de fondos, dato directo de Andrea;
  Existencias en 0€, pendiente — "el food cost lo ponemos luego").
  **Total: 244.712€.**
- `Plan de Financiación`: Ahorros personales **240.000€** (80.000€ × 3
  socias — Fuensanta, Lucia y la madre de Fuensanta, nombre todavía
  pendiente — confirmado 2026-10-20, resuelve el hueco inicial de
  160.000€ frente al total invertido). Resto de fuentes en 0€ ("sin más
  datos").
- `Inversión inicial` (lista de partidas por ID/Concepto/Importe,
  organizada en 3 bloques según el criterio de Andrea): **Operating
  Costs** (gastos de apertura) 9.450€ — incluye Marca, Depósitos y
  fianzas, Estudios previos (TBNB), y 5 partidas todavía en 0€
  pendientes (food cost, take away, menaje, utensilios de cocina,
  material de oficina). **CAPEX** 233.761,60€ — obra, mobiliario,
  maquinaria, cafetera Marzocco+molinos (ya pagada), pequeños
  electrodomésticos, TPV, impresoras/handhelds, y 3 partidas en 0€
  pendientes (iluminación, decoración, plantas). **OPEX (Gastos
  Fijos)** 1.980€/mes — alquiler, alarma, wifi, software TPV, y 2
  partidas en 0€ pendientes (póliza de seguro, RC).

**Pendiente de Andrea/cliente para cerrar estas dos hojas del todo:**
número real de socios y/o fuente de financiación del resto de la
inversión; food cost inicial, take away, menaje, utensilios de cocina,
material de oficina; iluminación, decoración, plantas; póliza de
seguro y RC.

**2026-10-20 (cont.) — Tercera socia confirmada.** La madre de
Fuensanta es la tercera socia (nombre pendiente). `Plan de
Financiación`: Ahorros personales = 80.000€ × 3 = **240.000€**, que
reconcilia con el total invertido — resuelve el hueco de financiación.

**2026-10-20 (cont.) — Hoja `Datos` (Supuestos): mix de venta, volumen
diario y food cost, con un error propio corregido en el camino.**

Andrea define el modelo de ingresos real: 3 segmentos de venta en sala
(sin delivery, Casa Clementina no reparte) — café solo (especialidad),
café + snack, café + plato — con una jornada de 8h, cerrado por la
tarde, afluencia del 80% sobre el aforo (44 pax) y rotación de mesa 4
veces al día. Food cost variable: 30%.

Para dar sitio a los 3 segmentos (la plantilla original del cliente
anterior solo tenía 2, "Classic"/"Maxi"), se insertaron 2 filas nuevas
en `Datos` y se reescribió la sección como "Mix de Venta (sala — sin
canal delivery)": % Café solo 20% (ticket 4€) / % Café + snack 40%
(ticket 10€) / % Café + plato 40% (ticket 18€) → **Ticket medio
calculado: 12,00€**, dentro de la horquilla ya confirmada (11-14€).
Canal delivery neutralizado (100% sala) sin borrar la sección, solo
desactivada. Volumen diario (44×80%×4 = **141 comensales/día**)
cargado en la hoja `Ventas` (escenario Base, Año 1), con la
estacionalidad ya confirmada aplicada directamente ahí: 56/día en
julio-agosto (-60%), 141/día el resto del año. Food Cost % = 30%
confirmado. De paso se tradujeron al español los restos en italiano
("Anno"→"Año", "€/ordine"→"€/pedido", "PESSIMISTICO/OTTIMISTICO"→
"PESIMISTA/OPTIMISTA") y se fijó el escenario activo en "Base".

**Error propio detectado y corregido en el mismo turno:** al insertar
las 2 filas nuevas, todo el contenido de `Datos` por debajo se desplazó
2 filas hacia abajo (comportamiento correcto y esperado de Google
Sheets — las fórmulas de otras hojas que apuntaban a esas celdas se
reajustaron solas). El error fue mío: seguí escribiendo varias
correcciones posteriores (Food Cost%, Alquiler, % Seguridad Social,
Impuesto de Sociedades, Inversión Total, limpieza de Branding/
Operations) usando los números de fila **de antes del desplazamiento**,
así que esas 18 celdas aterrizaron 2 filas más arriba de donde debían
(el desplazamiento no se tuvo en cuenta),
pisando contenido real (algunas con fórmulas en vivo, como "Inversión
Total" y "Costes Personal Neto Año 2", que quedaron rotas). Se detectó
al revisar la Cuenta de Resultados y ver "Compras Food" en 0€ pese a
tener el food cost puesto. Se releyó la hoja entera fila por fila con
los números reales ya desplazados, y se corrigieron las 18 celdas en su
posición correcta, restaurando las fórmulas rotas
(`=Turnos!C14`, `=Inversiones!C22`). Verificado después contra la
Cuenta de Resultados: Compras Food, Alquiler, IVA e Inversión Total ya
calculan correctamente.

**Pendiente, fuera del alcance de hoy (son hojas futuras, no de
`Datos`):** la fórmula `Costes Personal Neto Año 1/3` sigue en `#REF!`
— es la contaminación ya detectada en la hoja `Turnos` del cliente
anterior (roles Chef/Freidor, no los puestos reales de Casa
Clementina), pendiente de reconstruir esa hoja y la `Tabla Salarial`.
`Suministros` y `Servicios externos (Marketing)` en la Cuenta de
Resultados siguen leyendo datos contaminados de `Tesorería`, todavía
sin tocar.

**2026-10-20 (cont.) — Hoja `Ventas`: Año 2 y Año 3 con crecimiento compuesto.**
Andrea rellena ella misma el Año 1 (Pesimista 60/día, Base 90/día,
Optimista 140/día, con caídas de temporada propias por escenario). Se
construyen Año 2 y Año 3 con fórmulas de crecimiento compuesto sobre esas
cifras reales (no hardcoded): una celda de tasa anual editable por
escenario en P7:Q9 (Pesimista 3%, Base 6%, Optimista 10% — asunción
razonable, no dato del cliente, fácil de ajustar) multiplicando cada mes
del año anterior. Resultado: Pesimista 60→62→64, Base 90→95→101,
Optimista 140→154→169.

**Aviso pendiente de confirmar:** en el escenario Optimista del Año 1,
la caída de temporada está puesta en junio-julio (70/70) en vez de
julio-agosto como en Pesimista y Base — se ha propagado igual a Año 2 y
Año 3. Preguntado a Andrea si es intencional.

**2026-10-20 (cont.) — Corregido el desliz de temporada en Optimista.**
Confirmado por Andrea: la caída de temporada del escenario Optimista
debía estar en julio-agosto, no junio-julio. Corregido en Año 1
(C9:N9) — Año 2 y Año 3 se recalculan solos al ser fórmulas sobre Año 1.

## Cuenta de Resultados (1r año) — correcciones 2026-10-20

Siguiendo instrucción de Andrea de trabajar ya la Cuenta de Resultados dejando
coste de personal para más adelante (se vinculará cuando reconstruyamos Turnos
+ Tabla Salarial), se detectaron y corrigieron dos anomalías más, ambas
secuelas del mismo bug de desplazamiento de filas ya documentado arriba:

1. **"Ventas (food)" daba 0,00€ en todos los meses.** La fórmula depende de
   `Datos!F6` (% ventas en sala) y `Datos!G6` (% delivery) — el "truco 100%
   sala" que habíamos fijado antes. Esas celdas habían quedado completamente
   vacías. Corregido: `Datos!F6=1`, `Datos!G6=0`. Resultado ya correcto:
   Ventas (food) = 24.054,55€/mes en meses normales, 9.354,55€ en los meses
   de caída estacional (jul/ago), total año 259.254,55€. Compras Food se
   recalculó en cascada a 7.632,69€/mes (82.263,46€ año).
2. **"Servicios externos (Contabilidad)" daba 206,61€/mes en vez de 0€.**
   `Datos!C43` (Contabilidad Mensual) tenía 250€ (dato heredado del cliente
   anterior / residual del bug de desplazamiento) en vez de 0 — la nota
   "PENDIENTE — falta cifra real" ya estaba puesta pero el valor nunca se
   corrigió. Fijado a `Datos!C43=0`. Ya muestra 0,00€/mes correctamente.

**Nuevo hallazgo, no corregido todavía — pendiente de decisión de Andrea:**
"Costes financieros" (fila 27) da `#REF!` a partir del mes 9. No es un
problema de esta hoja: la fórmula apunta a `'Financiación'!C41:N41`, y ahí
las celdas de los meses 9-12 contienen literalmente `=#REF!` guardado (algo
se borró dentro de la hoja `Financiación`, el simulador de préstamo, que
sigue sin revisar esta sesión y estaba en la lista de hojas con posible
contaminación de otro cliente). Arreglarlo exige entrar en esa hoja, igual
que coste de personal exige entrar en Turnos/Tabla Salarial — se deja
pendiente de que Andrea decida si se aborda ahora o se agrupa con el resto
de hojas por revisar (Financiación, Amortizaciones, Tesorería, IVA,
Break-Even, Proyecciones).

Como consecuencia, "Total costes", "Beneficios/Pérdidas", "Impuesto de
Sociedades" y "Beneficio Neto" siguen en `#REF!` hasta que se resuelvan
tanto Costes de personal como Costes financieros — es esperado, no un bug
nuevo.

## Cuenta de Resultados 2º y 3er año — 2026-10-20

Andrea pide hacer la Cuenta de Resultados del 2º y 3er año. Las hojas
`Cuenta Resultados 2nd año` y `Cuenta Resultados 3rd año` ya existían con
toda la estructura y fórmulas montadas en paralelo exacto al 1r año
(mismos conceptos, Año2 = meses 13-24, Año3 = meses 25-36, referencian
`Ventas`, `Datos` y `Tesorería 2/3 año`). Tenían el mismo bug que el 1r
año (la fila F:G de "% sala / % delivery" en `Datos`, filas 6-8, se vació
entera con el bug de desplazamiento ya documentado — no solo la fila 6 del
año 1).

**Corregido:**
- `Datos!F7=1, G7=0` (año 2) y `Datos!F8=1, G8=0` (año 3) — mismo truco
  "100% sala" aplicado al año 1. Resultado:
  - **Año 2**: Ventas (food) = 25.497,82€/mes (9.915,82€ en los meses de
    caída estacional), total 274.809,82€. Compras Food en cascada:
    8.090,65€/mes.
  - **Año 3**: Ventas (food) = 27.027,69€/mes (10.510,77€ en caída),
    total 291.298,41€. Compras Food en cascada: 8.576,09€/mes.
- Contabilidad ya salía en 0,00€ en ambas hojas automáticamente, al ser
  `Datos!C43` compartido entre los 3 años (corrección ya hecha hoy mismo
  para el año 1).
- Personalizado `A2` de ambas hojas a "CASA CLEMENTINA" (mismo patrón que
  Inversiones/Inversión inicial/Plan de Financiación/Ventas/1r año).
- Limpiada fila "Ventas Tardeo" (volumen) del 3r año, que tenía un número
  suelto (21,92 en todos los meses) heredado de otro cliente — Casa
  Clementina no tiene tardeo, y en año 1/2 esa fila está vacía
  correctamente. Ya no afectaba al resultado (el precio de tardeo está en
  blanco), era solo inconsistencia visual.

**Error propio detectado y corregido en el acto:** al limpiar la fila de
Tardeo del año 3 escribí primero en la fila equivocada (`C9:N9` en vez de
`C8:N8`) porque la hoja del año 3 tiene una fila menos de margen que la de
año 1/2 — eso borró por un momento "Días de trabajo mensual" (24,5),
haciendo que Ventas (food) volviera a dar 0€. Detectado al releer la hoja
completa inmediatamente después del cambio y corregido restaurando
`C9:N9=24,5` y limpiando `C8:N8` (la fila correcta de Tardeo). Verificado
con una relectura completa de la hoja: todo correcto.

**Sigue bloqueado, como ya se explicó en el 1r año (no es nuevo, es el
mismo arrastre):** Costes de personal (`#REF!`, deferido a la
reconstrucción de Turnos/Tabla Salarial) y Costes financieros (`#REF!`,
depende de la hoja `Financiación` sin revisar) en los tres años. Total
costes, Beneficios/Pérdidas, Impuesto de Sociedades y Beneficio Neto
seguirán en `#REF!` en los tres años hasta resolver esos dos puntos.

## Tesorería 1r/2º/3er año — revisión inicial 2026-10-20

Andrea pide preparar la Tesorería de los 3 años. Las tres hojas
(`Tesorería 1r año`, `Tesorería 2 año`, `Tesorería 3 año`) ya existen con
toda la estructura y fórmulas montadas (Cobros, Pagos, Saldo Mes/Anterior/
Acumulado), heredando los mismos dos bloqueos ya documentados (Costes de
personal deferido, hoja `Financiación` rota) — y estos dos arrastran
también la hoja `IVA`, que depende de ambos para "Tributos IVA".

**Limpieza mecánica ya hecha (sin esperar validación, mismo criterio que
en Cuenta Resultados):**
- Vaciada la fila "Clientes/Ventas Tardeo diarios" (volumen) en las tres
  hojas de Tesorería — tenía números sueltos en rampa (4→16 año1, 20 año2,
  22 año3) heredados de otro cliente; no afectaban al resultado (precio
  tardeo en blanco → 0€) pero generaban ruido visual inconsistente.
- Corregido el título de `Tesorería 3 año`, que decía "SEGUNDO AÑO" por
  error de copia de plantilla → ahora "TERCER AÑO".
- Personalizado `A2` de las tres hojas a "CASA CLEMENTINA".

**Pendiente de datos reales de Andrea** (preguntado en el chat, no
inventado): Suministros, Marketing, Gastos diversos (y el pago puntual de
fin de año dentro de esa partida) y si el Alquiler de Mes 0 debe duplicar
el pago de fianza que ya consta como gastado en Inversión Inicial.

## Tesorería — datos reales de Andrea aplicados 2026-10-20

Respuesta de Andrea a las 4 preguntas pendientes:
- Suministros: agua 50€ + luz 600€ + gas 0€ (no tienen gas) = **650€/mes**.
- Marketing: **800€/mes**.
- Alquiler Mes 0: "lo dejamos en mensualidades porque ya tenemos todo
  pagado en este proyecto" → el Mes 0 NO debe duplicar la fianza (ya está
  pagada y contabilizada en Inversión Inicial), solo la mensualidad normal.
- Gastos diversos (150€/mes + pago puntual 1.650€/3.650€ a fin de año):
  sin respuesta todavía — vuelto a preguntar.

**Aplicado en las tres hojas de Tesorería (1r/2º/3er año):**
- Suministros: 650€/mes fijo los 3 años (antes 1.060€→1.600€→2.100€
  escalonado, residuo de otro cliente). Asunción tomada: se aplica el
  mismo 650€ también al Mes 0 del año 1 (antes 400€) y sin escalado por
  año, al no decir Andrea lo contrario — señalado para que lo corrija si
  quería otra cosa.
- Marketing: 800€/mes fijo los 3 años (antes 3.500-4.500€ escalonado).
  Misma asunción: se sustituyó también el pago especial de Mes 0 (antes
  6.000€, posible campaña de apertura) por el mismo 800€ — señalado por
  si Andrea quería mantener un presupuesto de lanzamiento aparte.
- Alquiler Mes 0 (`Tesorería 1r año!B26`): fórmula corregida de
  `=Datos!$C$46*2` a `=Datos!$C$46` — ya no duplica la fianza.

Cascada verificada en Cuenta Resultados 1r año: Suministros 537,19€/mes
neto de IVA, Marketing 661,16€/mes neto de IVA — correcto.

## IVA — diagnóstico 2026-10-20

Andrea pide terminar la hoja IVA. Revisión completa (27 columnas, 12
trimestres de los 3 años + Mes 0 pre-apertura): la hoja ya está bien
construida y ya recalcula sola con los datos reales de Tesorería que
acabamos de fijar (Suministros 338,43€/trim., Marketing 416,53€/trim.,
Alquiler 1.134€/trim. — se arrastraron automáticamente, sin tocar nada
aquí). El crédito IVA de Mes 0 (872,63€) es correcto.

Pero el resto de la hoja — Tributos IVA Trimestral y Acumulado de los 36
meses, en los 3 años — está en `#REF!` sin excepción. No es un problema de
datos: es que "Retribuciones propias" y "Seguridad Social" (coste de
personal, diferido) ya contaminan el Q1 del año 1 (no hace falta llegar al
mes 9), y al ser el IVA un acumulado trimestral, un solo mes roto rompe el
trimestre entero y, en cascada, todos los trimestres siguientes. Desde el
Q3 del año 1 se suma también "Cuota microcrédito" (hoja `Financiación`
rota).

Conclusión: no tiene sentido seguir pidiendo datos para IVA — el bloqueo es
estructural. Se lo planteé a Andrea como decisión (Financiación primero /
Personal primero / las dos / aparcar) — **elige Personal primero**, porque
es el que contamina desde antes (Q1, no Q3). Se continúa reconstruyendo
`Turnos` + `Tabla Salarial` con los roles reales de Casa Clementina.

## Personal — Tabla Salarial y Turnos reconstruidos 2026-10-20

Plantilla real confirmada por Andrea (vía chat, no AskUserQuestion — no
hay que repetir la pregunta): 1 Manager (1.800€ neto, 5h/día en servicio
de camarero + resto administrativo) + 1 Barista (1.500€ neto, cubre
barra y cocina ligera en horas tranquilas) + 1 Cocinero/a (1.400€ neto,
entra en horas de más movimiento) + 1 Ayudante de camarero/a (1.400€
neto, cubre los descansos de los tres anteriores) — hora punta máximo 3
personas a la vez, apertura/cierre siempre 1 persona sola. Camarero/a,
Ayudante de cocina y Jefe/a de cocina quedan en la tabla salarial a
tarifa de convenio como referencia para futuras contrataciones (0
personas hoy).

**Hecho:**
- `Tabla Salarial` reconstruida entera (antes: 10 filas de "CATEGORIA"
  genéricas con `#ERROR!` por comas decimales, 100% plantilla de otro
  cliente, sin datos reales). Nueva tabla: 4 puestos activos + 3 de
  referencia, Total Neto Mensual = **6.100€**, Coste empresa/mes =
  **8.113€** (con el 33% real), Coste empresa/año = **97.356€**.
  Corregido también un bug de formato (la columna de totales heredó
  formato de porcentaje del cliente anterior y mostraba "150000,00%" en
  vez de "1.500,00€").
- `Turnos` reconstruida como ficha operativa simple (antes: grid
  hora-por-hora de un restaurante con brigada de cocina completa de otro
  cliente — Chef/Runner/2 cocineros/Jefe cocina con turnos partidos,
  totalmente incompatible con el modelo de café de Casa Clementina).
  Nota transparente añadida: con 4 personas y 7 días abiertos, cuadrar
  2 descansos/semana para 3 puestos fijos con un solo Ayudante de
  camarero/a deja como máximo 1 día/semana algo más ajustado — no afecta
  al coste total, es decisión de cuadrante diario de la Manager, no del
  modelo financiero.
- `Datos!C52` ("% Seguridad Social + Impuestos"): corregido de **50%**
  (contaminación de otro cliente) a **33%** (dato real de Andrea).
- `Datos!C49/C50/C51` ("Costes Personal Neto AÑO 1/2/3"): antes
  `=Turnos!C8/C14/C22` (roto, `#REF!`, dependía del grid viejo) → ahora
  los tres apuntan a `='Tabla Salarial'!$D$14` (6.100€), misma plantilla
  los 3 años — asunción flageada: ajustar si Casa Clementina prevé
  contratar más personal según crecen las ventas.

**Resultado verificado:** Costes de personal ya da 8.113€/mes en las 3
Cuentas de Resultados; Retribuciones propias (6.100€) y Seguridad Social
(2.013€) ya dan cifras reales en las 3 Tesorerías. En el año 1, los
meses 1-8 de "Total costes" y "Beneficios/Pérdidas" **ya calculan de
verdad** (antes todo `#REF!`) — p.ej. Beneficio mes 1 = +180,26€, mes 7-8
(temporada baja) = -9.855,32€. El IVA trimestral también calcula ya en
los trimestres sin arrastre de Financiación (Q1 = 3.460,75€, Q2 =
4.333,38€).

**Único bloqueo que queda en todo el documento: la hoja `Financiación`**
(rota desde antes de esta sesión). Afecta: mes 9 en adelante del año 1,
y la totalidad de los años 2 y 3 (ahí "Costes financieros" está roto en
los 12 meses, no solo desde el mes 9). Bloquea en cascada: Costes
financieros y Cuota microcrédito en los 3 años, y por tanto Total
costes/Beneficios/Impuesto Sociedades/Beneficio Neto/Saldo de Tesorería
desde ese punto, y los trimestres de IVA que tocan el préstamo.

## Proyecciones — reconstruida entera 2026-10-20

Andrea pide calcular, en `Proyecciones`, el total de clientes de Ventas
Año 1 (Pesimista/Base/Optimista) con las franjas horarias y el ticket
medio reales, descartando las horas de tarde.

**Hallazgo:** la hoja estaba contaminada al 100% con el modelo de un
restaurante/bar de 24h de otro cliente — repetido 3 veces completas (una
por escenario): franjas desde "Breakfast 6:00" hasta "Late Night 02:00-
03:00" (con cena, afterwork y madrugada), tablas de gastos ("Shopping
30%, Staff 40%, Other Expenses 12,5% del Total Billing") y de "Monthly
Occupancy Rates" al 100% — nada de esto aplica a una cafetería de 8h sin
servicio de tarde. Limpiada por completo (filas 1-270, en 3 tramos por
el tamaño) y reconstruida desde cero:

- **TABLA RESUMEN** (Semanal/Mensual/Anual, IVA incluido): enlazada
  directamente a `Ventas!C7:N9` (Pesimista/Base/Optimista Año 1) y al
  ticket medio real (`Datos!C20`=12€) — nunca hardcoded, así que
  cualquier cambio futuro en Ventas se refleja solo. Verificado:
  Mensual Base = 26.460€ y Anual Base = 285.180€, coinciden exactamente
  con las cifras ya validadas en Cuenta Resultados/Tesorería.
- **3 tablas de reparto por franja horaria** (Pesimista/Realista/
  Optimista), solo con las franjas reales de la jornada de 8h: Apertura
  (8-10h), Media mañana (10-12h), Hora punta mediodía (12-14h), Cierre
  (14-16h) — sin tardeo, cena ni madrugada, como pidió Andrea.

**Asunción flageada (no es un dato de Andrea, hay que confirmarla o
ajustarla):** el reparto de clientes entre franjas es 20%/20%/40%/20%,
con más peso en la hora punta de mediodía — estimación propia de TBNB
consistente con la lógica de `Turnos` (coincide con el momento en que
hacen falta las 3 personas a la vez), no un dato real de afluencia por
hora de Casa Clementina. El horario exacto (8:00-16:00) también es una
asunción razonable sobre el "8h, cerrado por la tarde" ya confirmado,
nunca se fijó la hora exacta de apertura/cierre.

## Financiación — resuelto el último bloqueo del documento, 2026-10-20

Andrea confirma: **no hay préstamo real**, toda la inversión (244.712€)
se cubre con ahorros de las 3 socias. Lo que sí pide es calcular qué
necesitarían financiar (lo pendiente de pago + colchón de circulante
para aguantar la operativa) y qué opciones de préstamo hay.

**Diagnóstico confirmado:** la hoja `Financiación` tenía un préstamo
falso — "ICF" (120.000€, 6,5%, 84 meses) activo + "Microbank" (50.000€,
4,5%, 72 meses) inactivo. "ICF" = Institut Català de Finances, una
entidad que **solo financia en Catalunya** — contaminación clara de un
cliente de Barcelona, incompatible con "estamos en Madrid" que Andrea ya
había avisado. Además, un problema técnico aparte: la tabla de
amortización mensual solo tenía columnas hasta el mes 8 (la hoja solo
tenía 10 columnas en total) — de ahí el `#REF!` desde el mes 9 en
adelante y en los años 2-3 completos.

**Arreglado:**
- Desactivados Fin. 1 y Fin. 2 (`Activo=0`), vaciados sus datos falsos
  (nombre, importe, tipo de interés, duración) — quedan como slots
  disponibles para simular una opción real si se decide pedir
  financiación. Nota añadida en la propia hoja explicando la situación.
- Las 6 filas que dependían del grid roto ("Cuota microcrédito" en las 3
  Tesorerías, "Costes financieros" en las 3 Cuentas de Resultados) se
  redirigieron a `Financiación!$C$30` (la celda combinada, que ya da 0€
  correctamente) en vez del grid mensual roto — sin necesidad de tocar
  la estructura de columnas de la hoja.
- **Bug aparte detectado y corregido de nuevo:** `Datos!C52` (% Seguridad
  Social) había vuelto a estar en 50% en vez del 33% real que fijamos
  antes — no está claro si fue un cambio de Andrea al mirar el documento
  o algo más, se avisó y se corrigió otra vez.

**Resultado: todo el documento (Cuenta de Resultados, Tesorería e IVA,
los 3 años) calcula de principio a fin sin ningún `#REF!`.** Cifras
finales reales:

| | Año 1 | Año 2 | Año 3 |
|---|---|---|---|
| Beneficio Neto | 2.953,86€ | 9.226,40€ | 15.818,42€ |
| Saldo de caja mínimo del año | 11.787€ (mes 0) | 49.372,95€ (fin año) | 59.522,66€ (fin año) |
| Saldo de caja al cierre del año | 53.587,27€ | 102.960,22€ | 161.567,25€ |

**Hallazgo importante para la pregunta de Andrea:** con la plantilla y
costes actuales, **el Saldo Acumulado de Tesorería nunca baja del nivel
inicial en ningún mes de los 3 años** — crece de forma sostenida desde
los 11.787€ del mes 0. Es decir, **para la operativa del día a día no
hace falta financiación externa adicional**, los 20.000€ de provisión de
fondos ya son suficientes como colchón.

**Pendiente real para terminar el análisis de "lo pendiente":** en
`Inversión inicial`, 5 partidas de gastos de apertura siguen en 0€,
marcadas "PENDIENTE — falta cifra real": Food cost inicial, Take away
(packaging), Menaje, Utensilios de cocina, Material de oficina. Estas sí
son gastos reales sin pagar todavía y sin cifra — sin ellas no se puede
calcular "lo que necesitaríamos pedir para abrir con lo pendiente".
Preguntado a Andrea.

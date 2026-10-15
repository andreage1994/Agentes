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

## Gap analysis — qué falta antes de avanzar (para la reunión de hoy)

1. **Fijar una única cifra de inversión** (hay cuatro circulando:
   190.962€ solo obra, 239.561€ total pagado, 61.014€ pendiente, y
   276.125€ usado en el borrador de escenarios) — sin esto no se puede
   construir ni el Investment Plan ni el Viability Analysis del
   informe real.
2. **Traspaso: confirmar si es una vía real.** Depende de la aprobación
   de Panadario (arrendador principal), que todavía no ha sido
   consultado. El informe debería, como mínimo, señalar esta
   incertidumbre como riesgo — y sería mucho mejor si en la reunión de
   hoy se pregunta si ya se ha sondeado a Panadario, aunque sea
   informalmente.
3. **Validar el archivo `Abierto_Todos_Los_Dias.xlsx`**: ¿es la base de
   partida aprobada o un borrador a descartar/revisar? Si se mantiene,
   hay que reconciliar su cifra de inversión (276.125€) con las cuatro
   de arriba, y confirmar si el ticket medio creciente (7€→8,50€) y los
   10.900€/mes de gastos fijos están validados o son solo hipótesis de
   trabajo.
4. **Precio real del proyecto acústico de Absotec** — no viene en el
   documento compartido.
5. **Socios:** no hay ningún documento de pacto de socios ni reparto de
   capital en la carpeta. Si el informe tiene que ayudar a decidir
   entre socios, conviene saber cuántos son y cómo se reparte la
   decisión/el capital, aunque sea a nivel general.
6. **Hipótesis comerciales que pide el índice oficial y que no veo
   confirmadas en ningún documento:** aforo/número de cubiertos real
   del local, horario y días de apertura definitivos (el nombre del
   archivo de escenarios sugiere "todos los días" pero no sé si es el
   plan decidido o una opción a evaluar frente a otras), mix de ventas
   por línea (comida/bebida/delivery — el P&L ya trae esas filas,
   vacías), estacionalidad más allá de las variaciones mes a mes ya
   intuidas en el borrador.
7. **Plantilla de personal:** las pestañas "Turnos" y "Tabla Salarial"
   del modelo maestro están vacías — hace falta saber plantilla
   prevista (puestos, nº personas) y convenio/salario de referencia
   para completar costes de personal reales, más allá de la cifra
   genérica de "sueldos" que aparece en pagos pendientes.
8. **Limpiar la plantilla antes de usarla con el cliente:** la pestaña
   en italiano del modelo maestro, y la frase suelta sin terminar en el
   pptx (sección 8) — higiene de plantilla, no bloquea avanzar pero
   conviene revisarlo antes de compartir nada con Fuensanta/Lucia.

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

1. Reunión de hoy con Fuensanta/Lucia: usar el gap analysis de arriba
   como guion de preguntas.
2. Una vez resueltos los huecos de dato real (sobre todo el 1 y el 2),
   empezar a rellenar el modelo maestro de Proyección Financiera con
   `financiero-modelizacion`.
3. Construir el Business Viability Report con `financiero-viabilidad`
   una vez el modelo tenga números reales y validados.
4. Pasar todo por `financiero-contable-revision` antes de entregar nada
   al cliente.

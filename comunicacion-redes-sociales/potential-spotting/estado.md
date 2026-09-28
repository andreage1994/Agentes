# Estado — Potential Spotting

**Fecha de arranque:** 2026-09-28.

## Situación actual

Proyecto y equipo creados. Documentación de partida lista:
`parametros-filtro.md` (los 4 filtros de digital spotting dados por
Andrea), `plantilla-notas-desde-la-barra.md` (estructura del documento a
partir del caso de referencia La Greca) y `email-envio-notas.md` (plantilla
de email, en dos variantes según si hay visita física o no).

Primera tanda de digital spotting (Barcelona + Madrid) completada por
`potential-spotting-research` el 2026-09-28. Se identificaron 5 candidatos
que superan los filtros 1-2 con datos verificables (dos de ellos con
salvedades explícitas de dato en el filtro 3 o en la fuente de la nota —
ver fichas individuales). Quedan excluidos de esta lista, por instrucción
expresa, los locales ya en el radar de TBNB: La Muriel, El Velódromo, Can
Xurrades, La Principal, Casa Amalia, La Greca, Jaç Hi-Fi, Maldita Barra,
Parking Pizza/Pita, Bar Vereda, Kibuka, Saga Coffee, ATAV, SIAM, Casa Platos.

Otros locales explorados y descartados en esta tanda por no superar los
filtros 1-3 con confianza razonable (se documentan aquí para no repetir
trabajo en la próxima ronda, no tienen ficha propia):

- **Bar Alegria Gràcia** (Barcelona) — concepto muy reciente con crítica de
  prensa explícita sobre precio/valor ("el peor bar de Gràcia", ElNacional),
  pero no fue posible confirmar con confianza razonable un rating o número
  de reseñas específico de esta dirección (los datos encontrados se
  refieren de forma ambigua a otras direcciones de la misma marca). Revisar
  en una próxima ronda si ya tiene ficha propia consolidada en Google/TripAdvisor.
- **Bar Casi, Bar Trafalgar, Insolent (Gràcia), Bolboreta** — rating
  confirmado pero por encima de 4,5 sin patrón negativo claro que lo
  justifique dentro del filtro 2.
- **Snake Bar, Indomable, Devil's Cut, Casa Osorio, Frecuencia, Esotérica,
  Osteria Condal, Jazminos, Melós** — demasiado recientes para tener volumen
  de reseñas verificable (bajo o inexistente).
- **Cohete y Gamberro Barra Canalla (Goya)** — sí tienen ficha (ver tabla),
  pero con salvedad explícita: su rating proviene de un agregador con escala
  0-10 (GastroRanking), no de una nota de Google/TripAdvisor en escala 0-5
  confirmada de forma independiente.

`potential-spotting-estrategia` revisó los 5 candidatos el 2026-09-28 y
tomó las dos decisiones que `research` había dejado pendientes:

- **Gamberro Taberna Canalla (Olavide) y Gamberro Barra Canalla (Goya)**
  son la misma marca y propiedad (Grupo Barbillón). Se decide tratarlos
  como **una sola conversación**, anclada en Olavide (evidencia de tipo de
  oportunidad mucho más sólida y con más volumen de reseñas). Goya **no
  genera nota ni documento propio** — su única cita de evidencia ("la única
  pega el precio") es demasiado débil y contradicha por otra opinión
  positiva sobre las raciones; forzar un bloque 3 con eso habría incumplido
  la regla de no fabricar una observación genérica. Puede mencionarse como
  contexto una vez avance la conversación con Olavide.
- **Cohete** pertenece a Grupo Tragaluz, una cadena de restauración grande
  y ya consolidada, no un proyecto independiente con margen de crecimiento.
  Se decide **no priorizarlo ni pasar a redacción**: no encaja con el
  espíritu de "Notas desde la Barra" tal como está definido, más allá de
  que la evidencia de oportunidad (EXPERIENCE/ruido) sea honesta y válida.
  Queda documentado por si en el futuro TBNB decide abrir conversación
  también con grupos consolidados, pero es una decisión de negocio que no
  corresponde asumir aquí.

`potential-spotting-redaccion` redactó el 2026-09-28 el documento "Notas
desde la Barra" y el email de envío (variante B, digital spotting) para los
3 candidatos priorizados, en el mismo orden de contacto que dejó
estrategia:

1. **Malparit** (Barcelona) — patrón SERVICE sostenido por tres reseñas
   independientes. Documento: `candidatos/malparit-barcelona-notas.md`.
   Email: `candidatos/malparit-barcelona-email.md`.
2. **Gamberro Taberna Canalla, Olavide** (Madrid) — patrón SERVICE sostenido
   por el mayor volumen de reseñas de la tanda (796) y una cita de prensa
   que resume el ángulo casi textualmente. Documento:
   `candidatos/gamberro-taberna-canalla-olavide-madrid-notas.md`. Email:
   `candidatos/gamberro-taberna-canalla-olavide-madrid-email.md`.
3. **Casa Fiero** (Barcelona) — patrón CONCEPT muy bien articulado en una
   única reseña extensa, pero con volumen de reseñas bajo (14); prioridad
   moderada a la espera de que acumule más reseñas. Documento:
   `candidatos/casa-fiero-barcelona-notas.md`. Email:
   `candidatos/casa-fiero-barcelona-email.md`.

Los 3 son borradores. **Ninguno se envía** hasta que Andrea o Sergio los
revisen, personalicen (nombre del contacto, firma) y aprueben, tal como
fija `CLAUDE.md`.

Ver el detalle de ángulo (bloques 2 y 3) y variante de contacto en la
sección "Estrategia" de cada ficha original (`candidatos/<slug>.md`).

## Hoja de cálculo (Drive)

La hoja original "Potential spotting" en Drive tenía mucha información
duplicada (la tabla de Fases repetida 3 veces, dos listas de contactos casi
idénticas, notas de cada local con formato inconsistente). Se creó una
versión reestructurada, **"Potential Spotting v2 (reestructurado)"**
(<https://docs.google.com/spreadsheets/d/1YrQDrJRhJh2evjcTZhdIZO_NMlEKQT7mr2ZnOhgTPKA/edit>),
en la misma carpeta de Drive, con 4 pestañas en vez de 7:

- **Pipeline** — una fila por local (sustituye a `Base datos` + `DIGITAL
  SPOTTING`), ya con los 5 candidatos nuevos de esta tanda de digital
  spotting.
- **Fases** — la tabla de las 6 fases una sola vez, con las dos frases de
  posicionamiento de TBNB arriba.
- **Plantillas** — el email real (dos variantes) y la plantilla en blanco
  de "Notas desde la Barra", cada uno en su sitio.
- **Notas** — pestaña lista para recibir cada "Nota desde la Barra" ya
  redactada, en vez de una pestaña suelta por local con formato distinto.

Es una propuesta para que Andrea/Sergio la revisen — la hoja original no se
ha tocado ni borrado.

## Seguimiento de candidatos

Se rellena a medida que `potential-spotting-research` identifica locales.
Fases: 🟡 Investigado → 🟡 Priorizado (estrategia) → 🟡 Nota redactada →
🟡 Revisión Andrea/Sergio → 🟢 Enviado. También puede cerrarse en
🔴 No se prioriza, cuando estrategia decide explícitamente no llevar un
candidato a redacción.

| Local | Ciudad | Fase | Tipo de oportunidad | Notas |
|---|---|---|---|---|
| Malparit | Barcelona | 🟡 Nota redactada — pendiente de revisión de Andrea/Sergio | SERVICE (dominante) / CONCEPT-FOOD (secundario) | Rating 4,0/5 TripAdvisor, 44 reseñas (justo bajo el umbral de 50). Ficha: `candidatos/malparit-barcelona.md`. Documento y email: `candidatos/malparit-barcelona-notas.md` / `candidatos/malparit-barcelona-email.md`. |
| Casa Fiero | Barcelona | 🟡 Nota redactada — pendiente de revisión de Andrea/Sergio | CONCEPT (dominante) / FOOD (secundario) | Rating 3,9/5 TripAdvisor, solo 14 reseñas (no cumple filtro 3 formalmente, incluido como excepción justificada). Ficha: `candidatos/casa-fiero-barcelona.md`. Documento y email: `candidatos/casa-fiero-barcelona-notas.md` / `candidatos/casa-fiero-barcelona-email.md`. |
| Gamberro Taberna Canalla (Olavide) | Madrid | 🟡 Nota redactada — pendiente de revisión de Andrea/Sergio | SERVICE (dominante) / FOOD (secundario) | Rating 4,0/5 (RestaurantGuru), 796 reseñas. Conversación ancla para el Grupo Barbillón. Ficha: `candidatos/gamberro-taberna-canalla-olavide-madrid.md`. Documento y email: `candidatos/gamberro-taberna-canalla-olavide-madrid-notas.md` / `candidatos/gamberro-taberna-canalla-olavide-madrid-email.md`. |
| Gamberro Barra Canalla (Goya) | Madrid | 🔴 No se prioriza (sin nota independiente) | CONCEPT (evidencia demasiado débil) | Misma marca que Olavide (Grupo Barbillón); evidencia de oportunidad insuficiente para sostener un bloque 3 propio. Se integra como contexto en la conversación de Olavide, no genera documento ni email propio. Ver `candidatos/gamberro-barra-canalla-goya-madrid.md` (sección Estrategia). |
| Cohete | Barcelona | 🔴 No se prioriza | EXPERIENCE (dominante) / SERVICE (secundario, débil) | Grupo Tragaluz — cadena de restauración consolidada, no encaja con el espíritu de "Notas desde la Barra" (proyectos independientes con potencial, no cadenas ya establecidas). Rating solo disponible en escala GastroRanking 0-10. Ver `candidatos/cohete-barcelona.md` (sección Estrategia). |

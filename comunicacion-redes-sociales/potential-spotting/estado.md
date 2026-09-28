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
🟡 Revisión Andrea/Sergio → 🟢 Enviado.

| Local | Ciudad | Fase | Tipo de oportunidad | Notas |
|---|---|---|---|---|
| Malparit | Barcelona | 🟡 Investigado | SERVICE (dominante) / CONCEPT-FOOD (secundario) | Rating 4,0/5 TripAdvisor, 44 reseñas (justo bajo el umbral de 50). Ver `candidatos/malparit-barcelona.md`. |
| Casa Fiero | Barcelona | 🟡 Investigado | CONCEPT (dominante) / FOOD (secundario) | Rating 3,9/5 TripAdvisor, solo 14 reseñas (no cumple filtro 3 formalmente, incluido como excepción justificada). Ver `candidatos/casa-fiero-barcelona.md`. |
| Gamberro Taberna Canalla (Olavide) | Madrid | 🟡 Investigado | SERVICE (dominante) / FOOD (secundario) | Rating 4,0/5 (RestaurantGuru), 796 reseñas. Ver `candidatos/gamberro-taberna-canalla-olavide-madrid.md`. |
| Gamberro Barra Canalla (Goya) | Madrid | 🟡 Investigado | CONCEPT (evidencia débil) | Misma marca que el anterior (Grupo Barbillón); rating solo disponible en escala GastroRanking 0-10. Ver `candidatos/gamberro-barra-canalla-goya-madrid.md`. |
| Cohete | Barcelona | 🟡 Investigado | EXPERIENCE (dominante) / SERVICE (secundario, débil) | Grupo Tragaluz (cadena consolidada, no negocio independiente pequeño — señalado para estrategia). Rating solo disponible en escala GastroRanking 0-10. Ver `candidatos/cohete-barcelona.md`. |

# potential-spotting/

Detección de restaurantes y bares con potencial para convertirse en clientes
de TBNB, a través de dos vías:

1. **Spotting físico** — restaurantes que Andrea o Sergio visitan en persona y
   que les inspiran. Da lugar a un documento "Notas desde la Barra" genuino,
   nacido de una visita real.
2. **Digital spotting** — búsqueda activa de bares y restaurantes en
   Barcelona o Madrid a partir de datos públicos (rating, nº de reseñas,
   antigüedad, contenido de las reseñas), filtrados según los parámetros de
   `parametros-filtro.md`, sin que medie necesariamente una visita física.

**Importante — honestidad en el digital spotting:** cuando el contacto nace
de spotting digital, sin visita física, el documento y el email que lo
acompaña no deben dar a entender que Andrea o Sergio han estado en el local
si no es cierto — regla de la casa (`CLAUDE.md`: "honesto y nada agresivo en
ventas"). Ver la nota sobre esto en `plantilla-notas-desde-la-barra.md`.

## Cómo está organizada esta carpeta

- `README.md` — este documento.
- `parametros-filtro.md` — los 4 filtros que definen qué locales encajan
  como oportunidad de digital spotting, y cómo clasificar su "tipo de
  oportunidad" a partir de las reseñas.
- `plantilla-notas-desde-la-barra.md` — estructura y tono del documento
  "Notas desde la Barra" (formato de 5 bloques), a partir de la plantilla de
  referencia compartida por Andrea (caso La Greca, Barcelona, sept. 2026).
- `email-envio-notas.md` — plantilla del email para acompañar el envío de un
  documento "Notas desde la Barra" a un potencial cliente.
- `candidatos/` — fichas de locales identificados por digital spotting, cada
  uno con su ficha de filtros y su "tipo de oportunidad".
- `estado.md` — seguimiento del proceso.

## El equipo

Tres roles (`.claude/agents/`), en cascada:

1. **`potential-spotting-research`** — hace el digital spotting: busca
   locales en Barcelona/Madrid que cumplan los filtros de antigüedad,
   rating y nº de reseñas, y clasifica su "tipo de oportunidad" (Service /
   Experience / Concept / Food) a partir del contenido real de sus reseñas.
   No decide a quién contactar ni escribe nada de cara al cliente.
2. **`potential-spotting-estrategia`** — con la lista de candidatos ya
   investigada, decide prioridad de contacto, qué ángulo tiene sentido para
   cada uno (qué observación positiva liderar, qué "nos hizo pensar" es
   defendible con las reseñas reales) y vigila que el enfoque no se convierta
   en señalar errores — coherente con la propia filosofía del documento
   ("no son auditorías, no buscan señalar errores").
3. **`potential-spotting-redaccion`** — escribe el documento final "Notas
   desde la Barra" de cada candidato priorizado, siguiendo la plantilla y el
   tono de marca, y el email que lo acompaña.

**Regla del manual de la casa que sigue aplicando aquí, sin excepción:**
nada se envía a un potencial cliente sin que Andrea o Sergio lo aprueben
antes — ni el documento "Notas desde la Barra" ni el email. Todo lo que
produce este equipo es borrador para revisión, nunca envío directo.

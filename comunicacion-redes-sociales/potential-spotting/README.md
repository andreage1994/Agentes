# potential-spotting/

**Cambio de rumbo (2026-10-05, pedido por Andrea):** el modelo original de
este proyecto (digital spotting por reseñas → "Notas desde la Barra" con un
bloque de observación de mejora) **queda en pausa**. Cero respuestas tras
varias rondas de contacto real llevaron a Andrea/Sergio a concluir que,
aunque el tono fuera cuidado, diagnosticar algo mejorable a un desconocido
en frío sigue sintiéndose agresivo y no aporta el valor esperado. El nuevo
enfoque prioritario es **contacto directo para construir relación** —
proponer un café a profesionales, dueños y fundadores del sector, compartir
punto de vista, sin ningún diagnóstico ni crítica. Ver plantilla nueva en
`email-contacto-cafe.md`. El trabajo de digital spotting ya hecho
(`candidatos/`, fichas y borradores de "Notas desde la Barra") se conserva
sin borrar, por si en el futuro se retoma con otro enfoque — pero no se
genera contenido nuevo con ese modelo mientras no se decida lo contrario.

---

Detección de restaurantes y bares con potencial para convertirse en clientes
de TBNB, a través de dos vías (modelo original, en pausa — ver nota arriba):

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
  documento "Notas desde la Barra" a un potencial cliente (modelo en pausa).
- `email-contacto-cafe.md` — plantilla nueva (2026-10-05): contacto directo
  para proponer un café, sin diagnóstico ni documento adjunto. Vía principal
  de contacto en frío a partir de ahora.
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
antes — ni el documento "Notas desde la Barra" ni ningún email, incluido
`email-contacto-cafe.md`. Todo lo que produce este equipo es borrador para
revisión, nunca envío directo.

**Nota sobre los tres roles anteriores, mientras dure la pausa:** no se les
encarga trabajo nuevo con el modelo de digital spotting/"Notas desde la
Barra". Si en el futuro hace falta investigar a quién contactar para el
nuevo modelo de café (afinidad genuina, no patrón de reseñas negativas),
se decide entonces si se reutiliza alguno de estos roles o se define uno
nuevo — no se asume automáticamente.

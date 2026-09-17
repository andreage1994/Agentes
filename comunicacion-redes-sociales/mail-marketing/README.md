# mail-marketing/

Plantillas y contenido de email marketing para Mailchimp, a partir de la
estructura de flujos ya definida en `MAILMARKETING X TBNB.xlsx` (Drive,
carpeta "5. Marketing").

## Identidad de marca usada

Basada en `Manual_marca.pdf` (agencia eleyuve, 2024) — **no** en el brand kit
conectado en Canva, cuyos colores (burgundy/rosa/lavanda) no coinciden con la
marca real de TBNB y se descartaron como fuente para este trabajo.

- **Tipografías:** titulares en Helvetica Neue Bold (fallback web: Arial
  Black / Arial / sans-serif, ya que Helvetica Neue no está garantizada en
  todos los clientes de correo); cuerpo y etiquetas en Epilogue (Google Font,
  con fallback a Arial/Helvetica si el cliente de correo no carga fuentes web
  — la mayoría de clientes de Gmail/Outlook no lo hacen, así que el texto se
  verá en Arial en muchos casos, esto es normal y esperado en email).
- **Paleta vibrante** (una por etapa del funnel, para diferenciar visualmente
  cada flujo dentro de la misma identidad):
  - TOFU (Bienvenida/Nutrición) → `#33B086` eat this green
  - MOFU (Consideración) → `#009FE3` le bleu
  - BOFU (Conversión) → `#E94A4B` red bar
  - Reactivación → `#F3A038` tangerina
  - Newsletter (Campaña) → `#A890C3` lilacocktail
- **Neutrales:** blanco `#FFFFFF`, gris claro `#EDEDED`, negro mate `#1D1D1B`
  (cabecera y footer).
- **Logo:** wordmark "the BAR'n'BAR" con la "n" en el color de acento de cada
  plantilla — en el manual de marca la "n" es precisamente el elemento
  variable del logotipo, así que este uso es coherente con el sistema de
  marca, no una licencia nuestra.

## Archivos

- `plantilla-flujo-automatizacion.html` — plantilla maestra para los emails
  de automatización (TOFU, MOFU, BOFU, Reactivación): eyebrow + titular +
  cuerpo + botón CTA opcional + footer. Instrucciones de uso e importación a
  Mailchimp dentro del propio archivo (comentario al principio del HTML).
- `plantilla-newsletter.html` — plantilla para la newsletter mensual
  (Campaña): 3 fichas "leer más" + 1 ficha destacada de "novedad del mes".
- `contenido-emails.md` — todo el copy ya redactado en el excel, listo para
  pegar en las zonas editables (`mc:edit`) de cada plantilla, organizado por
  flujo y variante.

## Alcance de esta primera tanda

Incluye: TOFU (5 emails, varias variantes por interés) · MOFU (3 emails) ·
BOFU (2 emails) · Reactivación (2 emails) · Newsletter mensual (plantilla +
ejemplo del mes).

**No incluye — por decisión explícita de Andrea (2026-09-17):** el flujo
POST-VENTA / Onboarding cliente (3 emails, filas 25-27 del excel, marcadas en
rojo). Son emails a clientes ya firmados, no a leads, y se decidirá aparte si
necesitan el mismo diseño de captación.

## Antes de activar en Mailchimp

1. Importar ambas plantillas como "Code your own" → "Paste in code".
2. Rellenar cada zona `mc:edit` con el contenido correspondiente de
   `contenido-emails.md`.
3. Resolver los dos placeholders pendientes marcados en `contenido-emails.md`
   (`[interés seleccionado]` necesita un merge tag real; `[Nombre, Negocio]`
   del testimonio de BOFU #2 necesita un testimonio real con permiso, o
   quitar esa línea).
4. Configurar el asunto y el "preview text" nativos de la campaña en
   Mailchimp con los mismos textos de cada ficha (el bloque oculto del HTML
   es un refuerzo, no sustituye el campo nativo).
5. Como siempre en la casa: nada se activa ni se envía sin que Andrea o
   Sergio lo revisen antes.

## Pendiente / siguiente paso sugerido

- Decidir si se quiere un 4º color de acento distinto para diferenciar aún
  más "Reactivación" de "BOFU" en la bandeja de entrada (hoy usan tangerina y
  rojo respectivamente, ya son distintos, pero conviene revisarlo una vez se
  vean los emails renderizados en Mailchimp).
- Configurar en Mailchimp los tags/segmentos que activan cada automatización
  (double opt-in, interés seleccionado, tag CLIENTE ACTIVO, etc.) — esto es
  configuración de la propia herramienta, no de las plantillas.

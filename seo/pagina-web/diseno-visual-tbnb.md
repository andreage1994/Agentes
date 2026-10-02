# Diseño visual TBNB — referencia real de la web

**Fuente principal:** grabación de pantalla de la página real
`thebarnbarconsulting.com/bar-method/`, compartida por Andrea (2026-09-29)
— es la página que Andrea señala como "la página de los servicios". Las
capturas de referencia están en `seo/pagina-web/referencia-visual/`.

**Fuente secundaria:** `Document Design System TBNB.xlsx` (Drive) — libro
pensado para documentos/decks internos, no para la web, pero su paleta de
color coincide con lo que se ve realmente en el sitio (confirmado al
comparar). Se usa aquí solo como referencia de nombres/hex de marca.

## Paleta de color (confirmada visualmente contra la web real)

| Nombre | Hex aprox. | Dónde se usa en la web real |
|---|---|---|
| **red bar** | `#E94A4B` | Barra de anuncio superior, CTAs principales ("Descubre el BAR Method", "Reserva una llamada"), tarjeta "B — Breakdown", subrayado del ítem de menú activo, iconos de contacto en el footer |
| **tangerina** | `#F3A038` | Tarjeta "A — Architecture", sección "Caso de éxito" (fondo naranja) |
| **lemon icon** | `#FCE312` | Tarjeta "R — Run", sección CTA final ("El siguiente paso") |
| **lilacocktail** | `#A890C3` | Chevron/flecha decorativa entre secciones, tarjeta de testimonio en el caso de éxito |
| **le bleu** | `#009FE3` | Barra superior de la tarjeta comparativa "¿De dónde partimos?" |
| **eat this green** | teal/verde | Acento en el logotipo (la "n" de "BAR'n'BAR") |
| **negro** | `#0B0B0B` aprox. | Fondo de la sección hero y de "Nuestro método" (secciones oscuras) |
| **blanco / gris claro** | `#FFFFFF` / `#EDEDED` | Fondos de sección alterna, tarjetas neutras |

**Patrón de uso real:** cada sección grande tiende a tener **un color de
fondo dominante y saturado** (negro, naranja, amarillo) que ocupa todo el
ancho, alternando con secciones en blanco — no se mezclan varios colores
saturados dentro de la misma sección salvo en bloques pequeños (tarjetas).

## Tipografía observada

- **Titulares:** sans-serif de peso bold/black, minúsculas o frase normal
  (no todo mayúsculas salvo en eyebrows/etiquetas cortas como "TU
  SITUACIÓN", "CASO DE ÉXITO", "NUESTRO MÉTODO", "QUIÉNES SOMOS").
- **Eyebrows** (etiqueta corta encima del H2): mayúsculas, letter-spacing
  amplio, tamaño pequeño, en el color de acento de la sección.
- **Cuerpo:** sans-serif regular, buen contraste, párrafos cortos.

## Patrones reales de sección (para especificar maquetación en Elementor)

Observados en `/bar-method/`, de arriba a abajo:

1. **Barra de anuncio** (rojo, full-width, texto centrado + selector ES/EN).
2. **Header** — logo a la izquierda, menú horizontal centrado-derecha
   (Bar Method · Equipo · Proyectos · Traspasos · Blog), botón "CONTACTO"
   con borde a la derecha.
3. **Hero split** — fondo negro. Izquierda: 3 cuadrados de color
   decorativos, H1 grande en blanco, párrafo gris claro, botón CTA rojo.
   Derecha: tarjeta de imagen con overlay "CASO DE ÉXITO" + titular +
   resultado (carrusel con puntos de paginación).
4. **Comparativa de situación** ("¿De dónde partimos?") — tarjeta con
   barra superior de color (azul), dividida en 2 columnas por una línea
   vertical: una situación a la izquierda, otra a la derecha, cada una con
   eyebrow + H3 + texto. Patrón reutilizable para "dos perfiles de
   cliente" (ideal para diferenciar, por ejemplo, quien quiere abrir vs.
   quien ya tiene el negocio).
5. **Bloque de 3 tarjetas de color** ("BAR method": Breakdown/rojo,
   Architecture/naranja, Run/amarillo) sobre fondo negro — cada tarjeta es
   una forma tipo "nota adhesiva" con muesca en la esquina inferior,
   letra grande (inicial) + eyebrow + texto.
6. **Bloque de confianza/checklist** sobre fondo negro, con una lista de
   puntos y un CTA final ("Reserva una llamada").
7. **Caso de éxito** — sección de color sólido (naranja), 2 columnas:
   cifras grandes destacadas (p. ej. "+100.000 € de facturación en 6
   meses") a la izquierda con líneas separadoras, texto explicativo +
   tarjeta de cita (fondo lila) + tarjeta de insight (fondo rojo) a la
   derecha, botón "Ver caso completo →".
8. **Quiénes somos** — fondo blanco, imagen de persona real a la
   izquierda (con forma orgánica de color detrás), titular + párrafo +
   2 citas de founders (foto circular + nombre + cargo) + botón
   "Conócenos →".
9. **CTA final** — fondo amarillo, titular + párrafo explicando la llamada
   de 15 minutos + botón "AGENDAR CITA", con elemento gráfico (sticker
   "HELLO", forma orgánica, imagen).
10. **Banner de marquesina** (franja roja con texto en movimiento
    horizontal) para una llamada a la acción secundaria (en este caso,
    traspasos) — patrón reutilizable para destacar otro servicio.
11. **Footer** — 3 bloques de contacto (móvil, email, dirección) con
    icono circular rojo, logo, logos de subvenciones/certificaciones
    (Kit Digital, red.es, UE), iconos sociales, copyright y enlaces
    legales.

## El CTA de 15 minutos — confirmado por Andrea (2026-09-29)

**"Es nuestra estrella polar y cómo convertimos leads en clientes."** No
es una pregunta abierta: es real, está operativo y es el CTA principal de
conversión de todo el sitio. Ya existe en `/bar-method/` con esta redacción
exacta:

> "Una conversación de 15 minutos. Sin compromiso. Para entender dónde
> estás, qué te está frenando y si tiene sentido que trabajemos juntos.
> Si creemos que podemos ayudarte, te diremos cómo. Y si no, te lo decimos
> también."
>
> Botón: **AGENDAR CITA**

Los briefs del SEO proponen el texto de botón "AGENDAR REUNIÓN GRATUITA DE
15 MINUTOS" para las páginas nuevas — es coherente con lo que ya existe;
`web-redaccion` puede usar cualquiera de las dos variantes de texto de
botón, pero el mensaje de fondo (conversación de 15 min, sin compromiso,
honestidad de "si no podemos ayudarte, te lo decimos") debe ser el mismo
que ya vive en `/bar-method/`, no uno nuevo inventado.

## Datos reales de contacto (footer, para si hace falta citarlos)

- Móvil: +34 688 927 438
- Email: info@thebarnbarconsulting.com
- Dirección: Carrer Torrent de l'Olla 33, Gràcia, 08012 Barcelona

## Nota para quien maquete en Elementor

Esta guía describe patrones observados en una grabación de pantalla, no
sustituye abrir el editor de Elementor real para reutilizar los bloques
guardados/globales que ya existen en el sitio. Antes de construir nada
nuevo, comprobar si alguno de estos 11 patrones ya existe como bloque
reutilizable en la librería de Elementor del sitio.

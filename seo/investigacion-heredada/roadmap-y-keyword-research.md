# Investigación heredada de Saúl Felipe Cortés (colaborador de SEO externo)

Fuente: Google Drive, hoja de cálculo `2026_The Bar N Bar_Roadmap y primeros
accionables` (propietario: saulfelipecortes@gmail.com). **Confirmado por
Andrea (2026-10-02): Saúl era el colaborador externo que llevaba el SEO de
TBNB, despedido hoy mismo — `seo-estrategia-senior` toma su rol directamente
a partir de ahora, no queda nadie más externo tocando SEO.** Enlace:
https://docs.google.com/spreadsheets/d/1G3XD_j52MdAIoVRHTI6y_nUhlNyBfoarZz2r9zgi034

Este documento resume su estructura y decisiones ya tomadas; para el detalle
fila a fila (145 keywords, arquitectura completa) consultar directamente la
hoja — no se duplica aquí para evitar que esta copia quede desactualizada.

## Pestaña "Roadmap" — estado de las acciones

| Acción | Prioridad | Estado |
|---|---|---|
| Keyword Research | Alta | **Implementado** |
| Favicon | Media | **Implementado** |
| Arquitectura web y definición optimizaciones/nuevas URLs | Alta | **Implementado** |
| Análisis y limpieza técnica del site (enlazado, 4xx/3xx, robots.txt, sitemap.xml) | Alta | Pendiente |
| Definición de prompts de negocio y análisis (IA) | Media | Pendiente |
| Análisis del blog | Media | Pendiente |
| Mejoras de plantillas (Home, Servicios y Artículos) | Media | Pendiente |
| Propuesta de datos estructurados e implementación | Media | Pendiente |
| Comité de contenidos (2-3/mes) | Media | Pendiente |

Tareas "Always On" listadas sin detalle de cadencia: tracking de keywords,
comité de contenidos, revisiones pre/pro, monitorización de datos.

**Nota sobre el favicon:** figuraba como "Implementado" en esta hoja, y el
briefing de Andrea (punto 13 de su priorización) parecía contradecirlo —
**confirmado por Andrea que el favicon ya está resuelto**, el punto 13 de su
briefing quedaba desactualizado. No es tarea pendiente.

## Pestaña "Keyword research [WIP]" — 145 keywords

Columnas: Funnel (Conversión/Consideración) · Localidad · Target · Servicio ·
Keyword · Búsquedas mensuales · Posición 08/2026 · URL del nº1 actual.

Patrones observados en la muestra:
- Fuerte peso de **Traspasos** por ciudad (Barcelona, Zaragoza, Valencia,
  Madrid, Sevilla) — ej. "traspaso bar barcelona" (1.600 búsquedas/mes, la
  keyword de mayor volumen de toda la hoja), "traspaso restaurante
  barcelona" (880), "traspaso bar zaragoza" (880).
- Keywords de marca/servicio nacional (Consultoría, Asesoría, Marketing,
  Apertura) casi todas marcadas **"Not Ranked (Top 10)"** en la columna de
  posición — es decir, en la mayoría de términos de negocio TBNB todavía no
  aparece en la primera página de Google.
- Las pocas excepciones con posición real: "asesoria hosteleria barcelona"
  (posición 2) y "asesoria hosteleria" a nivel nacional (posición 5) — los
  únicos indicios de que ya hay algo de tracción.
- Para cada keyword sin posicionar se incluye la URL del competidor que sí
  ocupa el nº1 — material directo para el análisis de competencia que pide
  el punto 7 del briefing de Andrea.

## Pestañas "Arquitectura web [WIP]" y "Arquitectura web v2 [WIP]"

Dos versiones (la v2 es la más reciente/refinada) de una propuesta de
arquitectura en silos. Estructura principal detectada:

| Silo | URL sugerida | ¿Existe ya? | Keyword principal | Búsquedas/mes |
|---|---|---|---|---|
| Core | `/` (Home) | Sí | consultoria hosteleria / asesoria hosteleria | 960 |
| Servicios Core | `/consultoria-gastronomica/` | **No** | consultoria gastronomica | 500 |
| Servicios Core | `/marketing-gastronomico/` | Sí | marketing para restaurantes | 700 |
| Servicios Core | `/traspasos/` | Sí | valoracion traspaso bar | 50 (hub, alimenta sub-landings de Madrid/Barcelona) |
| Silo Servicios | `/asesoria-hosteleria/` | — | asesoria hosteleria | 470 |
| Silo Emprendimiento | `/abrir-restaurante-bar/` | Sí | como abrir un restaurante | 270 |

Cada fila trae también Title, H1 y Meta descripción ya redactados (en
mayúscula/minúscula de borrador) y un comentario estratégico. Dos ejemplos
literales de esos comentarios, porque son decisiones de fondo, no solo de
formato:

- Sobre la Home: *"URL Pilar Única. Absorbe 'consultoria hosteleria' (490) y
  'asesoria hosteleria' (470) para consolidar autoridad de dominio y evitar
  la canibalización en el TOP 5."*
- Sobre `/consultoria-gastronomica/` (página que no existe todavía): *"Fusiona
  'consultoría gastronómica' (320) y 'asesor gastronómico' (110). Integra
  módulos para Ingeniería de Menú (110 búsq), Pastelería/Postres (Elena/Yair)
  y Sumillería/Bodega (Aleix)."* — **Nombres completos confirmados** vía
  `../../equipo-tbnb.md` (bios reales de TBNB, aportadas por Andrea el
  2026-10-02): **Elena Reis** y **Yair Idanza**, colaboradores externos de
  pastelería (mismo modelo que los "Servicios Complementarios" con partners
  del BAR Method, ver `CLAUDE.md`). **Aleix Montcusi**, consultor F&B del
  equipo — su perfil es F&B en general, no sumillería específicamente, pero
  cubre ese terreno dentro de su rol.

Importante: `/consultoria-gastronomica/` **no existe en la web actual** según
esta hoja — sería una página nueva a crear. `/marketing-gastronomico/` y
`/abrir-restaurante-bar/` sí existen y coinciden exactamente con las páginas
ya trabajadas en `seo/pagina-web/paginas/` (ver estrategia/copy/maquetación ya
hechas) — **hay que verificar que esas páginas ya construidas respetan la
keyword principal, Title, H1 y meta descripción que define aquí esta hoja**,
no solo el ángulo de marca.

La pestaña "Arquitectura web [WIP]" (v1, más antigua) añade una columna
"Keywords Secundarias" con clusters de long-tail por silo — útil como lista
de variantes a cubrir dentro de cada página pilar, no como páginas nuevas.

## Pestaña "Comité de contenido" — backlog de temas de blog

44 filas con: Nº · Temática · Keywords (variantes) · Volumen mensual ·
Recomendación · Referencias (URLs de competencia/fuentes) · Documento ·
Estado.

Los primeros 4 temas de este backlog **coinciden exactamente** con artículos
que ya existen en `../blog-web/articulos/`:
1. Licencias para abrir un restaurante → ya escrito.
2. Ayudas de proveedores para montar un bar → ya escrito.
3. Ayudas de Estrella Galicia para montar un bar → ya escrito.
4. Ayudas de Mahou para montar un bar → ya escrito.

Es decir, **el listado de temas de `blog-web/listado-temas.md` no nació de la
nada: viene de este comité de contenido del gestor de SEO externo.** Falta
revisar las ~40 filas restantes del comité para ver cuántos temas más están
priorizados y sin escribir todavía — no se ha hecho en esta pasada por
volumen, es la primera tarea pendiente de `seo-estrategia-senior`.

## Pestaña "PLANTILLAS_TBNB" — ideas de lead magnet por fase del BAR Method

Herramientas/recursos descargables pensados como imán de leads, organizados
por fase (BREAKDOWN, y probablemente ARCHITECTURE/RUN en filas no muestreadas
— revisar la hoja completa). Ejemplos ya definidos:

1. **Auditoría de Hospitalidad y Experiencia** — analiza un restaurante/bar
   desde la experiencia de cliente (llegada, bienvenida, servicio, tiempos,
   producto, ambiente, atención, despedida). Disponible en ES/EN.
2. **Auditoría de Cumplimiento Normativo & APPCC** — checklist de
   cumplimiento normativo/sanitario, orientado a Barcelona.
3. **Diagnóstico de Concepto** — quiz/autodiagnóstico rápido sobre coherencia
   entre concepto, carta, posicionamiento y experiencia.
4. **APPCC Toolkit** — kit práctico para gestión de APPCC y registros.

**Confirmado por Andrea (2026-10-02): son solo idea en papel, nada construido
todavía.** El objetivo es usarlos como imán de registro a la newsletter de
TBNB — el visitante se descarga la plantilla a cambio de dejar su email, y
eso construye la base de datos de contactos. Esto conecta directamente con el
gap de atribución del briefing de Andrea: cada lead magnet puede llevar su
propio evento de conversión en GA4 (qué plantilla descargó, desde qué
página), dando datos reales de qué fase del BAR Method atrae más interés.
Tarea de `seo-analitica-conversion` (mecánica de entrega + medición) con
`seo-redaccion`/`seo-diseno-web` (contenido y forma de cada plantilla).

## Pestaña "RankTank-3" — tracking de posiciones

Configuración de la herramienta RankTank (add-on de Google Sheets para
tracking de SERP) apuntando a `https://www.thebarnbarconsulting.com/`, pero
con **Locale: United States / Language: English** — configuración
probablemente errónea para un negocio que opera en español en España.
102 keywords cargadas para escanear, 0 créditos usados todavía (el escaneo no
se ha llegado a ejecutar, o se reseteó). **Antes de retomar el tracking, hay
que corregir el locale/idioma de esta herramienta** — si no, cualquier dato
que devuelva no sirve.

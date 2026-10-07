# SEO/Web — medición mensual (datos reales pasados por Andrea)

Registro mes a mes, siguiendo los campos de `plantilla-datos-medicion.md`.
Todo lo de abajo es dato real exportado de GA4/Search Console — nada
estimado.

## Septiembre 2026 (1-30 sept)

### Snapshot de sitio completo (GA4)

- Sesiones: **571**. Usuarios activos: 421 (406 nuevos + 48 recurrentes —
  el solape entre ambas métricas es normal en GA4, no es un error de
  suma).
- Tiempo medio de interacción por usuario activo: 57s. Sesiones
  interactivas por usuario: 0,85.
- Fuente de tráfico (sesiones): **google/cpc 240** (Ads) · google/organic
  160 · directo 127 · ig/social 9 · chatgpt.com/ai-assistant 6 ·
  ads.google.com/referral 6 · facebook.com/referral 4.
- Por canal (nuevos usuarios): Paid Search 188 · Organic Search 116 ·
  Direct 76 · Organic Social 14 · Referral 5 · AI Assistant 4 ·
  Cross-network 3.
- Campañas de Google Ads activas: "TBNB - Consulting - ..." (131
  sesiones) y "TBNB - Consulting - B..." (109 sesiones) — nombres
  truncados en el export, 240 sesiones en total (coincide con
  google/cpc).
- **Leads cualificados: 0. Conversiones: 0.** "Key events by platform" y
  "Users by disqualified lead reason" aparecen como **"No data
  available"**, no como "0 real". Esto es importante: no significa
  necesariamente que no haya habido ningún lead en septiembre, sino que
  **todo indica que no hay ningún evento de conversión configurado en
  GA4** (ni para el formulario de contacto ni para la reunión de 15
  min). Sin ese evento, GA4 no tiene forma de contar un lead aunque
  ocurra. **Pregunta para Andrea/Sergio: ¿existe ya ese evento
  configurado, o es el primer hueco real a cerrar?** Si no existe, es
  más urgente que cualquier otra cosa de este informe — sin él, todos
  los meses seguirán marcando 0 leads, sea cual sea el tráfico.
- Geografía: España 332 de 421 usuarios activos. Barcelona y Madrid
  empatadas como ciudad con más usuarios (92 cada una), luego Málaga y
  Valencia (11 cada una).
- Idioma: mayoría clara en español, resto residual (inglés, chino,
  catalán, francés, italiano, ruso).
- Stickiness: DAU/MAU 6,2% · DAU/WAU 21,1% · WAU/MAU 29,2%.

### Por página (GA4) — vistas del mes

| Página | Vistas |
|---|---|
| Home / Consultoría de hostelería (título truncado en export) | 293 |
| Contacto (título truncado) | 177 |
| "Bar..." (título truncado) | 72 |
| Servicios | 70 |
| Proyectos | 67 |
| **Traspasos** | 57 |
| Equipo | 54 |

### Search Console — tendencia de sitio (4 meses, del propio export)

| Periodo | Clics | Impresiones | CTR | Posición media |
|---|---|---|---|---|
| Jul 2026 | 145 | 18.753 | 0,77% | 11,8 |
| Ago 2026 | 175 | 22.943 | 0,76% | 11,6 |
| **Sep 2026** | **181** | **24.202** | **0,75%** | **10,1** |
| Oct 1-4 (parcial) | 25 | 3.313 | 0,75% | 11 |

Lectura: tendencia positiva de fondo — posición media mejorando mes a
mes (11,8 → 10,1) y más impresiones cada mes, incluso antes de publicar
el blog nuevo o las páginas de servicio en curso.

### Search Console — keywords prioritarias del research de Saúl

Cruce contra las keywords principales de cada silo
(`investigacion-heredada/roadmap-y-keyword-research.md`):

| Keyword prioritaria | Silo | Volumen objetivo | Clics sept | Impresiones sept | Posición sept |
|---|---|---|---|---|---|
| consultoria hosteleria | Home | 960 (combinada con asesoria) | 2 | 216 | 6,33 |
| consultoria hosteleria barcelona | Home (variante) | — | 0 | 34 | 4,82 |
| asesoria hosteleria | Home / Silo Servicios | 470 | 0 | 40 | 19,15 |
| consultoria gastronomica barcelona | `/consultoria-gastronomica/` (no existe aún) | 500 | 1 | 31 | 12,1 |
| consultoria gastronomica madrid | idem | — | 0 | 20 | 22,6 |
| **marketing para restaurantes** | `/marketing-gastronomico/` | 700 | **0** | **0 — sin ninguna impresión** | — |
| **traspaso bar barcelona** | `/traspasos/` | **1.600 (la de mayor volumen de toda la hoja)** | **0** | **0 — sin ninguna impresión** | — |
| como abrir un restaurante (exacta) | `/abrir-restaurante-bar/` | 270 | 0 | 1 | 2,0 |
| manual para abrir un restaurante (variante real que sí aparece) | idem | — | 0 | 23 | 22,22 |

**El hallazgo más importante de este cruce:** las dos keywords de mayor
volumen objetivo de todo el research heredado —"traspaso bar barcelona"
(1.600/mes) y "marketing para restaurantes" (700/mes)— tienen **cero
impresiones** en septiembre. No es que estén mal posicionadas, es que
Google no les ha mostrado la web **ni una sola vez** para esas búsquedas
exactas, pese a que ambas páginas (`/traspasos/` y
`/marketing-gastronomico/`) ya existen y reciben tráfico real (Traspasos
tuvo 57 vistas en septiembre). Esto apunta a un problema de
indexación/optimización on-page de esas dos páginas para esas keywords
exactas, no a un problema de posición — hay que revisarlo con
`seo-arquitectura-web` antes de dar por bueno que "ya están las páginas,
falta posicionarlas".

## Próxima entrega

Mismo formato, mes de octubre — cadencia mensual ya acordada.

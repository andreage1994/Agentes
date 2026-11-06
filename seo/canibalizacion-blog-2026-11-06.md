# Canibalización en el blog — mapa preliminar (2026-11-06)

**Qué es esto:** una primera lista de posibles canibalizaciones. Está
hecha con:
- el sitemap de posts de la web (132 URLs, leído el 2026-11-05);
- el export de Search Console **por páginas** que ya tenemos
  (`seo/blog-web/curacion-blogs-mas-visitados-2026-10.md`,
  `seo/medicion-mensual.md`);
- los avisos que ya estaban en `seo/blog-web/curacion-estrategia.md`.

**Qué no es todavía:** una canibalización **confirmada**. Solo hay
canibalización real cuando dos URLs nuestras salen en Google para **la
misma búsqueda** y se reparten las impresiones. Eso solo se ve con datos de
Search Console de **consulta + página** juntas (ver el final del documento).
Mientras no lleguen esos datos, todo lo de abajo es **hipótesis**: la
deducimos por el slug, el título y el tema de cada URL.

Tampoco se pudo abrir cada artículo para comparar su H1 y su title, porque
la web devolvía errores 502 (ver `seo/auditoria-web-2026-11-05.md`).

Riesgo: 🔴 alto (mismo tema y misma intención) · 🟠 medio (temas que se
solapan) · 🟢 bajo (temas vecinos pero con ángulos distintos).

---

## Español

| # | Tema | URLs que compiten | Riesgo | Nota |
|---|---|---|---|---|
| 1 | **Licencias de apertura** | `/licencias-abrir-restaurante/` (4 nov 2026) · `/licencias-de-apertura-de-restaurantes/` (jun 2026) · `/licencias-para-abrir-un-restaurante/` (la que citan nuestros briefs; no aparece en el sitemap) | 🔴 | Tres URLs con la misma intención. Hay que comprobar si la de los briefs redirige o si ha desaparecido. |
| 2 | **Errores al abrir un restaurante** | `/errores-comunes-al-abrir-un-restaurante/` · `/errores-comunes-al-abrir-un-restaurante-2/` | 🔴 | Duplicado literal (el sufijo `-2` sale de WordPress). Una de las dos sobra. |
| 3 | **Monodosis** | `/fin-monodosis-restaurantes/` (may 2026, 24 clics, posición 8) · `/por-que-quitan-los-monodosis-en-los-bares/` (sep 2026) | 🔴 | El artículo nuevo compite con uno que ya funcionaba. |
| 4 | **"Facturo/estoy lleno pero no gano"** | `/como-calcular-la-rentabilidad-de-un-negocio-de-hosteleria/` (**161 clics, el nº 1 del blog**) · `/rentabilidad-restaurante-lleno-sin-beneficios/` · `/restaurante-factura-pero-no-gana/` · `/tu-restaurante-esta-lleno-pero-no-ganas-dinero/` · `/punto-de-equilibrio-en-restauracion-cuanto-necesitas-vender/` (36 clics) · `/consultoria-hosteleria-rentable/` | 🔴 | Ya estaba señalado en curación como "contenido fragmentado". Es el grupo más grave porque roza la página que más tráfico trae. |
| 5 | **Diseño de carta** | `/como-disenar-carta-restaurante/` (4 nov 2026) · `/como-crear-una-carta-de-menu/` (dic 2025) · `/platos-vampiro-rentabilidad-restaurante/` | 🔴 / 🟢 | Las dos primeras tienen la misma intención. Platos vampiro es un ángulo distinto (ingeniería de menú). |
| 6 | **Vender, comprar o traspasar** | `/lo-que-debes-saber-antes-de-vender-un-restaurante/` (26 clics) · `/como-vender-o-comprar-tu-negocio-con-exito/` · `/comprar-restaurante-traspaso/` · la página `/traspasos/` · `/comprar-un-restaurante/` | 🔴 | Ya señalado en `medicion-mensual.md`. Es la keyword de más volumen del research ("traspaso bar barcelona", 1.600/mes) y no tiene una URL clara que la lidere. |
| 7 | **Reducir costes** | `/como-reducir-los-gastos-de-un-bar/` (18 clics, actualizado el 4 nov) · `/gastos-hormiga-bar/` | 🟠 | Puede convivir si "gastos hormiga" se queda como la lupa sobre costes pequeños y enlaza a la guía general. |
| 8 | **Food cost, escandallo e inventario** | `/food-cost-restaurantes/` · `/escandallo-evitar-desperdicio-restaurante/` · `/control-de-inventario-restaurantes/` · `/negociar-proveedores-restaurante/` | 🟠 | Son temas vecinos. El riesgo está entre food cost y escandallo. Hay que confirmar que `/food-cost-2026-por-que-el-calculo-ya-no-vale/` (la URL de los briefs) redirige a `/food-cost-restaurantes/`. |
| 9 | **Problemas del día a día** | `/problemas-diarios-de-un-restaurante/` · `/la-solucion-a-los-problemas-del-dia-a-dia-en-restaurantes-mal-gestionados-con-the-bar-n-bar/` (2024) · `/los-errores-que-matan-el-servicio-de-tu-restaurante/` | 🟠 | Los dos primeros tienen la misma intención. El de 2024 es candidato a redirigir. |
| 10 | **Café de especialidad** | `/como-vender-cafe-de-especialidad/` (19 clics) · `/la-transicion-al-cafe-de-especialidad-con-the-bar-n-bar/` (2024) · `/cafe-con-tonica/` | 🟠 / 🟢 | La transición de 2024 se solapa con la de cómo venderlo. Café con tónica es otro tema. |
| 11 | **Concepto de hostelería** | `/como-crear-un-concepto-de-hosteleria/` · `/descubre-el-arte-de-analizar-un-concepto-de-hosteleria-…/` (2024) | 🟠 | El patrón es el mismo que en los grupos 9 y 10: un post de 2024 "con The Bar N' Bar" frente a otro nuevo. |
| 12 | **Abrir un bar o elegir modelo** | `/guia-completa-para-abrir-un-bar/` (82 clics, 16.475 impresiones, posición 13) · `/los-5-tipos-de-negocios-…-2024/` (151 clics) · grupo 2 | 🟢 | Ya se decidió en curación que tienen intenciones distintas (qué modelo elegir frente a cómo ejecutar). Hay que vigilar que el grupo 2 no le quite fuerza a la guía. |
| 13 | **Ayudas y cerveceras** | `/ayudas-montar-bar/` · `/mahou-te-monta-el-bar/` · `/estrella-galicia/` | 🟢 | Se diseñaron como piezas distintas. Hay que confirmar que las URLs antiguas `/ayudas-para-montar-un-bar/` y `/estrella-galicia-te-monta-el-bar/` redirigen a las nuevas. |
| 14 | **Personal** | `/errores-plantilla-personal-restaurante/` · `/como-reducir-la-rotacion-de-personal-en-tu-bar/` · `/subida-sueldos-hosteleria-beneficio/` | 🟢 | Ángulos distintos. |
| 15 | **"Consultoría de hostelería"** (fuera del blog, pero dentro del sitemap de posts) | Home · `/consultoria-hosteleria-en-barcelona/` · `/consultoria-hosteleria-en-madrid/` · `/por-que-contratar-la-consultoria-de-hosteleria/` | 🔴 **confirmada** | Es la única que ya está medida con datos reales: la Home está en la posición 28,7 y Barcelona en la 3,6 para "consultoria hosteleria" (ver `medicion-mensual.md` y `curacion-14-recomendacion-fusion.md`). |

## Inglés

| # | Tema | URLs que compiten | Riesgo |
|---|---|---|---|
| 16 | Problemas del día a día | `/en/restaurants-daily-problems/` · `/en/fix-your-restaurants-daily-problems/` · `/en/the-solution-to-everyday-problems-in-poorly-managed-restaurants-…/` | 🔴 tres URLs |
| 17 | Café de especialidad | `/en/how-to-sell-specialty-coffee/` · `/en/transitioning-to-specialty-coffee-with-the-bar-n-bar/` · `-2/` · `-3/` | 🔴 cuatro URLs, tres de ellas con el mismo slug |
| 18 | Espresso tonic | `/en/espresso-tonic/` · `/en/espresso-tonic-the-gold-mine-for-your-bar/` | 🔴 |
| 19 | Monodosis | `/en/end-single-dose-restaurants/` · `/en/why-single-dose-portions-are-vanishing-from-bars/` | 🔴 (el mismo caso que el grupo 3 en español) |
| 20 | Desperdicio y escandallo | `/en/avoid-restaurant-food-waste/` · `/en/recipe-costing-avoid-restaurant-waste/` | 🔴 |
| 21 | Rentabilidad | `/en/restaurant-profitability-full-but-not-profitable/` · `/en/restaurant-management-audit-true-profitability/` | 🟠 |
| 22 | Fichas de proyecto | `/en/religion-coffee/` + `-2/` … `-10/`, `/en/geisha-coffee-shop/` + `-2/`, `/en/gabbys-bakery/` + `-2/`, `/en/brunch-and-the-city/` + `-2/` | 🔴 duplicados técnicos, no editoriales |

**Un hallazgo que no es canibalización, pero es urgente:**
`/en/the-5-most-profitable-hospitality-businesses-in-2024/` tenía la **mejor
posición media de todo el blog (4,01)** según Search Console, y **no aparece
en el sitemap de posts**. Puede que esté en otro sitemap, que se haya
despublicado o que se le haya cambiado el slug. Hay que mirarlo antes de
perder ese tráfico.

## Patrón de fondo

Casi todos los casos 🔴 vienen de una de estas tres cosas:
1. **Reescribir creando una URL nueva** en vez de actualizar la que ya
   existía: grupos 1, 3, 5, 8 y 13. Las nuevas son del 4 de noviembre o de
   septiembre y conviven con las antiguas.
2. **Duplicados de WordPress con sufijo `-2`, `-3`…**: grupos 2, 17 y 22.
3. **Posts de 2024 "con The Bar N' Bar"** que se volvieron a escribir en
   2025–2026 sin redirigir los antiguos: grupos 9, 10, 11 y 16.

Regla propuesta para el equipo: **al curar o reescribir un artículo, se
mantiene la URL antigua si ya tiene tráfico**. Si hay que cambiarla, se
pone una redirección 301 el mismo día.

---

## Qué hace falta para confirmar el análisis

### 1. Imprescindible: Search Console con consulta + página juntas

El export de "Páginas" que pasasteis el 28 de octubre no basta: dice cuánto
tráfico tiene cada URL, pero no **por qué búsquedas**. Se puede sacar de
dos maneras (la opción A es la buena):

**Opción A: un solo archivo con todo.** Instalad el complemento gratuito
**"Search Analytics for Sheets"** en Google Sheets (lo hacéis vosotros desde
vuestra cuenta, sin conectar nada a este sistema). Configuración:
- Propiedad: thebarnbarconsulting.com
- Fechas: **últimos 12 meses** (o 16, el máximo)
- Agrupar por (*Group by*): **Query** + **Page**
- Sin filtros. Filas: todas.

Descargadlo como CSV y subidlo aquí. Con eso lo cruzo todo y cada grupo de
arriba queda confirmado o descartado.

**Opción B: sin instalar nada, consulta a consulta.** En Search Console:
Rendimiento → filtro **Consulta** → "Consulta exacta" → pestaña **Páginas**
→ Exportar. Es lo mismo que ya hicisteis con "consultoria hosteleria".
Habría que repetirlo con estas búsquedas:

1. licencia apertura restaurante
2. errores al abrir un restaurante
3. monodosis bares
4. rentabilidad restaurante
5. restaurante lleno sin beneficios
6. punto de equilibrio restaurante
7. carta restaurante
8. vender restaurante
9. traspaso bar barcelona
10. reducir gastos bar
11. food cost restaurante
12. escandallo
13. café de especialidad
14. problemas restaurante
15. espresso tonic

### 2. Muy útil: lista de redirecciones

Desde WordPress: Rank Math → **Redirecciones** → exportar. Así sé qué URLs
antiguas ya redirigen y no hay que tocarlas. No pude comprobarlo yo porque
la web devolvía 502.

### 3. Una decisión vuestra, no técnica

Qué URL debe liderar **Traspasos** (grupo 6). Es una línea de negocio, no
solo una keyword, y no lo debe decidir el SEO.

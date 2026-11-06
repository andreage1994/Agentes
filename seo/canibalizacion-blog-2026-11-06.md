# Canibalización en el blog y la web: análisis con datos de Search Console

**Fecha:** 2026-11-06
**Fuente:** export de Search Console con **consulta + página**, sacado por
Andrea el 2026-11-06 con *Search Analytics for Sheets*. Son 5.325 filas,
3.781 búsquedas, 165 URLs, 222 clics y 138.995 impresiones.

El archivo en bruto **no se guarda en el repo**. Aquí solo va el análisis.

**Criterio de canibalización:** una búsqueda con ≥ 30 impresiones en la que
**dos o más URLs nuestras** se llevan cada una ≥ 15 % de las impresiones (y
al menos 10 impresiones).

Con ese criterio salen **175 búsquedas canibalizadas, que suman 66.466
impresiones: el 48 % de todas las del sitio**.

> ⚠️ **Hay que confirmar el rango de fechas del export.** El total de clics
> (222) es muy bajo comparado con el export de Páginas del 28 de octubre
> (161 clics solo para el artículo de rentabilidad en 6 meses; en este, 9).
> Parte de la diferencia se explica porque Google oculta las búsquedas poco
> frecuentes cuando se agrupa por consulta. Aun así, para leer bien los clics
> hace falta saber qué fechas se eligieron. Las **comparaciones entre URLs**
> de este documento no dependen de eso y son válidas.

Las ✅/❌ marcan si se confirma o se descarta lo que planteaba el mapa
preliminar del mismo día (hecho solo con el sitemap).

---

## 1. Confirmadas, ordenadas por impacto

### 🔴 A. "Consultoría de hostelería": la Home y las páginas locales (≈ 49.000 impresiones)

Es, con mucha diferencia, la canibalización más grande del sitio. Compiten la
Home, `/consultoria-hosteleria-en-barcelona/`,
`/consultoria-hosteleria-en-madrid/`,
`/por-que-contratar-la-consultoria-de-hosteleria/` y
`/consultoria-hosteleria-rentable/` en más de 80 búsquedas.

| Búsqueda | Impr. | Quién sale y en qué posición |
|---|---|---|
| consultoria hosteleria | 3.856 | **Madrid 6,6** · Home 33,4 · Barcelona 29,3 · Por qué contratar 36,4 |
| consultoria gastronomica barcelona | 1.737 | **Barcelona 13,5** · Home 31,4 |
| consultoria hosteleria barcelona | 1.279 | Home 12,7 · Barcelona 11,1, prácticamente empatadas |
| consultor hosteleria | 804 | **Madrid 4,5** · Home 47,6 · Barcelona 46,4 |
| consultoría hostelería madrid | 668 | **Madrid 8,4** · Home 12,6 |

Lectura:
- Las páginas locales ganan siempre a la Home. La Home solo aporta clics
  por la marca ("the bar n bar", "barnbar").
- **Corrección a lo documentado:** para "consultoria hosteleria" (sin
  ciudad), en este export la que mejor posiciona es **Madrid (6,6)**, no
  Barcelona. En `medicion-mensual.md` y `curacion-14-recomendacion-fusion.md`
  figuraba Barcelona en la posición 3,56, pero con otro periodo. Antes de
  decidir el destino de la fusión del #14 hay que revisarlo con el mismo
  rango de fechas.
- `/por-que-contratar-la-consultoria-de-hosteleria/` aparece en casi todas
  estas búsquedas, siempre por debajo de la posición 30, y solo tiene 1 clic.
  Confirma la recomendación de fusionarla.

**Decisión para `seo-estrategia-senior` y `seo-arquitectura-web`:** asignar
cada búsqueda a una URL. La Home para la marca y la búsqueda genérica,
Barcelona y Madrid para las búsquedas con ciudad. Después, ajustar los
titles y H1 de la Home para que no persiga "consultoría hostelería +
ciudad".

### 🔴 B. Duplicados técnicos en inglés (antes no estaban detectados)

- **"The 5 most profitable hospitality businesses in 2024": 16 URLs.** Además
  de la original existen las versiones `-2` a `-16`.
  **Corrección:** el artículo no había desaparecido. La URL original sigue
  recibiendo impresiones (590). El problema es que tiene 15 copias.
  - Cuidado: en "hospitality business ideas" la copia **`-9` está en la
    posición 1,2** y la original en la 4,5. Hay que redirigir **todas las
    copias a una sola URL**, sin borrarlas sin más.
- **"Transitioning to specialty coffee": 5 URLs** (original y `-2` a `-4`).
  La que de verdad tiene visibilidad es la **`-3`, con 5.821 impresiones**,
  la 6.ª URL del sitio. En curación se estaba trabajando la `-2` (242
  impresiones). Hay que replantear sobre cuál se trabaja.
- Hay variantes con erratas que reciben impresiones:
  `/los-5-tipos-de-negocios-de-hosteleria-mais-rentables-en-2024/`
  ("mais") y `/los-5-tipos-de-negocios-de-hosteleria-mas-rentables/`.

### 🔴 C. Fichas de proyecto en ES y EN compitiendo por la misma búsqueda de marca

| Búsqueda | ES | EN |
|---|---|---|
| geisha coffee madrid (1.556) | 777 impr, pos. 9,5 | 779 impr, pos. 9,4 |
| religion coffee (427) | pos. 12,2 | **pos. 9,1, gana la inglesa** |
| brunch and the city (820) | `/brunch-and-the-city/` | `/en/brunch-and-the-city-2/` |
| eat my trip, caravan lavapies | ES | EN |

No se arregla fusionando páginas, sino con **`hreflang`**, que hoy no existe
en la web (ver `auditoria-web-2026-11-05.md`). Con hreflang, Google enseña la
ES en España y la EN fuera, en vez de repartir la posición entre las dos.

### 🟠 D. Rentabilidad ✅ confirmada, pero acotada

| Búsqueda | Impr. | Resultado |
|---|---|---|
| rentabilidad en hostelería | 177 | **Calcular rentabilidad 3,5** · 5 tipos de negocio 43,9 |
| es rentable un bar | 74 | 5 tipos **8,6** · Calcular rentabilidad 17,3 |
| cuanto factura un bar al mes | 195 | **Calcular rentabilidad 13,3** · Punto de equilibrio 31,6 |

- Entre el artículo de rentabilidad y el de 5 tipos de negocio hay unas
  1.400 impresiones compartidas. Entre rentabilidad y punto de equilibrio,
  unas 1.100.
- El trío de "lleno pero no gano" casi no tiene datos:
  `/rentabilidad-restaurante-lleno-sin-beneficios/` 145 impresiones,
  `/tu-restaurante-esta-lleno-pero-no-ganas-dinero/` 74 y
  `/restaurante-factura-pero-no-gana/` ninguna. **No le está quitando tráfico
  al artículo de rentabilidad. Es contenido flojo, no canibalización grave.**
  Fusionarlo hacia el de rentabilidad sigue teniendo sentido, pero por
  limpieza, no por urgencia.
- La frontera entre "rentabilidad" y "5 tipos de negocio" que se definió en
  curación es correcta. Al reescribir hay que respetarla.

### 🟠 E. Vender un restaurante ✅

En "mejor momento vender restaurante" (1.963 impresiones),
`/lo-que-debes-saber-antes-de-vender-un-restaurante/` está en la posición
**6,1** y `/como-vender-o-comprar-tu-negocio-con-exito/` en la 24,7.
**La que lidera es "lo que debes saber"**: hay que fusionar la otra hacia
ella.

### 🟠 F. Errores al abrir un restaurante ✅

En "errores al abrir un restaurante", el original está en la posición
**9,1** y el `-2` en la 14,7. Hay que redirigir el `-2` al original.

### 🟢 G. Gestionar un bar (nueva, no estaba prevista)

En "como gestionar un bar" y otras parecidas (467 impresiones),
`/guia-completa-para-abrir-un-bar/` (39,8) y `/como-hacer-crecer-tu-bar/`
(46,8) se reparten las impresiones, las dos muy abajo. Es una oportunidad
más que un problema: ninguna de las dos responde bien a esa búsqueda.

### 🟢 H. Monodosis ✅, pero pequeña

En "adios a las monodosis" las dos URLs se reparten las impresiones (5,8 y
9,2), con unas 200 impresiones en total. Merece la pena fusionarlas, pero
el volumen es bajo.

## 2. Descartadas o sin datos todavía

| Grupo del mapa preliminar | Resultado |
|---|---|
| Licencias | ❌ Sin datos. Solo `/licencias-de-apertura-de-restaurantes/` recibe impresiones (1.197). `/licencias-abrir-restaurante/` no aparece: es demasiado reciente. **Riesgo futuro alto:** hay que decidir cuál se queda antes de que empiecen a competir. |
| Carta, ayudas, Mahou, Estrella Galicia, APPCC, food cost | Sin datos (publicadas o actualizadas el 4 de noviembre). Se vuelven a medir en diciembre. |
| Reducir gastos frente a gastos hormiga | ❌ Descartada. Gastos hormiga tiene 2 impresiones. |
| Escandallo, inventario y food cost | ❌ Sin búsquedas compartidas. |
| Concepto de hostelería | ❌ No compiten, pero hay un dato importante: **la de 2024** (`/descubre-el-arte-de-analizar-un-concepto…/`) **tiene 1.259 impresiones, y la nueva solo 137.** Si se fusionan, **la que se queda es la antigua**. |
| Problemas del día a día, café de especialidad en ES, espresso tonic, single-dose en EN, desperdicio en EN | ❌ Volumen insignificante o sin búsquedas compartidas. |
| Traspasos | ❌ No hay canibalización entre artículos, pero **`/traspasos/` tiene 1.654 impresiones y 0 clics**. El problema es de CTR o de intención, no de canibalización. |

### Un aviso que sale de los datos

La búsqueda "ayudas de estrella galicia para montar un bar" (1.224
impresiones, 16 clics, **la búsqueda no de marca que más clics trae**) la
gana hoy `/guia-completa-para-abrir-un-bar/`. El artículo nuevo
`/estrella-galicia/` va a por esa misma búsqueda. **Hay que enlazar desde la
guía al artículo nuevo** y dejar que lo absorba de forma natural. No hay que
quitarlo de la guía hasta ver que el nuevo posiciona.

## 3. Regla para el equipo

1. Al curar o reescribir un artículo, **se mantiene la URL que ya tiene
   impresiones**, aunque sea la antigua (ver el caso del concepto).
2. Antes de redirigir, **se mira qué copia posiciona mejor**. A veces no es
   la original (ver la `-9` del 5 most profitable o la `-3` de specialty
   coffee).
3. Todas las URLs `-2`, `-3`… se redirigen con un 301 a una sola URL.

## 4. Siguientes pasos

1. Andrea: confirmar el **rango de fechas** del export.
2. `seo-arquitectura-web`: lista de redirecciones para B, E, F y H, y
   `hreflang` para C.
3. `seo-estrategia-senior`: decidir qué URL va con cada búsqueda en A.
4. Repetir este análisis en **diciembre de 2026**, cuando los artículos del
   4 de noviembre ya tengan datos.

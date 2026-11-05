# Auditoría de la web en vivo — thebarnbarconsulting.com

**Fecha:** 2026-11-05 · **Método:** rastreo directo (navegador sin interfaz +
lectura de sitemaps de Rank Math), sin conectar ninguna cuenta (ni GA ni
Search Console). Solo lectura: no se ha tocado nada de la web.

**Alcance real:** el servidor respondió 502/503 a la mayoría de peticiones,
así que solo se pudieron analizar a fondo 7 páginas: `/en/`, `/bar-method/`,
`/the-bar-method/`, `/servicios/`, `/proyectos/`, `/contacto/` y `/blog/`,
más el sitemap completo de posts (132 URLs). La home en español, `/equipo/`,
`/traspasos/`, las páginas locales y los artículos sueltos **no cargaron
nunca** en esta sesión.

---

## 1. Lo más urgente: la web casi no responde

- Las páginas que sí cargaron tardaron **9–18 segundos** cada una.
- La mayoría devolvió **502 Bad Gateway** tras ~8 s de espera (siempre el
  mismo tiempo, lo que apunta a un *timeout* del servidor de origen), incluida
  la **home en español** en 4 intentos separados por varios minutos.
- `/consultoria-gastronomica/` tardó 38 s en devolver un 404.

**Ojo con la interpretación:** parte de los cortes pueden venir de la red de
esta sesión (que sale por un proxy), así que no está demostrado que un
cliente real vea lo mismo. Pero que incluso las páginas que funcionan tarden
más de 9 segundos sí es un problema real, porque Google penaliza esa
velocidad y la mayoría de la gente se va antes de que cargue.

**Acción (Sergio, IT):** abrir la home desde un móvil con 4G y pasar
PageSpeed Insights hoy mismo. Si se confirma, hablar con el hosting y con
Eleyuve (quien hizo la web): caché de página, plan del hosting y peso de
Elementor y los plugins.

## 2. Dos BAR Method distintos publicados a la vez

| URL | Qué dice | Estado |
|---|---|---|
| `/bar-method/` (enlazada en el menú) | **Breakdown → Architecture → Run** ✅ (el método actual) | Indexable |
| `/the-bar-method/` | **Branding → Audit → Remodel** ❌ (versión antigua) | Indexable, con su propia canónica, 2 H1 |

- Las dos páginas compiten por la misma búsqueda (canibalización) y, sobre
  todo, **le cuentan al cliente dos métodos distintos**.
- `/the-bar-method/` ofrece una "reunión gratuita de **30 minutos**"; el resto
  de la web dice **15 minutos**.
- La versión en inglés es `/en/the-bar-method/`, así que no sabemos qué versión
  del método cuenta.

**Acción:** redirección 301 de `/the-bar-method/` → `/bar-method/` (y revisar
`/en/the-bar-method/`). Antes de redirigir, rescatar lo que la página antigua
tenga de valor para el SEO (sus H2 "Consultoría hostelera en Barcelona y
Madrid", por ejemplo).

## 3. Contenido duplicado y canibalización (sitemap de posts)

- **9 copias de Religion Coffee en inglés**: `/en/religion-coffee-2/` hasta
  `/en/religion-coffee-10/`, todas creadas el 22–23 de junio de 2026, además
  de `/en/religion-coffee/`. Seguramente son borradores duplicados al traducir.
  Hay que borrarlas o redirigirlas.
- Más duplicados con sufijo: `errores-comunes-al-abrir-un-restaurante` y
  `-2`, `geisha-coffee-shop` y `-2` (también en EN), `brunch-and-the-city` y
  `-2`, `gabbys-bakery` y `-2`, `reginas-brunch-2`, tres
  `transitioning-to-specialty-coffee…`.
- **Tres artículos sobre licencias**: `licencias-abrir-restaurante` (nuevo,
  4 nov), `licencias-de-apertura-de-restaurantes` (junio) y
  `licencias-para-abrir-un-restaurante` (la que citan nuestros briefs). Hay que
  quedarse con uno y redirigir los otros.
- Lo mismo con **ayudas** (`ayudas-montar-bar` frente a
  `ayudas-para-montar-un-bar`, la que citan los briefs), **Estrella Galicia**
  (`estrella-galicia` frente a `estrella-galicia-te-monta-el-bar`) y
  **food cost** (`food-cost-restaurantes` frente a
  `food-cost-2026-por-que-el-calculo-ya-no-vale`). Hay que confirmar si las URL
  antiguas redirigen a las nuevas (no se pudo comprobar por los 502).
- `los-5-tipos-de-negocios-de-hosteleria-mas-rentables-en-2024`: el slug dice
  "2024" y el contenido se actualizó en 2026.
- Las fichas de **proyectos** (Rasa, Lady Madrid, Gambit…) y los **anuncios de
  traspaso de 2024** (`obrador-y-sala-en-el-centro-de-madrid`, `esquina-unica…`)
  están publicados como *posts* del blog. Hay que revisar si los locales siguen
  disponibles y quitar del índice los que ya no lo estén.

## 4. SEO on-page de las páginas principales

| Página | Problemas |
|---|---|
| `/servicios/` | **Sin H1.** Meta genérica. Esquema `Article`/`Person` en una página de servicio. |
| `/proyectos/` | **Sin H1 ni H2**, solo 174 palabras. La meta dice "con **mis** clientes" (en singular; parece heredada). |
| `/contacto/` | **Sin H1 y sin meta description.** El enlace `mailto:info%20@%20thebarnbarconsulting.com` tiene espacios y **no funciona**. `tel:+688927438` no lleva el prefijo 34, así que **no funciona desde fuera de España** y falla en algunos móviles. |
| `/blog/` | 2 H1 ("Entrebares" y "¿Buscas un traspaso?") y ningún H2. |
| `/the-bar-method/` | 2 H1 (uno es "Entrebares", que parece salir de una plantilla). |
| `/en/` | El H1 aparece duplicado. **20 de 29 imágenes sin alt.** El botón "DISCOVER OUR PROJECTS" lleva a `/proyectos/` en **español**. |
| Todas | **Ningún `hreflang`** entre ES y EN, aunque toda la web está en dos idiomas. Google no sabe qué versión enseñar en cada país. |

Otros detalles que se repiten en todas las páginas:
- Hay enlaces internos con `http://` (sin s): pie legal, botones de proyectos
  y contacto en EN. Cada uno pasa por una redirección.
- El texto prellenado de WhatsApp acaba en "Thanks **�**" (un carácter
  roto).
- La nube de etiquetas tiene erratas indexables: `/tag/rentabiliad/`,
  `/tag/hosteleria-2/`. Hay unas 30 etiquetas con 1–2 posts cada una
  (*thin content*). Recomendación: poner las etiquetas en `noindex`.
- El pie dice "Copyright THE BAR AND BAR © **2024**", y los perfiles salen
  como "@THEBARANDBAR" aunque el enlace es `@thebarnbar_`.
- En `/bar-method/` aparece "**Lady Madrid · Barcelona**" con "+100.000 € de
  facturación en 6 meses". Hay que confirmar la ciudad y que la cifra está
  verificada y aprobada para publicarse.
- En la home EN, la sección de citas (`/en/citas-manifiestos/…`) mezcla
  slugs en español dentro de `/en/`.

## 5. URLs que usan nuestros briefs y su estado real

Esto responde en parte al pendiente de `seo/pagina-web/estado.md` sobre
verificar las URLs internas antes de montar en Elementor:

| URL de los briefs | Resultado |
|---|---|
| `/consultoria-gastronomica/` | ❌ **404**: no existe |
| `/sobre-nosotros/` | ❌ 404 (la página real es `/equipo/`) |
| `/bar-method/` | ✅ existe (es la buena; ver punto 2) |
| `/consultoria-hosteleria-barcelona/` y `/-madrid/` | ⚠️ En el sitemap existen como `/consultoria-hosteleria-**en**-barcelona/` y `/-en-madrid/` (y son *posts*, no páginas). Los briefs usan la URL sin "en". No se pudo comprobar si redirigen. |
| `/servicios/consultoria-rrhh-hosteleria/`, `/servicios/consultoria-tecnologica-hosteleria/`, `/marketing-gastronomico(-restaurantes)/`, `/abrir-restaurante-bar/` | ⚠️ 502, sin verificar. No están en el sitemap de posts; el sitemap de páginas no se pudo descargar. |

## 6. Lo que está bien

- Rank Math está bien configurado: sitemaps divididos, canónicas
  correctas, `index, follow`, previsualización de imagen grande.
- El `robots.txt` es correcto y no bloquea nada importante.
- La nueva `/bar-method/` cuenta bien el método, con el tono de la casa
  ("peeeeero…", "cada uno va a su bola") y casos de éxito arriba.
- Se ha publicado mucho blog nuevo en noviembre (8 posts el 4 de noviembre).

---

## Prioridades sugeridas

1. **Velocidad y caídas del servidor**: confirmar desde fuera y hablar con
   el hosting (Sergio).
2. Redirigir `/the-bar-method/` → `/bar-method/` y unificar "15 minutos".
3. Arreglar el email y el teléfono rotos de `/contacto/`, que cuestan leads
   directamente.
4. Limpiar duplicados: 9× Religion Coffee EN, tres posts de licencias y los
   demás `-2`.
5. Poner `hreflang` ES↔EN y un H1 en servicios, proyectos y contacto.
6. Repetir esta auditoría cuando el servidor responda, para cubrir la home ES,
   `/equipo/`, `/traspasos/`, las páginas locales y una muestra de artículos.

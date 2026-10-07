# Diagnóstico: por qué /traspasos/ y /marketing-gastronomico/ tienen 0 impresiones

**Aviso primero:** intenté comprobarlo yo directamente (robots.txt,
código fuente de las páginas) y no puedo — el proxy de salida de esta
sesión bloquea el acceso a `thebarnbarconsulting.com` (mismo bloqueo que
ya habían encontrado los agentes de investigación del blog). Así que esto
es un paso a paso para que lo ejecutéis vosotros o quien gestione la web.

## 1. Inspección de URL en Search Console (el más fiable, empezar aquí)

**Cómo llegar:**
1. Entra en [search.google.com/search-console](https://search.google.com/search-console)
2. Arriba a la izquierda hay un selector de propiedad (el nombre/dominio
   actual con una flechita) — confirma que está seleccionada la
   propiedad de `thebarnbarconsulting.com` (puede haber dos tipos de
   propiedad, dominio y prefijo de URL; si hay varias, prueba con la que
   use `https://www.thebarnbarconsulting.com`).
3. **Arriba del todo de la pantalla**, no en el menú lateral, hay una
   barra de búsqueda larga (suele decir algo como "Inspeccionar
   cualquier URL en este dominio"). Haz clic ahí.
4. Pega la URL completa: `https://www.thebarnbarconsulting.com/traspasos/`
   y pulsa Enter.
5. Espera unos segundos — Search Console consulta su base de datos.

**Qué mirar en el resultado:**
- Arriba de todo: un aviso grande que dice **"La URL está en Google"**
  (con icono verde) o **"La URL no está en Google"** (icono distinto).
  Esto solo ya responde a media pregunta.
- Si no está indexada, debajo hay un motivo concreto — algo como
  "Descubierta: actualmente sin indexar", "Rastreada: actualmente sin
  indexar", "Bloqueada por robots.txt", "Error de servidor (5xx)" o
  "Problema de redirección". Anótalo tal cual sale, cada uno significa
  algo distinto.
- Haz clic en **"Ver URL rastreada"** o despliega el detalle (suele
  haber una flecha o un botón "Más información") — ahí aparece la
  sección de **canonical**: "Canonical declarado por el usuario" y
  "Canonical seleccionado por Google". Si las dos URLs no coinciden
  (por ejemplo, Google eligió el Home en vez de `/traspasos/`), ese es
  un hallazgo importante — significa que Google trata esta página como
  "duplicada" de otra.
- Si la página está bien pero nunca se ha rastreado, hay un botón
  **"Solicitar indexación"** en la parte superior derecha del resultado
  — haz clic y espera (puede tardar desde minutos a días en reflejarse).
- **Repite exactamente los mismos pasos 3-5 con la segunda URL**:
  `https://www.thebarnbarconsulting.com/marketing-gastronomico/`.

## 2. Comprobación rápida manual: `site:`

No hace falta ninguna herramienta especial. Abre Google normal (google.com)
y escribe, tal cual, en la barra de búsqueda:

```
site:thebarnbarconsulting.com/traspasos/
```

Pulsa Enter. Si no sale ningún resultado, confirma que no está indexada
(con independencia de lo que diga Search Console — es un segundo chequeo
rápido). Repite con `site:thebarnbarconsulting.com/marketing-gastronomico/`.

## 3. Ver el código fuente de cada página

1. Abre la página real en el navegador:
   `thebarnbarconsulting.com/traspasos/`
2. Clic derecho en cualquier zona vacía de la página (no sobre una
   imagen ni un enlace) → en el menú que aparece, elige **"Ver código
   fuente de la página"** (en Chrome en inglés a veces dice "View Page
   Source"). También funciona el atajo `Ctrl+U` (o `Cmd+U` en Mac).
3. Se abre una pestaña nueva llena de código HTML. Ahí dentro, pulsa
   `Ctrl+F` (buscador del navegador) y escribe **`robots`**.
   - Si encuentras una línea tipo
     `<meta name="robots" content="noindex">` — ahí está la causa: la
     propia página le dice a Google que no la indexe.
4. Busca también **`canonical`** con el mismo buscador — mira la URL
   que aparece dentro de `<link rel="canonical" href="...">`. Tiene que
   ser la propia URL de la página (`/traspasos/`), no otra distinta.
5. Repite los pasos 1-4 con `/marketing-gastronomico/`.

## 4. robots.txt del sitio

Escribe directamente en la barra de direcciones del navegador (no en el
buscador de Google):

```
thebarnbarconsulting.com/robots.txt
```

Se abre un archivo de texto simple. Busca (`Ctrl+F`) líneas que empiecen
por `Disallow:` y comprueba si alguna incluye `/traspasos/` o
`/marketing-gastronomico/` — si está ahí, Google tiene prohibido
rastrear esa carpeta entera.

## 5. Sitemap

Igual que el paso anterior, en la barra de direcciones:

```
thebarnbarconsulting.com/sitemap.xml
```

Si no carga nada o da error, prueba `thebarnbarconsulting.com/sitemap_index.xml`
(algunos sitios reparten el sitemap en varios ficheros). Una vez abierto,
busca (`Ctrl+F`) "traspasos" y "marketing-gastronomico" — confirma que
ambas URLs aparecen listadas ahí.

## 6. Enlazado interno

1. Dentro de Search Console, en el **menú lateral izquierdo**, busca la
   sección **"Enlaces"** (a veces aparece como "Links").
2. Dentro, hay dos bloques: "Enlaces externos" y **"Enlaces internos"**
   — entra en el segundo.
3. Sale una tabla de páginas con el número de enlaces internos que
   recibe cada una. Busca `/traspasos/` y `/marketing-gastronomico/` en
   esa lista (puede haber un buscador arriba de la tabla).
4. Si el número es muy bajo o no aparecen en absoluto, son "páginas
   huérfanas" — nada del propio sitio apunta a ellas, lo que las hace
   más difíciles de encontrar para Google incluso sin ningún bloqueo
   técnico.

## 7. Si todo lo anterior sale limpio: contenido on-page

Si llegas aquí sin encontrar nada (indexada, sin noindex, canonical
correcto, con enlaces internos), el problema ya no es técnico — es que
el contenido real de la página no usa la keyword objetivo de la forma
en que la define el research heredado. Para esto no hace falta que
entres en ningún sitio nuevo: simplemente dime qué Title (lo que sale en
la pestaña del navegador) y qué H1 (el titular grande visible) tiene
cada página ahora mismo, y yo lo comparo directamente contra lo que
recomienda `investigacion-heredada/roadmap-y-keyword-research.md` para
esas dos URLs — ya tengo ese documento.

## Resumen del orden de diagnóstico

1 y 2 dicen si está indexada. 3 y 4 dicen si algo lo está bloqueando
explícitamente. 5 y 6 dicen si Google tiene forma de encontrarla. 7 solo
hace falta mirarlo si los 6 anteriores salen limpios — y para ese, solo
necesitas decirme lo que ves, lo reviso yo.

# Diagnóstico: por qué /traspasos/ y /marketing-gastronomico/ tienen 0 impresiones

**Aviso primero:** intenté comprobarlo yo directamente (robots.txt,
código fuente de las páginas) y no puedo — el proxy de salida de esta
sesión bloquea el acceso a `thebarnbarconsulting.com` (mismo bloqueo que
ya habían encontrado los agentes de investigación del blog). Así que esto
es un checklist para que lo ejecutéis vosotros o quien gestione la web —
no son pasos teóricos, son los sitios exactos donde mirar, en el orden en
que conviene descartarlos.

## 1. Inspección de URL en Search Console (el más fiable, empezar aquí)

En Search Console, arriba del todo hay una barra de "Inspeccionar
cualquier URL". Pega la URL completa (`https://www.thebarnbarconsulting.com/traspasos/`,
luego repetir con `/marketing-gastronomico/`) y mira:

- **"URL está en Google"** vs. **"URL no está en Google"** — esto solo ya
  responde a la mitad de la pregunta.
- Si no está indexada, Search Console da el motivo exacto: "Descubierta,
  actualmente sin indexar", "Rastreada, actualmente sin indexar",
  "Bloqueada por robots.txt", "Problema de redirección", etc. — cada uno
  apunta a una causa distinta, no hace falta adivinar.
- Abajo, compara **"canonical declarado por el usuario"** contra
  **"canonical seleccionado por Google"** — si Google ha elegido una URL
  distinta como canónica (por ejemplo, el Home), significa que Google
  considera que esta página es "igual" a otra y no la indexa por
  separado. Esto sería un hallazgo importante si pasa.
- Si todo está bien pero nunca se ha rastreado, hay un botón
  **"Solicitar indexación"** justo ahí.

## 2. Comprobación rápida manual: `site:`

En Google, buscar `site:thebarnbarconsulting.com/traspasos/` (y lo mismo
para marketing-gastronomico). Si no sale nada, confirma que no está
indexada, independientemente de lo que diga Search Console.

## 3. Ver el código fuente de cada página

Clic derecho sobre la página en el navegador → "Ver código fuente" (o
`Ctrl+U`). Buscar (`Ctrl+F` dentro del código):

- `noindex` — si aparece un `<meta name="robots" content="noindex">`,
  ahí está la causa: la propia página le está diciendo a Google que no
  la indexe.
- `canonical` — comprobar que el `<link rel="canonical" href="...">`
  apunta a la propia URL de la página, no a otra distinta.

## 4. robots.txt del sitio

Entrar en `thebarnbarconsulting.com/robots.txt` directamente en el
navegador. Buscar alguna línea `Disallow:` que incluya `/traspasos/` o
`/marketing-gastronomico/` — si está ahí, Google tiene prohibido
rastrear esa carpeta entera.

## 5. Sitemap

Entrar en `thebarnbarconsulting.com/sitemap.xml` (o `sitemap_index.xml`
si redirige a varios). Confirmar que ambas URLs aparecen listadas. Si no
están, Google tiene menos señal para priorizarlas — no es necesariamente
la causa única, pero ayuda añadirlas si faltan.

## 6. Enlazado interno

En Search Console → **Enlaces** → **Enlaces internos**, buscar cuántos
enlaces internos tiene cada una de las dos URLs. Si el número es muy bajo
o cero, son "páginas huérfanas" — nada del propio sitio apunta a ellas,
lo que las hace más difíciles de descubrir y rastrear para Google,
incluso si no hay ningún bloqueo técnico.

## 7. Si todo lo anterior está limpio: revisar el contenido on-page

Si la página está indexada, no tiene noindex, el canonical es correcto y
tiene enlaces internos, pero aun así no aparece para su keyword
objetivo, el problema ya no es técnico — es que el contenido real de la
página (Title, H1, cuerpo del texto) no usa literalmente la keyword
objetivo de la forma en que la define el research heredado de Saúl
(`investigacion-heredada/roadmap-y-keyword-research.md`, columnas
Title/H1/Meta Descripción de cada URL). Comparar lo que hay publicado
hoy contra esas recomendaciones.

## Resumen del orden de diagnóstico

1 y 2 dicen si está indexada. 3 y 4 dicen si algo lo está bloqueando
explícitamente. 5 y 6 dicen si Google tiene forma de encontrarla. 7 solo
hace falta mirarlo si los 6 anteriores salen limpios.

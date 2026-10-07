# SEO — qué datos de medición necesito (sin conector)

Andrea/Sergio pasarán esto manualmente, sin conectar ninguna cuenta
(regla de la casa). Cadencia propuesta: **mensual**, mismo ritmo que el
dashboard de marketing ya acordado — se puede pasar en el mismo envío.

Nota sobre la fuente: Google Tag Manager en sí no guarda datos, solo
configura qué se mide — los números reales están en **Google Analytics
(GA4)**, que es lo que GTM alimenta. Lo de abajo se saca del informe de
GA4 y, aparte, de Search Console (posiciones de búsqueda, que no pasa por
GTM).

## 1. Snapshot de sitio completo (GA4)

- Sesiones totales del mes.
- Usuarios nuevos vs. recurrentes.
- Fuente de tráfico: orgánico / directo / redes sociales / referral.
- Conversiones del formulario de contacto o de la reunión gratuita de 15
  minutos (si ya hay un evento de conversión configurado en GA4 para
  esto — si no existe todavía, decidme y lo apunto como pendiente aparte,
  no como hueco de dato).

## 2. Por página (GA4) — solo las páginas ya en vivo hoy

Mientras el blog nuevo y las páginas de servicio nuevas no estén
publicadas, esto sirve de punto de partida ("antes") para comparar
después:

- Home.
- Cualquier página de servicio ya en vivo (no las que están pendientes de
  Elementor).
- Artículos de blog ya en vivo (no los 7 nuevos, esos no cuentan hasta
  que se publiquen la semana del 13).

Por cada una: sesiones del mes + conversiones si las tiene.

## 3. Search Console — posiciones de búsqueda

- Posición media, impresiones y clics del mes para las keywords
  principales del research de Saúl (el mismo listado de 145
  keywords/silos ya validado). No hace falta las 145 una por una si es
  mucho trabajo manual — con las 15-20 de mayor prioridad por silo basta
  para la primera entrega.

### Cómo sacar este informe, paso a paso

1. Entrar en [search.google.com/search-console](https://search.google.com/search-console)
   con la cuenta de Google que tenga acceso a la propiedad de
   `thebarnbarconsulting.com`. (Si nadie de TBNB tiene ahora mismo acceso
   de propietario, hay que pedírselo a quien configuró la propiedad
   originalmente, desde Configuración → Usuarios y permisos dentro de
   Search Console — con rol "Completo" o al menos "Restringido" para
   verlo.)
2. En el menú lateral, entrar en **Rendimiento** ("Performance").
3. Arriba del todo, comprobar que estén activadas las 4 métricas: Clics
   totales, Impresiones totales, CTR medio, **Posición media** (son 4
   casillas/pestañas de color, si alguna está apagada no sale en la
   tabla).
4. Ajustar el rango de fechas arriba a la derecha al mes que toque
   reportar (por defecto Search Console muestra los últimos 3 meses).
5. Abajo, en la tabla, pinchar la pestaña **Consultas** ("Queries") —
   ahí sale cada término de búsqueda con sus 4 métricas.
6. Usar el buscador de la propia tabla para filtrar por cada keyword
   prioritaria del research de Saúl (o mirar directamente las que más
   impresiones tengan, suelen coincidir).
7. Para no copiar fila a fila: botón **Exportar** arriba de la tabla →
   exportar a Google Sheets o CSV, y ese archivo (o un pantallazo de la
   tabla filtrada) es lo que me podéis pasar.

## Sobre RankTank

Es un complemento (add-on) de Google Sheets que escanea Google para
comprobar en qué posición aparece cada keyword — vive dentro del Sheet
heredado de Saúl, pestaña "RankTank-3". Ya tiene 102 keywords cargadas,
apuntando a `thebarnbarconsulting.com`, pero nunca ha llegado a
ejecutar el escaneo.

**El problema:** está configurado con *Locale: United States* y
*Language: English*. Para un negocio que opera en español en Madrid y
Barcelona, esto hace que cualquier dato que devuelva no sirva — compara
contra el Google.com en inglés de EEUU, no contra el Google.es en
español que ve un cliente real.

**Cómo corregirlo:** quien tenga acceso a ese Google Sheet debe abrir el
add-on RankTank (menú de complementos dentro del propio Sheet) y cambiar,
en la configuración del proyecto/pestaña "RankTank-3":
- **Locale:** Spain (o, si la herramienta permite nivel de ciudad, Madrid
  — mejor aún si permite configurar también Barcelona como ubicación
  secundaria, dado que TBNB opera en las dos).
- **Language:** Spanish / Español.

Después de corregir el locale, hay que lanzar el escaneo (usa créditos
de la cuenta — ahora mismo hay 0 usados, así que no se ha gastado nada
todavía).

### Qué necesito exactamente si queréis que yo acceda

Importante ser honesto sobre el límite real: **aunque me deis acceso al
Google Sheet, no puedo abrir el menú del complemento RankTank ni tocar
sus desplegables de Locale/Language** — esa configuración vive dentro de
la interfaz propia del add-on (un panel que se abre dentro de Google
Sheets), y no tengo una herramienta en este entorno que pueda interactuar
con esa interfaz. Es un clic de 2 minutos para quien ya tenga el Sheet
abierto — no hace falta dármelo a mí para esa parte concreta.

Lo que sí puedo hacer si me compartís el Sheet (con la herramienta de
Google Drive, acceso de lectura basta): confirmar la lista de 102
keywords ya cargadas, leer los resultados una vez alguien lance el
escaneo con el locale ya corregido, y ahorraros el paso de exportar/
pegarme los datos a mano cada mes. Si queréis eso, compartid el archivo
(o pasadme el enlace) y lo repaso.

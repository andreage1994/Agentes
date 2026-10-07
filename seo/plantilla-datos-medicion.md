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
todavía). Yo no tengo acceso a ese Google Sheet, así que esto lo tiene
que aplicar quien sí lo tenga — si en algún momento queréis darme acceso
de lectura/escritura a ese Sheet puntualmente, dígnoslo y lo repaso, pero
no hace falta un conector permanente para esto, es una corrección de
configuración puntual.

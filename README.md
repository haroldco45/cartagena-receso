# Cartagena en semana de receso

App (PWA) para vender el plan a Cartagena de **Viajamax** en la semana de receso de octubre de 2026 (bloqueos JetSMART desde Medellín).
Asesora: **Alba Rosa Durán** — WhatsApp 317 676 8210.

Publicada en: https://haroldco45.github.io/cartagena-receso/

## Qué hace
- Salidas: 5 al 8, 8 al 11 y 9 al 12 de octubre de 2026. Cada salida se bloquea sola cuando llega su fecha (hora de Colombia).
- Lista de los 30 hoteles del flyer con filtros por colección (Esencial, Confort, Élite) y por alimentación.
- Calculadora: adultos + niños con su edad. Niño dentro del rango del hotel = tarifa niño; mayor del rango = tarifa adulto; menor del rango o sin tarifa = "a consultar".
- Envía la solicitud completa a Alba por WhatsApp.
- Fotos de Wikimedia Commons con crédito automático y videos de Barú y Tierra Bomba.
- No guarda datos personales.

## Publicar en GitHub Pages
1. Crea el repositorio público **cartagena-receso** en **haroldco45**.
2. Sube todo el contenido, incluida la carpeta `img` y `.nojekyll`.
3. **Settings → Pages → main / (root) → Save**.

## Cambiar precios u hoteles
En `index.html` busca `var HOTELES=`. Cada hotel tiene: colección, nombre, habitación, precio adulto, precio niño, rango de edad y alimentación.
Luego sube la versión en `sw.js` (`cartagena-receso-v1` → `v2`).

## Supuestos para confirmar con Alba
- Que los niños mayores del rango del hotel pagan tarifa de adulto.
- Qué cubre exactamente "Full estilo" en Dorado Plaza, Cartagena Plaza y Grand Sirenis.
- El flyer dice "Act. 10/06/2026": confirmar que los precios siguen vigentes.

---
Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados

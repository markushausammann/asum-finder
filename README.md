# Asum Finder

Shows which linnaosa and asum you are in, live via GPS, on Tallinn's official city map.

- `index.html` is the whole app: one static file, no build step.
- Borders: Tallinn city GIS, layer `Linnaosad_asumid` (8 linnaosad, 84 asumid), embedded in the page.
- Base map: Tallinn city GIS `aluskaart_yldine`, loaded live from gis.tallinn.ee.
- GPS only works when the page is served over HTTPS.

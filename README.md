# TrainDodge
**Dodge the train. Know before you go.**

TrainDodge prototype: a live map of train crossings in Waycross, GA (repo: crossing-map).

- `index.html` – mobile-friendly Leaflet + OpenStreetMap map of 77 public at-grade crossings in Ware County, GA (FRA crossing inventory). Tap a crossing for details and Blocked/Clear buttons; reports are shared across phones in real time via the ntfy.sh public relay (12-hour retention; Supabase upgrade prepared in `schema.sql`). Top 5 launch crossings are ringed in orange.
- `ware_crossings.csv` / `ware_crossings.geojson` – cleaned FRA data (crossing ID, street, lat/lon, trains/day, AADT, railroad).

Data: FRA Crossing Inventory (Form 71) – Current, data.transportation.gov.

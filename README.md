# Destin Daybreak

A self-contained conditions dashboard and daily briefing for a Destin, FL trip (Jun 20-27, 2026).

- Live weather, tides, water temp, and NWS alerts (NWS api.weather.gov + NOAA Tides & Currents station 8729511)
- Locally computed sun times, moon phase, beach score, and a solunar bite score
- Manual beach-flag toggle, editable trip ops, checklist, and a per-day itinerary
- Best-beach-day ranking from the multi-day forecast (populates ~7 days out)

Single file, no build step, no dependencies. Everything entered stays in the browser via localStorage.

## Run locally
Open `index.html` in a browser. (Live API calls need to be served over http/https, not opened via file://, to avoid CORS issues.)

# redbus-design-data

Static, public sample data for the redBus Data Sync Figma plugin: ten popular routes per market
(India, Singapore, Malaysia, Indonesia, Peru, Colombia, Cambodia, Vietnam), each with real buses as they appear
in redBus search results. It is only used to fill design mockups.

- `index.json` lists the routes; `<domain>/<route>.json` is one route (buses in English and the local language, plus edge cases).
- Refreshed by hand with `scripts/refresh-data.sh` in the plugin repo.

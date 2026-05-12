# prema-hub — Dashboard hub pro i-prema.de

Login-gated rozcestník pro Prema dashboardy.

- **Live URL:** _bude doplněno po push na GitHub Pages_
- **Heslo:** `Prema` / `prema-2026` (SHA-256 hash uložen v `index.html` jako `ACCESS_HASH`)
- **Změna hesla:** v PowerShellu spustit `python -c "import hashlib; print(hashlib.sha256('USER:PASSWORD'.encode()).hexdigest())"` a hodnotu vložit do `ACCESS_HASH`

## Odkazované dashboardy

1. **prema-dashboard** — orders + počasí + mapa Bundesländer
2. **prema-sos** — Share of Search DE (V1 snapshot)

# raaaw — Website-Prototyp (Variante C, mobile-first)

Statische Seite. `index.html` plus `assets/` (Lausanne-Fonts, Dosen-Renderings, Fotos).

## Deployment
Vercel: neues Projekt aus diesem Ordner importieren.
Framework Preset "Other", kein Build-Schritt, Output Directory leer lassen.

- `index.html` — der gesamte Prototyp
- `assets/` — Fonts, Dosen, Fotos
- `vercel.json` — `noindex`-Header

## Noch offen
- Warenkorb und Formulare sind Attrappen (kein Checkout, kein Versand)
- Preise und Rechtstexte sind Platzhalter
- Für Aufsteller und Kisten fehlen Fotos — die Flächen sind markierte Platzhalter
- vor einem echten Launch den `noindex`-Header entfernen

# raaaw — Website-Prototyp (Variante B)

Statische Seite, eine Datei. Alle Assets (Fonts, Dosen, Fotos, Clips) sind inline.

- `index.html` — der gesamte Prototyp
- `vercel.json` — `noindex`-Header, damit der Prototyp nicht bei Google landet

## Deployment
Vercel: Projekt aus diesem Repository importieren. Kein Build-Schritt, kein Framework —
Framework Preset "Other", Output Directory leer lassen.

## Noch offen
- Warenkorb ist eine Attrappe (kein Checkout)
- Instagram-Permalinks: in `index.html` die Arrays `REEL_URL` und `POST_URL` füllen
- vor einem echten Launch den `noindex`-Header entfernen

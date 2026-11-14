# Adventní vesnička – Pro malé dobrodruhy

Online adventní kalendář pro vanoce.promaledobrodruhy.cz (1.–24. 12. 2026).

Skřítek dobrodruh prochází zasněženou vesničkou. Na klik, klepnutí nebo mezerník dojde k dalšímu domečku a otevře okýnko s odměnou (omalovánka, pohádka, básnička, e-book, body, hra, slevový kód). Den po otevření je v okně scéna z domečku.

## Soubory
- `index.html` – celá hra (HTML + CSS + JS, bez závislostí)
- `vesnicka.webp` – ilustrace vesničky (4344 × 1448 px)
- `sk_*.webp` – skřítek: `r` = doprava, `l` = doleva, `0` stojí, `1`/`2` kroky
- `okno_otevrene.webp` – otevřené okýnko
- `scena_01–24.webp` – scény v oknech
- `logo.jpg` – logo

## Spuštění
Stačí otevřít `index.html`, nebo nasadit jako statický web (GitHub Pages, Netlify, Cloudflare Pages).

## Kde se co mění (v `index.html`)
- `HOUSES` – jména domečků a poloha okýnek na ilustraci
- `ODMENY` – odměna pro každý den (texty, soubory ke stažení, kódy)
- `SCENES` – scény v oknech a jejich zarovnání

## Ještě chybí
- Fáze 3: otevírání jen v daný den (podle serverového data)
- Fáze 4: přihlášení e-mailem, záznam otevřených okýnek, připisování bodů, losování
- Soubory ke stažení, mini hry, slevové kódy ve wpj

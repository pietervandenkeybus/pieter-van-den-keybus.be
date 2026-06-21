# pieter-van-den-keybus.be

Je oorspronkelijke site (blauw "UX- & CX-strateeg"-ontwerp), met **herschreven en verbeterde teksten**
zodat je opnieuw kunt laten indexeren. Statische single-page site (HTML/CSS, geen build).

## Inhoud van deze map
- `index.html` — de volledige pagina (CSS en JS inline)
- `robots.txt`, `sitemap.xml` — `lastmod` op 2026-06-21
- `CNAME` — bevat `pieter-van-den-keybus.be`
- `.nojekyll` — serveert de bestanden ongewijzigd op GitHub Pages

## Opnieuw laten indexeren (na deploy)
1. Vervang de bestaande bestanden in je repo door deze en push.
2. In **Google Search Console** → URL-inspectie → plak `https://pieter-van-den-keybus.be/` → **"Indexering aanvragen"**.
3. Dien eventueel `sitemap.xml` opnieuw in. De bijgewerkte `lastmod` seint dat de pagina is gewijzigd.

## Wat er is aangepast
- **Teksten herschreven** (titel, meta-description, hero, Over mij, Expertise, Projecten, Contact en de
  beschrijvingen in de structured data). De boodschap blijft gelijk, de formuleringen zijn vernieuwd en aangescherpt —
  genoeg verschil om als verversde content te tellen.
- **Zichtbaarheidsfix**: inhoud is nu standaard zichtbaar; de fade-in draait alleen met JavaScript (`body.js`).
  Crawlers, PDF-export en no-JS-bezoekers zien voortaan alle secties.
- **`sameAs` rechtgezet**: verwees naar een niet-bestaand domein (`pietervandenkeybus.be` zonder streepjes).
  Nu gekoppeld aan je echte domeinen: `.be`, `.eu`, `.net` + LinkedIn + Uflow.

## Volledige sameAs (staat al in index.html)
- https://pieter-vandenkeybus.be
- https://pieter-vandenkeybus.eu
- https://pieter-vandenkeybus.net
- https://www.linkedin.com/in/pietervandenkeybus
- https://uflow.be

# Kasper til Cozze

En personlig landingpage til ansøgningen som marketingkoordinator i Cozzes marketingteam. Siden er bygget på koden fra Maki-siden (repoet Maki, som igen bygger på hey-kasper.dk) med ny tekst, Cozzes farver og Cozzes logo.

## Mappen

- site/: selve hjemmesiden. Det er kun denne mappe, der kommer online.
  - index.html: forsiden med al teksten
  - cv.html og ansoegning.html: CV'et og ansøgningen bygget op som PDF'erne i assets/pdf/. Ret teksten begge steder.
  - css/dokument.css: designet til CV og ansøgning (Barlow og Barlow Condensed, farverne fra PDF'erne)
  - en/: de engelske udgaver (index.html, cv.html og application.html). Sprogvælgeren DA/EN i toppen skifter mellem dem. Ret teksten på begge sprog, når noget ændres.
  - 404.html: siden, der vises, hvis adressen er forkert
  - css/styles.css: farver og design. Cozzes farver (petrol #274345 og limegrøn #C4C969) står øverst under `:root`.
  - js/main.js: små forbedringer, fx agentvælgeren i toppen og temaknappen
  - assets/cozze-logo.svg: Cozzes logo i deres grønne logofarve (#336466)
  - assets/og-image.jpg og og-image-en.jpg: billedet, der vises, når linket deles på LinkedIn eller i en mail
- netlify.toml: fortæller Netlify, at site/ skal publiceres.

## Linket

Siden ligger på GitHub Pages: https://kasperai-stack.github.io/cozze/

Den bliver opdateret automatisk, hver gang der pushes (se .github/workflows/pages.yml). Første gang skal GitHub Pages slås til én gang: Settings → Pages → Source: "GitHub Actions".

## Se siden på din egen computer

1. Åbn en terminal i mappen.
2. Skriv `npx serve site` og åbn adressen, der vises i terminalen.

## Godt at vide

- Siden skal ikke kunne findes på Google. Den har `noindex` i HTML'en, i netlify.toml og i robots.txt.
- Der er ingen Google Tag Manager, cookies eller formular på siden. Kontakt sker via "Kald til samtale" (mail til kasmussen80@gmail.com) og telefon.
- Teksten følger Kaspers stemme: dansk, "I" og "jer" til Cozze, ingen tankestreger og ingen opdigtede tal. Fakta kommer fra jobopslaget, cozzebbq.com og Kaspers CV.

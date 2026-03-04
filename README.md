# Nikolaj Blegvad — Portfolio

Portfolio og artikkelarkiv for nikolajblegvad.com.
Bygget som en ren HTML/CSS/JS one-pager uten rammeverk eller CMS.

---

## Filstruktur

    nikolajblegvad.com/
    ├── index.html        ← Forsiden (hero, portfolio, om, kontakt)
    ├── artikler.html     ← Fullstendig artikkelarkiv
    └── bilder/
        ├── hero/         ← De fire bildene øverst på forsiden
        ├── musikk/
        ├── portrett/
        ├── dokumentar/
        └── reportasje/

---

## Legge til et nytt bilde

1. Komprimer bildet til under 300kb (bruk squoosh.app)
2. Gi filen et beskrivende navn: konsert-oslo-2024.jpg
3. Last opp til riktig mappe, f.eks. bilder/musikk/
4. Åpne index.html og finn portfolio-seksjonen
5. Kopier en eksisterende p-item blokk
6. Bytt data-cat, data-src, data-title og tekst i p-cat og p-name

---

## Legge til en ny artikkel

1. Åpne artikler.html
2. Finn riktig årstall-seksjon, eller lag en ny year-divider
3. Kopier en eksisterende article-row blokk
4. Bytt href til den faktiske URL-en til artikkelen
5. Bytt data-cat, data-year, publikasjon, tittel og ingress

Legg alltid nyeste artikler øverst.
Kategorier: musikk · kultur · portrett · samfunn

---

## Oppdatere forsiden (utvalgte artikler)

Forsiden viser 4 utvalgte artikler. Disse redigeres i index.html
i seksjonen merket id="journalism". Samme fremgangsmåte som over.

---

## Publisere endringer

1. Gå til github.com/nikobl21/nikolajblegvad-portfolio
2. Klikk på filen du vil endre
3. Klikk blyant-ikonet
4. Gjør endringen
5. Klikk Commit changes

Netlify publiserer endringen automatisk på nikolajblegvad.com innen 30 sekunder.

---

## Bildeformat

- Format: JPEG
- Bredde: maks 1800px
- Filstørrelse: under 300kb
- Verktøy: squoosh.app (gratis, ingen installasjon)

---

## Teknologi

- Ren HTML5, CSS3 og vanilla JavaScript
- Ingen rammeverk, ingen avhengigheter, ingen database
- Fonter: Playfair Display + IBM Plex Mono + IBM Plex Sans (Google Fonts)
- Hosting: Netlify (gratis plan)
- Kildekode: GitHub

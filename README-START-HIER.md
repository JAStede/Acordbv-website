# ACORD BV — PREMIUM WEBSITE (NL / EN / DE)

## Openen en publiceren
Upload **alle bestanden en mappen** uit deze ZIP naar de root van een nieuwe GitHub-repository (bijvoorbeeld `acord-preview`). Zet in Settings > Pages de branch `main` en folder `/ (root)` aan. De preview-URL wordt `https://<gebruikersnaam>.github.io/acord-preview/`.

De root `index.html` leidt naar `nl/index.html`. De navigatie, taalwisselaar, projectcarrousel, e-mail- en telefoonlinks zijn als echte links in de code opgenomen.

## Wat zit erin?
- 14 pagina's per taal: 42 inhoudspagina's NL/EN/DE, plus startpagina.
- Originele ACORD-logo uit door gebruiker verstrekte JPG, ongewijzigd in de website opgenomen.
- Cinematische AI-conceptbeelden (uitsneden van gegenereerde ontwerpbeelden), geen echte foto's van Acord-projecten. Vervang deze voor publicatie door eigen materiaal.
- Responsive ontwerp, mobiel menu, scrollanimaties en interactieve projectcarrousel.
- SEO-titels, descriptions, canonicals en hreflang. **Let op:** canonical-URL's zijn bedoeld voor het uiteindelijke acordbv.nl, niet voor GitHub-preview.
- Geen betaalde externe libraries of backend. Google Fonts is de enige externe designafhankelijkheid.

## Nog niet definitief / belangrijk
1. **NIET LIVE ZETTEN OP acordbv.nl** voordat bedrijfsgegevens, contactgegevens, certificeringen, projecten en teksten door Acord zijn bevestigd.
2. Previewpagina's staan bewust op `noindex,nofollow`; robots.txt blokkeert crawlers. Zo blijft dit een niet-geïndexeerde testversie (niet privé; iedereen met de URL kan kijken).
3. Contact verloopt via e-mail/telefoonlinks, er is geen formulier dat gegevens op een server opslaat. Test de e-mail en telefoonkoppelingen.
4. De privacytekst is concept en moet door Acord worden gecontroleerd. Laat Duitse en Engelse teksten professioneel nalezen.
5. **WordPress:** dit pakket is een zelfstandige statische website, geen WordPress-thema. Vervang de huidige WordPress-installatie niet door simpelweg dit ZIP als thema te uploaden.
6. Voor migratie: volledige WordPress-back-up, bestaande URL's inventariseren, 301-redirects, DNS/MX/SPF/DKIM bewaren, SSL, cookie-/privacycontrole, Search Console en testen.
7. Voor livegang noindex/robots herzien, sitemap.xml genereren en definitieve URL-structuur instellen.
8. Foto's zijn AI-conceptbeelden en mogen niet als echte Acord-projectdocumentatie worden gepresenteerd.

## Budget
De code is zonder betaalde frontend-frameworks gemaakt. Kies voor de uiteindelijke zakelijke hosting pas na controle van de actuele voorwaarden. Een GitHub Pages preview is handig voor beoordeling; een zakelijke host zoals Cloudflare Pages kan geschikter zijn voor definitieve publicatie.

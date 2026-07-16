# Stijlplan — Zeilrelatiedag (nieuwe site zeilrelatiedag.com)

## Research samenvatting

- **Evenement:** De Zeilrelatiedag bestaat al 30+ jaar en is hét netwerkevenement voor de duurzame energiesector (offshore wind, zon, netbeheer, energiebedrijven). Eén dag zeilen op de Friese meren om relaties in een informele setting te ontmoeten.
- **Organisatie:** Stichting Vrienden van de Zeilrelatiedag · info@zeilrelatiedag.nl
- **Editie:** Vrijdag 18 september 2026 · Friese meren, Friesland · inschrijfdeadline was 1 september.
- **Doelgroep:** beslissers en relaties in de duurzame energiesector (TenneT, Eneco, Vattenfall, Siemens, CrossWind, TotalEnergies, EQUANS e.a.).
- **Kern van de opdracht (klant):** kleine, snel op te leveren one-pager op zeilrelatiedag.com met (1) mooie hero met zeilgevoel, (2) een duidelijke melding dat de inschrijving voor **2026 vol** is en dat men volgend jaar weer kan inschrijven — zonder registratieformulier, en (3) een deelnemers-sectie met een grid van deelnemerslogo's.
- **Wat mist de huidige site (zeilrelatiedag.nl):** gedateerd WordPress-thema (Illdy), weinig sfeer/"zeilgevoel", geen sterke hero, logo's staan er functioneel maar niet als visitekaartje. Het evenement stráált prestige uit, de site nog niet.

**Aannames (checken bij klant):** exacte merk-hexcodes zijn niet uit de live site te herleiden; palet is afgeleid van het bestaande logo (blauw/zeil) en de branche. Deelnemerslogo's worden rechtstreeks van zeilrelatiedag.nl geladen met nette fallback. Cijfers ("30+ jaar", "25+ relaties") zijn afgeleid van de huidige site en representatief.

## Kleuren

Bewust weg van de eerdere demo's: SeaFit gebruikt al een petrol/aqua nautisch palet, Splinter dennengroen/oker, Zowiezo marineblauw/magenta. Voor de Zeilrelatiedag kies ik een **klassiek regatta-palet**: diep nachtblauw (open water bij gouden uur) met een warm **zon-goud** accent dat verwijst naar "zon en wind" — de energie-branche én het zeilgevoel bij zonsondergang. Geen groenige petrol, maar een echt blauw + warm goud.

| Kleur | Hex | Gebruik |
|---|---|---|
| Nachtblauw | `#0C2340` | Primair: nav, hero-basis, footer, koppen op licht |
| Diepwater | `#16385C` | Kaarten, verlopen, secundaire vlakken |
| Horizonblauw | `#3E7CA6` | Subtiel accent, lijnen, iconen |
| Zon-goud | `#E7A23B` | Actiekleur: highlights, focus-states, accenten |
| Zacht goud | `#F4CF8E` | Zachte highlights, badges op donker |
| Zeildoek | `#F5F1E8` | Warme lichte basis-achtergrond (zeilwit) |
| Inktblauw | `#0A1726` | Hoofdtekst |

## Typografie (Google Fonts)

- **Display/koppen:** **Cormorant Garamond** — een verfijnde, hoog-contrast serif met klassiek zeilclub-/prestige-gevoel dat past bij een 30-jarig relatie-evenement. Bewust gène Inter/Poppins.
- **Body:** **Mulish** — een rustige, humanistische sans die zeer goed leesbaar is en de sierlijke display mooi in balans houdt. Niet eerder gebruikt in de demo's.

## Layout-concept

Compacte, premium one-pager (klant vroeg om een kleine site): full-bleed hero met open water en gouden licht, met de tekst uitgelijnd op dezelfde container (`.wrap`) als de navigatiebalk → deelnemers-logogrid → footer. De "inschrijving vol"-melding staat als slanke, vaste balk onderin het scherm zodat de boodschap altijd zichtbaar is zonder de pagina te domineren.

## Signatuur-element

**De horizon-hero met levend water:** een full-bleed zeilscène met gelaagde, zacht bewegende SVG-golven en een zeilboot-silhouet op de horizon; de kop fade-t regel voor regel in. Het tweede bewijsstuk is de **vaste "inschrijving vol"-balk** onderin beeld: geen doodlopende knop en geen storende foutmelding, maar een elegante, informatieve status-strip ("Editie 2026 is volgeboekt — volgend jaar kunt u zich weer inschrijven"). Dezelfde boodschap staat als rustige status-badge in de navigatiebalk. Er is bewust gène registratieformulier: de pagina informeert alleen, precies zoals gevraagd.

## Assets

- Logo en deelnemerslogo's: rechtstreeks van zeilrelatiedag.nl (met fallbacks).
- Sfeerfoto's: Pexels — klassiek/Europees zeilen op open (binnen)water, gouden uur; geen tropische oceaan of megajachten, zodat het Nederlands/Fries aanvoelt. Alle beelden vooraf visueel gecontroleerd.

## Toegankelijkheid / motion

Semantische HTML, zichtbare keyboard-focus, `prefers-reduced-motion` gerespecteerd (golf-, balk- en scroll-animaties degraderen naar statisch). Subtiele, spaarzame GSAP scroll-reveals.

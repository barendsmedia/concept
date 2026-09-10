# STYLE.md — Rebu Kozijnen (kozijnconfigurator)

Losstaande tool-demo voor Rebu Kozijnen (rebukozijnen.nl): een online configurator
waarin de bezoeker in zes stappen een kozijn samenstelt en direct een schaaltekening
plus richtprijs ziet. Geen homepage-concept maar een **functionele demo** — bedoeld om
te laten zien wat een configurator op de site kan doen voor de offerte-aanvraag.

## Kleuren
- `--green-700` `#1B6B45` — Rebu-groen, primaire knoppen en actieve stappen
- `--green-600` `#227A50` — hover/selectiestaat
- `--green-100` `#DCEAE1` — zachte vulling voor gekozen kaarten
- `--paper`     `#F7F5EF` — warm papier, tekenblad-gevoel
- `--surface`   `#FFFFFF` — panelen en balken
- `--line`      `#DAD4C4` — hairlines en rasterlijnen
- `--ink`       `#23262A` — bijna-zwart voor tekst en profielcontouren
- `--glass-a/b` `#E4EEF0` / `#C9DDE2` — koel glasverloop in de tekening

Groen als merkkleur, gecombineerd met een warme papierkleur in plaats van het
gebruikelijke witte SaaS-grijs: de configurator moet aanvoelen als een technische
tekening op de werkbank, niet als een webformulier. Een volledig dark-mode palet is
meegeleverd (`prefers-color-scheme` + `data-theme`), zodat de tool ook in een donkere
omgeving leesbaar blijft.

## Typografie (Google Fonts)
- Display/koppen: **Big Shoulders Display** (smal, industrieel — past bij profielen)
- Body/UI: **Work Sans** (rustig, compact, goed op kleine labels)
- Cijfers/maten: **IBM Plex Mono** (maatvoering, prijzen en specs blijven uitlijnen)

## Layout-concept
Een app-shell in plaats van een scrollpagina: vaste topbalk met stappenteller, links
een configuratiepaneel van 420px, rechts een live tekenvlak, onderin een spec-balk met
richtprijs en CTA's. Onder 900px klapt alles netjes onder elkaar tot een scrollbare
pagina.

## Signatuur-element
**De live schaaltekening.** Elke keuze — type, materiaal, afmeting, indeling, zijlicht,
kleur en glas — wordt direct als technische aanzichttekening opgebouwd in SVG, inclusief
maatlijnen in millimeters, draai-/kiepsymbolen, schuifrichting en een raster op de
achtergrond. Met een schakelaar tussen buiten- en binnenaanzicht (buitenkleur versus
binnenkleur) en zoomknoppen. De richtprijs onderin loopt live mee als bandbreedte.

## Assets
- Geen fotografie: de hele tool is opgebouwd uit inline SVG, dus geen externe
  afbeeldingen en niets dat kan breken bij deployment.
- Het logo in de topbalk is een tijdelijke SVG-markering (`REBU KOZIJNEN`) — te
  vervangen door het echte logobestand van Rebu.
- `og.png` (1200×630) is de share-afbeelding voor WhatsApp/LinkedIn: dezelfde
  papier-en-raster taal als de tool, met de kop "Stel uw kozijn samen en zie direct
  de prijs", een schematisch draaikiepraam met maatlijnen en de richtprijs. Zelf
  gegenereerd (rebukozijnen.nl heeft geen eigen og:image), dus bij een nieuwe kop of
  kleur moet deze opnieuw worden gemaakt.

## Credit
"Demo door Barends Media" staat als chip in de **ondermarge van het tekenvlak** —
de plek van het stempelveld op een echte werktekening. Dat is de enige plek in deze
app-shell die structureel vrij blijft: `PAD.b` houdt onder de tekening altijd 56px
open, en de zoomknoppen zitten rechtsonder. De chip heeft de achtergrondkleur van het
tekenvlak plus een hairline, zodat hij in rust wegvalt maar leesbaar blijft wanneer de
tekening bij inzoomen (tot 220%) eronder schuift. Gecontroleerd op alle vijf
kozijntypes op maximale afmeting, in vijf viewports.

## Aandachtspunten
- Alle prijzen, m²-tarieven, maatgrenzen en meerprijzen zijn **fictief** en dienen als
  rekenvoorbeeld. Deze moeten met Rebu worden ingevuld voordat de tool live gaat.
- De CTA "Vraag offerte aan" toont nu een bevestiging met een link naar rebukozijnen.nl;
  in productie zou hier een formulier of e-mailkoppeling achter komen.

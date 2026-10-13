# Stijlplan — Gerdes Tuin Totaal

## Research samenvatting
- **Branche:** hovenier / tuinaannemer (eenmanszaak). Zwaartepunt volgens de opdrachtgever: schuttingen bouwen, aangevuld met bestrating, tuinaanleg en onderhoud.
- **Doelgroep:** particuliere huiseigenaren met een achtertuin (rijtjeshuis, twee-onder-een-kap) die één betrouwbare vakman zoeken in plaats van drie losse partijen.
- **Werkgebied (aanname):** Noord-Holland Noord. Een bedrijvengids noemt Kerkmeerweg 22, 1724 PK Oudkarspel (gemeente Dijk en Waard) en als oprichtingsdatum 22-01-2021. Nog checken bij de klant.
- **Huidige site:** gerdestuintotaal.nl was vanuit de bouwomgeving niet bereikbaar. Volgens Michael hangt de inhoud tegen de schermranden aan (geen marges en geen max-breedte) en voelt de site niet verzorgd. Daar maakt dit concept het verschil: een royale, gecentreerde layout met veel lucht, een duidelijke hiërarchie en een vaste CTA.
- **Concurrenten (algemeen beeld bij regionale hoveniers):** veel sites zijn generieke WordPress-thema's met een slider, een losse lijst diensten en geen beeld van hoe de klant de tuin straks ervaart. "Beter dan de rest" betekent hier: in één oogopslag laten zien dat Gerdes de hele tuin doet, en dat interactief maken.

## Kleuren (afgeleid van de belettering op de bus)
De bus is zilver met een antraciet/zwarte plaat waarop wit "GERDES" en limegroen "TUIN TOTAAL" staan, plus een groen blad in de kruiwagen. Dat is het merk. Om de bekende AI-combinatie van near-black met acid-green te vermijden, gebruiken we limegroen spaarzaam als accent. Het donker is een **haaggroen** in plaats van zwart, en de basis is licht **bus-zilver/mist**.

| Token | Hex | Gebruik |
|---|---|---|
| `--plate` | `#161A17` | Busplaat-antraciet: navigatie, logo-plaat, hero-kader |
| `--hedge` | `#1D3A27` | Haaggroen: donkere secties (tuinplan, CTA) |
| `--lime` | `#8CD34A` | Logo-lime ("TUIN TOTAAL"): accenten, hotspots, focus |
| `--leaf` | `#3F9A3A` | Bladgroen: knoppen op licht, iconen |
| `--silver` | `#DCE0DD` | Bus-zilver: randen, kaarten |
| `--mist` | `#F3F5F2` | Basis-achtergrond |
| `--ink` | `#18201A` | Tekst |

## Typografie (Google Fonts)
- **Display:** [Unbounded](https://fonts.google.com/specimen/Unbounded): breed, geometrisch en zwaar, net als het "GERDES"-woordmerk op de bus. Robuust en ambachtelijk, niet chic.
- **Body:** [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk): rustig en goed leesbaar, met een warme ondertoon.
- Labels gebruiken de wijde letterspatiëring van "T U I N  T O T A A L" op de bus.

Beide fonts zijn nog niet in eerdere demo's gebruikt.

## Layout-concept
De pagina loopt als een wandeling door een achtertuin: je begint bij de erfgrens (hero met schutting), loopt over het tuinplan langs alle onderdelen en eindigt bij de bus voor de deur en de uitnodiging voor een gratis tuinadvies.

## Signatuur-element
**Het interactieve tuinplan.** Een getekende bovenaanzicht-plattegrond van een Nederlandse achtertuin met schutting, terras, gazon, borders, tuinhuis en haag. Elk onderdeel is een hotspot. Klik, tik of tab erop, dan licht de zone limegroen op en een paneel vertelt wat Gerdes daar doet. Zo wordt de naam "Tuin Totaal" letterlijk zichtbaar: één vakman voor elk vlak van je tuin.

Daarnaast herhaalt de vorm van de busplaat (zwart vlak met afgeronde hoeken) zich in de navigatie en het hero-kader, zodat de site direct herkenbaar is voor wie de bus in de straat ziet staan.

## Beeld
- `bus.jpg`: eigen foto van de bedrijfsbus (aangeleverd door Michael).
- Overige foto's: Unsplash, met een groene fallback-achtergrond als een foto niet laadt. Bij voorkeur later vervangen door projectfoto's van Gerdes zelf.
- Logo: als SVG nagetekend van de busbelettering, omdat het originele bestand niet op te halen was. Vervangen door het echte logobestand.

## Toegankelijkheid / motion
Semantische secties, zichtbare focus in limegroen, het tuinplan bedienbaar met toetsenbord (knoppen en pijltjestoetsen), en GSAP-reveals die uit staan bij `prefers-reduced-motion`.

# STYLE.md — Visboot-Huren.nl (Eiland van Maurik / Tiel)

Demo-concept voor **Visboot-Huren B.V.**: verhuur van volledig uitgeruste roofvisboten
(FishHawk 450) — met of zonder vaarbewijs, inclusief Garmin Livescope.

## Kleuren
- `--deep`   `#062C27` — diep, donker water (hero, donkere secties, footer)
- `--water`  `#0B463C` — dieptgroen water, kaarten & verlopen op donker
- `--pine`   `#10695A` — helderder riet/water-groen, secundaire accenten
- `--spray`  `#5FE0BE` — "Livescope"-mint, technisch accent (sonar, highlights, badges)
- `--amber`  `#F4A62A` — zonsopkomst-amber, **primaire CTA** & aandachtsvlakken
- `--amber-2``#E0890F` — dieper amber voor hover/tekstaccent op licht
- `--cloud`  `#F2F7F4` — lichte mist-achtergrond (lichte secties)
- `--sand`   `#F6F0E4` — warme zand-tint voor afwisseling
- `--ink`    `#04160F` — bijna-zwart bosgroen (tekst op licht, topbar)

Bewust wég van de generieke "AI-look". Ook bewust anders dan de bestaande
maritieme demo **SEAFIT** (dat is premium petrol + helderblauw + messing): dit palet
is een *roofvisser-bij-dageraad*-sfeer — donker moerasgroen water met een warme
zonsopkomst-amber en een koele "Livescope"-mint als technisch accent. Amber is de
primaire actiekleur, mint markeert de high-tech uitrusting (Garmin/Livescope).

## Typografie (Google Fonts)
- Display/koppen: **Anton** — fors, poster-achtig, expeditie/outdoor-gevoel.
- Body & UI: **Sora** — modern, licht technisch (past bij de Garmin-electronica), rustig leesbaar.

Geen Inter/Poppins-default; ook geen overlap met eerdere demo's (Big Shoulders,
Bricolage, Fraunces, Space Grotesk zijn al gebruikt).

## Layout-concept
Full-bleed, donkere "op-het-water"-hero met een eigen SVG-boot + sonar-sweep,
afgewisseld met lichte secties; brede sonar-/golfscheiders en cijfers die uit de
grid steken. Rustig en strak, één gedurfd interactief element.

## Signatuur-element
**De vaarbewijs-schakelaar** — een grote, interactieve segment-toggle
"Zonder vaarbewijs (15 pk)" ⇄ "Met vaarbewijs (60 pk · Livescope)". Bij omschakelen
wisselt geanimeerd het hele bootpaneel: foto, badge, motorvermogen, snelheid,
uitrusting en beschrijving. Zo is het onderscheid — dé kernvraag van elke klant —
in één oogopslag en tastbaar duidelijk. Ondersteund door een **live sonar-animatie**
in de hero die de high-tech Livescope-belofte visueel maakt.

## Extra vereisten (uit de opdracht)
- **Language switcher** bovenin: NL (actief) · DE · EN — werkend voor de belangrijkste
  koppen/labels; Duitsers zijn een kern-doelgroep, dus de DE-schakelaar demonstreert
  dat de vertaling er al staat. Site-inhoud blijft verder Nederlands.
- **Contactformulier + contactgegevens** op de homepage (naam, e-mail, telefoon,
  gewenste datum, keuze boot, bericht) met echte contactgegevens.

## Assets & foto's
De echte bootfoto van de klant (`boat-vrij.jpg` van de huidige site) is nu verwerkt in
de hero-achtergrond, het bootpaneel (vaarbewijsvrije uitvoering) én de uitrustings-sectie,
zodat de eigen boot herkenbaar terugkomt. Overige beeld-slots gebruiken sfeervolle
roofvis/Hollands-water-stockfoto's (Unsplash) in een container mét gradient-fallback en
`onerror`-afhandeling, zodat een niet-ladende foto nooit "gebroken" oogt. Aan te leveren
extra bootfoto's (o.a. de 60 pk-uitvoering) vervangen de resterende stock 1-op-1.

## Motoren
Beide FishHawk 450-uitvoeringen varen met **Mercury**-buitenboordmotoren (15 pk
vaarbewijsvrij / 60 pk met vaarbewijs).

## Toegankelijkheid / motion
Semantische HTML, zichtbare keyboard-focus, `prefers-reduced-motion` gerespecteerd
(sonar- en reveal-animaties degraderen naar statisch). GSAP + ScrollTrigger, spaarzaam
ingezet voor fade/rise-reveals.

# STYLE.md — Ultra Marine Benelux

## Stijlrichting: "Aluminium × Arctic Ice"
Ultra Marine bouwt gelaste aluminium boten voor het echte water. De stijl is daarom
koud, technisch en premium: diep marineblauw/near-black als basis, een arctisch
staalblauw accent en geborsteld-aluminium zilver. Zo voelt de site meteen een klasse
professioneler dan de huidige Engelse spec-site, en sluit hij aan op hun witte logo op
donkere achtergrond en de "arctic" fotografie.

## Kleuren
| Rol | Hex |
|-----|-----|
| Marine near-black (basis) | `#0B1418` |
| Marine 2 (secties/cards) | `#0F1D24` |
| Arctisch staalblauw (accent) | `#38A7DE` |
| Staalblauw diep (hover/links) | `#1E6FA8` |
| Geborsteld aluminium | `#C6D0D6` |
| Aluminium licht / paper | `#F4F7F8` |

## Typografie (Google Fonts)
- **Display:** Sora (700/800) — technisch, strak, karaktervol.
- **Body:** IBM Plex Sans (400/500/600) — nuchter, industrieel, goed leesbaar.

## Layout-concept
Full-bleed donkere hero → afwisselend lichte en donkere secties met een consequent
staal/aluminium accentsysteem; brede witruimte, strakke rasters. De hero-content is
links uitgelijnd op exact hetzelfde raster (`.wrap`) als de blokken eronder (logo,
"Waarom Ultra Marine", series en footer starten op dezelfde linkerlijn).

## Signatuur-element
De interactieve **series-verkenner**: de bezoeker filtert het complete programma
(10+ series) live op *gebruik* (vissen / recreatie / werk) én *rompvorm*
(diepvorm / platbodem / multihull / RIB). De bootkaarten faden en herschikken bij
elke keuze.

## Beeld & logo (op verzoek van de klant)
Op verzoek gebruikt de demo de **eigen assets van Ultra Marine**:
- **Logo:** hun originele `logo-white.svg` in nav én footer.
- **Hero:** de originele intro-/arctic-foto (TRV 640 JET).
- **Bootkaarten:** per serie een eigen fabrieksfoto van ultra-marine.nl.

Deze bestanden worden nu **live** van `ultra-marine.nl` geladen (met `preconnect`,
`preload` op de hero, `loading="lazy"` + `decoding="async"` op de kaarten en een
`onerror`-fallback). Let op: die server reageert soms traag; voor de definitieve
oplevering is het netter de echte logo- en fotobestanden lokaal in
`/ultra-marine/assets/` te hosten (downloaden en zelf serveren), zodat de branding
behouden blijft én de pagina overal snel laadt.

## Demo-signalering (Barends Media)
Rechtsonder staat een vaste (`position:fixed`) **demo-badge** met een duidelijke link
naar [barendsmedia.nl](https://barendsmedia.nl/). Zo is meteen zichtbaar dat dit een
concept van Barends Media is, en fungeert de badge tegelijk als subtiele portfolio-CTA.

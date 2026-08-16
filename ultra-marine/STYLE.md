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
staal/aluminium accentsysteem; brede witruimte, strakke rasters.

## Signatuur-element
De interactieve **series-verkenner**: de bezoeker filtert het complete programma
(10+ series) live op *gebruik* (vissen / recreatie / werk) én *rompvorm*
(diepvorm / platbodem / multihull / RIB). De bootkaarten faden en herschikken bij
elke keuze.

## Performance-uitgangspunt (belangrijk)
De demo is **volledig self-contained**: het logo is een inline SVG en foto's komen van
een snel CDN met `loading="lazy"`, `decoding="async"` en vaste afmetingen. Er wordt
**niets** live van `ultra-marine.nl` geladen (die server reageert traag), zodat de
pagina overal — ook lokaal geopend — direct in één keer laadt. Voor oplevering levert
de klant idealiter de echte logo- en fotobestanden aan om lokaal mee te hosten.

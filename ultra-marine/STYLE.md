# STYLE.md — ULTRA MARINE (Rijswijk)

Demo-concept voor Ultra Marine: fabrikant van aluminium boten (20+ jaar), 10+ series voor
vissen, recreatie en werk op het water. Werkgebied Benelux.

## Kleuren
- `--abyss`   `#07131B` — diep marine near-black, hoofd-donkerkleur (hero, footer)
- `--hull`    `#0D2331` — staalnavy voor secties en kaarten
- `--steel`   `#16394C` — lichter staalblauw voor verlopen en randen
- `--ice`     `#38A7DE` — arctic/ijsblauw, primair accent & CTA (uit de merk-uitstraling)
- `--ice-2`   `#7FD6F7` — helder highlight-blauw voor gradients en hover
- `--alu`     `#B9C7CF` — geborsteld aluminium zilver (materiaal-signatuur)
- `--frost`   `#EEF4F7` — lichte "ijs/schuim" achtergrond voor lichte secties
- `--ink`     `#04101A` — bijna-zwart voor topbar/stats

Palet is afgeleid van het merk: wit logo op donkere achtergrond met arctisch/staalblauw.
Bewust wég van de generieke "AI-look" én van de eerdere maritieme demo (SEAFIT, petrol +
messing). Hier draait alles om **aluminium + arctic ice**: koud, technisch, premium.

## Typografie (Google Fonts)
- Display/koppen: **Sora** (700–800, modern-technisch, krachtig — "springt van het beeld")
- Body: **IBM Plex Sans** (engineered, precisie-gevoel dat past bij aluminiumbouw)

Bewust anders dan SEAFIT (Big Shoulders + Manrope) zodat de demo's zichtbaar verschillen.

## Layout-concept
Full-bleed arctische hero met de eigen intro-boot van Ultra Marine, gevolgd door een
donker "waterlijn"-stramien met technische spec-badges, een filterbare series-verkenner
en lichte proces-/social-proof-secties — koud staalblauw als rode draad.

## Signatuur-element
**De series-verkenner** — een interactieve filter-teaser waarmee de bezoeker het complete
programma (10+ series) live filtert op *gebruik* (vissen / recreatie / werk) en *rompvorm*
(diepvorm / platbodem / multihull / RIB). De boot-kaarten faden en herschikken bij elke
keuze — precies het "kies uit 10+ series"-idee van de huidige site, maar dan als
verrassend en tastbaar interactie-element. Ondersteund door een arctic hero met een
subtiele parallax op de intro-foto.

## Assets
- Logo (wit) en herofoto (TRV 640 JET arctic) rechtstreeks van ultra-marine.nl.
- Boot-/serie-foto's van de huidige site, aangevuld met neutrale Noord-Europese
  water-sfeer waar nodig. Geen tropische/oceaanbeelden — koel, Noordzee/Benelux.

## Toegankelijkheid / motion
Semantische HTML, zichtbare keyboard-focus, `prefers-reduced-motion` gerespecteerd
(scroll-reveals en parallax degraderen netjes). GSAP + ScrollTrigger, spaarzaam ingezet.

# STYLE.md — SEAFIT (Heerhugowaard)

Demo-concept voor SEAFIT: opbouw, reparatie, refit en onderhoud van (kleine tot middelgrote) boten.

## Kleuren
- `--petrol`   `#082B33` — diep petrol, hoofd-donkerkleur (hero, secties)
- `--petrol-2` `#0E4553` — lichter petrol voor kaarten/verlopen
- `--aqua`     `#0F85C4` — logokleur (uit het SEAFIT-logo), primair accent & CTA
- `--aqua-deep``#0A6699` — afgeleide, dieper blauw voor tekstaccenten op licht
- `--brass`    `#C79A4B` — nautisch messing, sterren & highlights
- `--foam`     `#F2F7F6` — lichte "schuim"-achtergrond
- `--ink`      `#04171C` — bijna-zwart petrol (topbar, footer, stats)

Premium-maritiem palet, bewust wég van de generieke "AI-look" en van de eerdere
Heerhugowaard-demo's (groen bij Splinter, marineblauw/magenta bij Zowiezo). Het
accent is afgestemd op de blauwe logokleur van SEAFIT (#0F85C4).

## Typografie (Google Fonts)
- Display/koppen: **Big Shoulders Display** (fors, industrieel-nautisch)
- Body: **Manrope** (rustig, modern, goed leesbaar)

## Layout-concept
Doorbreekt bewust het "alles-in-een-container"-stramien: full-bleed hero met een
boot die van de rand loopt, een reuzen-SEAFIT-waterlijn op de achtergrond,
golf-SVG's als scheiders en cijfers/kaarten die buiten de grid steken.

## Signatuur-element
**De refit-reis** — een GSAP-gepinde horizontale scroll waarbij de boot door 5
refit-stations schuift (binnenkomst → polyester & gelcoat → motor → poets &
Ceramic Pro → te water). De titel blijft tijdens de hele reis in beeld en de
animatie start zodra de sectie boven in beeld komt. Tweede bewijsstuk: een
**before/after-reveal** met een echte SEAFIT-boot (realistische verweer-treatment
voor "voor", spiegelend voor "na"). Aangevuld met een **play-knop in de hero** die
een modal opent met de eigen werkplaatsvideo van SEAFIT.

## Assets
- Logo, projectfoto's en video: rechtstreeks van seafit.nl (met nette fallbacks).
- Alle foto's tonen kleine/middelgrote boten en de eigen diensten — geen oceanen,
  duikers of mega-jachten.

## Toegankelijkheid / motion
Semantische HTML, zichtbare keyboard-focus, `prefers-reduced-motion` gerespecteerd
(horizontale scroll degradeert naar een verticale kaartenlijst op mobiel).

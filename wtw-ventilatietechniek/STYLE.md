# Stijlplan — WTW Ventilatietechniek

## Bedrijf & branche
Revisie, reparatie én verkoop van ventilatiemotoren en WTW-units (Alkmaar, Berenkoog 56a).
10+ jaar ervaring, snelle afhandeling (vaak retour dezelfde dag), 2 jaar garantie op
kogellagers. Merken: Brink, Itho, Zehnder, Orcon, Duco, Agpo, Vent-Axia, S&P, Nibe, Ubbink.
Doelgroep: particulieren met een defecte WTW-unit/ventilatiemotor én installateurs die
revisie uitbesteden. Branche = techniek/installatie: vertrouwen, precisie en snelheid tellen.

## Wat er mis is met de huidige site
Functionele maar generieke OpenCart-webshop: geen sterk verhaal, geen duidelijke
afspraak-/inleverflow, zwakke hiërarchie en gedateerde uitstraling. Het vakmanschap
(motor openmaken, lagers vervangen, uitbalanceren) komt visueel niet tot z'n recht.

## Kleuren (afgeleid van het blauwe logo + "schone lucht"-thema)
- `--navy`      #0A1B2E  — diepe technische marineblauw (basis, donkere secties)
- `--steel`     #163B57  — staalblauw (kaarten/diepte)
- `--sky`       #2BB0D6  — helder logoblauw / luchtstroom-accent
- `--air`       #5FE3D0  — fris aqua (airflow, tweede accent, hover)
- `--mist`      #EEF4F8  — koele off-white achtergrond
- `--ink`       #0E1922  — tekst
- `--white`     #FFFFFF

## Typografie (Google Fonts — bewust technisch, nog niet gebruikt in andere demo's)
- Display/koppen: **Space Grotesk** — mechanisch, precies, engineering-gevoel
- Body/UI: **IBM Plex Sans** — technische leesbaarheid, past bij installatiebranche

## Layout-concept
Donkere, technische hero met bewegende luchtstroom-lijnen; daaronder rustige lichte
secties in een strak grid dat het proces (inleveren → reviseren → retour) en de
diensten helder maakt, met vertrouwen-blokken (garantie, snelheid, merken).

## Signatuur-element
1. **Airflow-hero:** subtiele, geanimeerde luchtstroom-streamlines die over de hero
   bewegen — visualiseert letterlijk "ventilatie" en blijft hangen.
2. **Afspraakformulier** (kernwens klant): een verzorgd, kaartachtig afspraakformulier
   met 3 duidelijke standaardvragen (type apparaat, gewenste dienst, voorkeursmoment)
   plus contactgegevens. Live samenvatting en nette validatie-feedback.

## Animatie
Spaarzame scroll-reveals (IntersectionObserver) + CSS airflow-animatie in de hero.
`prefers-reduced-motion` wordt gerespecteerd (alle beweging uit).

# Stijlplan — Splinter Deuren (Heerhugowaard)

## Research samenvatting

- **Bedrijf:** Splinter Deuren B.V., deurspecialist én webshop in Heerhugowaard (Noord-Holland). Nieuwe showroom aan het Nijverheidsplein 57 in aanbouw (verwacht medio 2026).
- **Diensten:** Voordeuren, achterdeuren/schuifpuien, binnendeuren, utiliteitsdeuren (geluid-, inbraak- en brandwerend), kozijnen en deurbeslag. Volledige full-service: opmeten, maken én monteren met eigen personeel. De live site is een webshop (WooCommerce-achtig) met winkelmand, verlanglijst, account en betaalmethoden.
- **USP's:** eigen meet- en montagedienst (geen onderaannemers), transparante vaste prijs voor het hele traject, groot assortiment stijlen (klassiek t/m modern), gratis en vrijblijvend advies, online bestellen óf op maat laten maken.
- **Contact:** Nijverheidsplein 57, 1704 RB Heerhugowaard · 085 - 40 14 717 · contact@splinterdeuren.nl · WhatsApp 06 31 79 07 00 · ma–vrij 09:00–17:00 · KVK 96228482.
- **Wat mist de huidige site:** de bestaande webshop is technisch prima en mobielvriendelijk, maar oogt generiek en productcatalogus-achtig — de kern van hun verhaal ("wij meten, maken én monteren zelf, één vaste prijs") komt nergens groot en gevoelsmatig naar voren. Geen sterk hero-statement, geen visuele nadruk op vakmanschap, geen concreet verschil tussen "oude deur" en "nieuwe deur" getoond.
- **Concurrentie:** Deuren Team, Deurencompleet, Kuiters Timmerfabriek, Rodako Deuren, Carper Timmerfabriek — allemaal vergelijkbare productcatalogus-opzet met gratis-offerte-belofte. Onderscheidend vermogen zit in de eigen full-service (meten/maken/monteren) en transparante prijs, niet in het aanbod zelf — dat verhaal moet in het concept centraal staan.

**Aanname (checken bij klant):** exacte hex-kleurcodes van het merk zijn niet uit de live site te herleiden (styling zit in externe, niet-inspecteerbare CSS binnen deze sandbox). Het logobestand heet `lichtlogo` (lichte variant), wat erop wijst dat het merk primair op een donkere achtergrond wordt getoond — dit concept is daarop gebaseerd. Klantcijfers en reviews zijn representatieve voorbeelden.

## Kleuren

Afgeleid van de branche (deuren, hout, deurbeslag) en de donkere-achtergrond-toepassing van het bestaande logo. Bewust weg van het "near-black + fel accent"-cliché door voor een dieper, groenig antraciet te kiezen in plaats van puur zwart, gecombineerd met warme koper- en okertinten die refereren aan deurbeslag en hout.

| Kleur | Hex | Gebruik |
|---|---|---|
| Dennengroen (donker) | `#1E3229` | Primair: nav, hero-achtergrond, footer, koppen op licht |
| Okeramber | `#D98B3D` | Actiekleur: CTA-knoppen, links, focus-states, winkelmand-badge |
| Koperbrons | `#B8814B` | Accent: iconen, lijnen, deurbeslag-motief |
| Walnoot | `#6B4A34` | Tertiair: kaartranden, hout-referentie |
| Warm ivoor | `#F5F1E8` | Basis-achtergrond secties |
| Inktgroen-zwart | `#171F1A` | Hoofdtekst |

## Typografie

- **Display:** [Fraunces](https://fonts.google.com/specimen/Fraunces) — een karaktervolle, ambachtelijke serif met warme details; past bij het vakmanschap en de "op maat gemaakt"-belofte zonder de crème/serif/terracotta-cliché-combinatie te herhalen (ander kleurenpalet, donkere basis i.p.v. crème).
- **Body:** [Public Sans](https://fonts.google.com/specimen/Public+Sans) — strak, functioneel en zeer leesbaar; complementeert de sierlijke display-font en houdt productinformatie (afmetingen, prijzen, opties) helder.

## Layout-concept

Een webshop-homepage met een donkergroene navbalk (servicebalk → logo + gecentreerd categoriemenu met mega-dropdowns → rechts uitgelijnde webshop-iconen: zoeken, verlanglijst, winkelmand met telbadge, account, keurmerk). Daaronder bouwt de pagina het verhaal op als het eigen proces van Splinter Deuren: eerst het contrast tonen (oud vs. nieuw in de hero), dan het aanbod als productgrid met prijzen, de USP's, de werkwijze (opmeten → maken → monteren) en tot slot bewijs en call-to-action. Contentbreedte 1300px voor een ruime laptop-/desktoplayout.

## Signatuur-element

**Voor/na-schuifslider in de hero.** Bezoekers slepen een verticale lijn tussen een verweerde, gedateerde voordeur en een strakke nieuwe Splinter Deuren-deur. Dit maakt de belofte ("uw oude deur verdient een opvolger") direct tastbaar in plaats van abstract, en is het ene gedurfde element in een verder rustige, strakke pagina.

## Webshop-elementen

Herkenbaar als webshop, met behoud van de groene huisstijl: servicebalk (advies · bezorging & montage · iDEAL), donkergroene shopbalk met rechts uitgelijnde iconen (zoeken/verlanglijst/winkelmand met telbadge/account/keurmerk), uitgebreide mega-dropdowns voor Deuren, Deurbeslag en Kozijnen, een productgrid met SKU's/prijzen en "In winkelmand"/verlanglijst-interactie (front-end demo met toast), en betaalmethoden + Webshop Keurmerk in de footer.

## Bronnen

Content en gegevens overgenomen van splinterdeuren.nl (homepage, /contact/), bezocht op 2026-07-13. Productfoto's en logo hotlinked vanaf de bestaande site (`usercontent.one/wp/www.splinterdeuren.nl/...`) — voor livegang aanbevolen dit lokaal te hosten. Sfeerfoto's (voor/na-slider, werkplaats) zijn royalty-free stockfoto's van Unsplash. Prijzen/SKU's zijn indicatief; winkelmand, zoeken en betalen zijn visuele demo's, niet functioneel.

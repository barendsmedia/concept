Dit repository wordt gebruikt om homepage-concepten (demo's) te bouwen voor potentiële klanten van Barends Media. Wanneer gevraagd wordt om "een demo", "een concept" of "een voorstel" voor een bedrijf te maken, volg dan onderstaande workflow volledig.

Doel: een visueel overtuigende, moderne homepage neerzetten die de potentiële klant direct laat zien wat een nieuwe website voor hen kan betekenen. Het is een verkooptool: eerste indruk telt zwaarder dan technische perfectie.

Workflow

1. Research (verplicht vóór het bouwen)

Bezoek de huidige website van het bedrijf (indien opgegeven of vindbaar).
Noteer: branche, doelgroep, diensten/producten, USP's, contactgegevens, werkgebied.
Noteer wat er mis is met de huidige site (verouderde stijl, geen mobile, slechte hiërarchie) — dit bepaalt waar het concept het verschil moet maken.
Kijk naar 2–3 directe concurrenten in dezelfde branche om te bepalen wat "beter dan de rest" betekent.

2. Stijlbepaling (vastleggen vóór het coderen)

Maak eerst een kort stijlplan en leg dit vast in STYLE.md in de projectmap:
Kleuren: 4–6 hexwaarden, afgeleid van de branche en (waar bruikbaar) het bestaande logo/merk/website. Niet zomaar een generiek palet.
Typografie: een karaktervolle display-font + complementaire body-font (Google Fonts). Kies bewust per project, niet standaard Inter/Poppins op elke demo.
Layout-concept: één zin die de opbouw beschrijft.
Signatuur-element: het ene onderdeel waardoor deze demo blijft hangen (bijv. een interactieve configurator-teaser, een before/after-slider, een opvallende hero-behandeling). Eén gedurfd element, de rest rustig en strak.


Vermijd de herkenbare "AI-look": crème achtergrond + serif + terracotta accent, near-black + één felle acid-green, of krantenlayout met hairlines. Alleen gebruiken als het écht bij het merk past.

3. Bouwen

Techniek:
Eén zelfstandig index.html-bestand per klant: HTML, CSS en JS embedded. Geen build-steps. Zo is de demo direct te openen en te delen.
Volledig responsive (mobile-first testen, inclusief de nodige breakpoints inbegrepen).
Semantische HTML, zichtbare keyboard-focus, prefers-reduced-motion respecteren.
Afbeeldingen: gebruik van stock foto's (unsplash, pexels), CSS-gradients, SVG-illustraties of neutrale placeholders met duidelijke labels ("[Foto: dakkapel plaatsing]").


Voorstel voor opbouw qua secties (aanpassen per branche, niet klakkeloos overnemen):

Sticky navigatie met logo(tekst) + CTA-knop
Hero met sterke kop, subregel en primaire CTA — de hero is de thesis van het concept
USP's / waarom-dit-bedrijf (3–4 punten)
Diensten of producten
Proces / werkwijze (alleen als de branche dit vraagt)
Social proof: reviews, cijfers, keurmerken
CTA-sectie (offerte aanvragen / contact)
Footer met contactgegevens en NAP-data

Subtiele animaties: scroll-reveals en hover-states zijn prima, maar georchestreerd en spaarzaam. Overdaad voelt AI-gegenereerd. Groot voorstander van minimale gsap animaties waarbij elementen bijvoorbeeld in beeld faden als je er naartoe scrollt.

4. Copy

Alle teksten in het Nederlands, tenzij anders gevraagd.
Schrijf realistische, branchespecifieke copy — geen lorem ipsum. Gebruik informatie van de huidige website waar beschikbaar.
Concrete verkopende koppen ("Uw dakkapel geplaatst in 1 dag") boven vage claims ("Kwaliteit staat voorop").
CTA's benoemen exact wat er gebeurt: "Vraag gratis offerte aan", niet "Verstuur".
Echte contactgegevens van het bedrijf overnemen indien bekend; anders duidelijke placeholders.

5. Opleveren

Bestandsstructuur: het resultaat moet geplaatst worden in een map /concepts/{bedrijfsnaam-slug}/index.html
Sluit af met een korte samenvatting voor Michael:

De gekozen stijlrichting en waarom (2–3 zinnen, bruikbaar in het klantgesprek)
Het signatuur-element
Eventuele aannames die gecheckt moeten worden bij de klant


Checklist vóór oplevering

Responsive gecontroleerd (mobiel, tablet, desktop)
Geen gebroken externe resources
Copy is Nederlands, foutloos en branchespecifiek
Stijl wijkt zichtbaar af van eerdere demo's in demos/ (check bestaande mappen)
STYLE.md aanwezig met palet, fonts en onderbouwing
Contactgegevens/NAP kloppen of zijn duidelijk als placeholder gemarkeerd


Voorbeeldprompt: "Maak een demo voor https://www.voorbeeldklant.nl"

→ Doorloop stap 1 t/m 5 volledig. Vraag alleen om verduidelijking als de branche of het bedrijf niet te achterhalen is.

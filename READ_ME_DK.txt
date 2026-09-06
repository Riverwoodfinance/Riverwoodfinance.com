RIVERWOOD FINANCE — WEBSITE / EARLY ACCESS
Version 1.0 · 6. september 2026

UPLOAD TIL GITHUB
1. Pak ZIP-filen ud på computeren.
2. Læg de syv websitefiler nedenfor i samme mappe i GitHub-projektet som den nuværende index.html. Erstat index.html med den nye fil.
3. Behold den eksisterende CNAME-fil og den eksisterende Pages-/domæneopsætning. Pakken ændrer ikke disse indstillinger.
4. Gem/commit ændringen og afvent projektets normale publicering. Genindlæs derefter hjemmesiden.

Det er de udpakkede filer, som skal uploades — ikke ZIP-filen som en enkelt fil.
Denne læsevejledning behøver ikke ligge på det offentlige website.

WEBSITEFILER
index.html
riverwood-intelligence-background.webp
riverwood-intelligence-background-mobile.webp
riverwood-finance-logo-light.png
riverwood-finance-logo.png
riverwood-favicon.png
riverwood-social-preview.jpg

DESIGN OG INDHOLD
Siden er en kort, engelsksproget teaser med den valgte 03-retning: et diskret, bølgende datamotiv i marineblå/teal.
Baggrunden ligger bag hele siden. Tekst og knapper er HTML og ikke indbygget i baggrundsbilledet.
Den gamle tre-scene-animation og dens HTML/CSS er fjernet.
Q0–Q5, den detaljerede arkitektur, fondseksempler og scores vises ikke på den nye side.
Udviklingsstatus, planlagte anvendelser og tidlige professionelle dialoger er tydeligt adskilt fra et lanceret produkt.
Det eksisterende logo er bevaret som uændret originalfil. Den nye lysere variant er afledt af samme grafik til den mørke baggrund; den er ikke et nyt, genereret logo.

TEKNIK
Statisk HTML med indbygget CSS. Ingen JavaScript-afhængigheder, tredjepartsfonte, analytics eller sporingskode er tilføjet.
Desktop og mobil bruger hver sin optimerede WebP-baggrund.
Navigationen bruger interne ankre. Kontaktknappen åbner et nyt udkast i den besøgendes mailprogram til info@riverwoodfinance.com. Der er ikke en formularserver eller en automatisk tilmeldingsliste.
Social-preview-billedet bruges i sidens Open Graph-metadata. Det er lavet fra den kodede side og indeholder den samme udviklingsstatus.

KONTROL
HTML/CSS er kontrolleret, lokale filhenvisninger er gennemgået, og alle ankre har et mål.
Browser-rendering er kontrolleret i Chromium ved 1440, 1366, 1920, 768, 390 og 320 pixels bredde. Der er ikke konstateret horisontalt overflow i disse tests.
Logoets proportioner, navigationen til kontaktsektionen, tastaturadgang og reduced-motion-indstillingen er kontrolleret.
Dette er ikke en test på fysiske iPhone-/Android-enheder eller i alle browsermotorer.

OM DE GAMLE OFFENTLIGE ASSETS
De tidligere riverwood-loop-*.png-filer og riverwood-intelligence-monitor.png bruges ikke længere af den nye side.
Upload af denne pakke sletter ikke gamle filer. Efter kontrol af den nye side kan gamle, ubrugte demo-assets fjernes fra den publicerede mappe, så de ikke fortsat ligger på deres tidligere billedadresser.
En ny hjemmeside fjerner ikke eksisterende repo-historik, indekserede kopier eller materiale, som andre allerede har gemt.

Den eksisterende live-hjemmeside er ikke ændret ved udarbejdelsen af denne pakke. Publicering sker først ved upload til dit projekt.

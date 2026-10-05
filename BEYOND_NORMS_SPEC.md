# Beyond Norms — första preview-specifikation

## Projekt

- Varumärke: **Beyond Norms**
- Webbplats: `beyondnorms.se`
- GitHub: `tomasljonsson-png/beyondnorms-site`
- Cloudflare Workers & Pages: `beyondnorms-site`
- Ändra inte andra projekt, särskilt inte You, Me &.

## Syfte

Skapa en kort, professionell första presentation av Thomas som **energikonsult för fastigheter**. Besökaren ska på några sekunder förstå kopplingen mellan energi, bygg- och fastighetsteknik och data, och enkelt hitta kontaktuppgifter.

## Målgrupp

Fastighetsägare och projektorganisationer som behöver stöd inom energi, energisamordning i byggprojekt, tekniska system eller fastighetsdata.

## Budskap

- Primär rubrik: **Energi, teknik och data som fungerar tillsammans.**
- Positionering: **Energikonsult för fastigheter**.
- Energisamordning i byggprojekt ska synas som en naturlig del av erfarenheten.
- Visa sambandet: byggprojekt → fastighetsteknik → data → uppföljning.
- Beskriv kompetens, inte själva webbplatsen.

## Sidstruktur

1. Header med Beyond Norms-logotyp.
2. Hero med positionering och en kort konkret ingress.
3. Tre kompetensområden:
   - Energi
   - Bygg & fastighetsteknik
   - Data & digitalisering
4. Kort del om spannet från byggprojekt till befintlig fastighet.
5. Exempel på uppdrag.
6. Kontakt med mail, telefon och WhatsApp.
7. Enkel footer.

## Designriktning

- Behåll den befintliga visuella familjen: varm neutral bakgrund, mörk Beyond Norms-branding, mjukt rundade paneler och luft.
- Känsla: senior specialist, inte stort konsultbolag.
- Stor, tydlig typografi; korta textstycken; tydlig rytm.
- Ingen stockbild, inga generiska tjänsteikoner, inga överdrivna färgblock och ingen onödig corporate-känsla.
- Mobil ska vara lättläst och fungera utan horisontell scroll.
- Respektera `prefers-reduced-motion`.

## Copy och innehåll

- Skriv på svenska i första versionen.
- Använd **energikonsult** hellre än **energikonsulting**.
- Håll sidan kort och konkret.
- Avancerade meriter/verktyg som Brick, REB, Azure/Fabric och LoRa ska inte ligga på startsidan i denna version.
- Nämn inte Fabege eller andra kunder/referenser utan uttryckligt klartecken.
- Undvik resultatlöften, certifieringar, besparingssiffror och andra uppgifter som inte uttryckligen verifierats.
- Ingen kontaktknapp behövs; vanlig e-post-, telefon- och WhatsApp-länk räcker.

## Rutter och build

- `dist/index.html` är svensk startsida.
- `dist/sv/index.html` är svensk sida på `/sv/`.
- `dist/logo.svg` är logotypen som används av båda rutterna.
- `wrangler.jsonc` anger `./dist` som statisk asset-katalog för Cloudflare-builden.

## Kontakt

- E-post: `thomas.l.bn@outlook.com`
- Telefon/WhatsApp: `+46 73 944 13 50`

## Acceptanskriterier

- Sidan laddar från både `/` och `/sv/` i previewmiljön.
- Logotyp och kontaktlänkar fungerar.
- Ingen CTA-knapp eller kontaktformulär finns.
- Copy säger inte att sidan bara är en enkel första webbversion.
- Inga ogrundade kund-, resultat- eller certifieringspåståenden förekommer.
- PR-preview fungerar innan någon ändring mergas eller går live.

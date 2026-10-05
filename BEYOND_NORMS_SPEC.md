# Beyond Norms — första preview-specifikation

## Projekt
- Varumärke: **Beyond Norms**
- Webbplats: `beyondnorms.se`
- GitHub-repo: `tomasljonsson-png/beyondnorms-site`
- Cloudflare Workers & Pages: `beyondnorms-site`
- Projektet hålls helt separat från You, Me &.

## Syfte och målgrupp
En kort, professionell presentation av Thomas som **energikonsult för fastigheter**. Den ska tala till fastighetsägare och projektorganisationer som behöver stöd med energi, energisamordning i byggprojekt, fastighetsteknik eller fastighetsdata.

## Kärnbudskap
- Huvudrubrik: **Energi, teknik och data som fungerar tillsammans.**
- Positionering: **Energikonsult för fastigheter**.
- Synliggör energisamordning i byggprojekt som en naturlig del av profilen.
- Visa sambandet: byggprojekt → fastighetsteknik → data → uppföljning.
- Beskriv kompetensen, inte själva webbplatsen.

## Sidstruktur
1. Header med Beyond Norms-logotyp.
2. Hero med positionering och konkret ingress.
3. Tre områden: **Energi**, **Bygg & fastighetsteknik**, **Data & digitalisering**.
4. Kort sektion: **Från byggprojekt till befintlig fastighet**.
5. **Exempel på uppdrag**.
6. Kontakt med mail, telefon och WhatsApp.
7. Enkel footer.

## Design och ton
- Behåll varm neutral bakgrund, mörk Beyond Norms-branding, mjukt rundade paneler och luft.
- Känsla: senior specialist, inte stort konsultbolag.
- Stor tydlig typografi, korta stycken och lugn läsrytm.
- Inga stockbilder, generiska tjänsteikoner eller överdrivna färgblock.
- Mobil ska vara lättläst och fungera utan horisontell scroll; respektera `prefers-reduced-motion`.
- Första versionen är på svenska.

## Copy-gränser
- Använd **energikonsult** hellre än **energikonsulting**.
- Undvik generiska fraser, buzzwords, långa presentationer och ogrundade löften.
- Nämn inte Brick, REB, Azure/Fabric, LoRa, Fabege eller andra kunder/referenser på startsidan utan separat godkännande.
- Lägg inte till certifieringar, resultat eller besparingssiffror om de inte uttryckligen verifierats.
- Ingen knapp eller formulär behövs; använd enkla kontaktlänkar.

## Rutter och Cloudflare-build
- `dist/index.html` serverar sidan på `/`.
- `dist/sv/index.html` serverar samma svenska sida på `/sv/`.
- `dist/logo.svg` är logotypen.
- `wrangler.jsonc` pekar på `./dist` som statisk asset-katalog.

## Kontaktuppgifter
- E-post: `thomas.l.bn@outlook.com`
- Telefon: `+66 81 045 51 73`
- WhatsApp: `+46 73 944 13 50`

## Acceptanskriterier
- `/` och `/sv/` laddar samma svenska presentation i preview.
- Logotyp, mail-, telefon- och WhatsApp-länkar fungerar.
- Ingen CTA-knapp eller kontaktformulär finns.
- Sidan beskriver Thomas arbete, inte att det bara är en första webbversion.
- Inga ogrundade kund-, resultat- eller certifieringspåståenden förekommer.
- PR-preview verifieras innan merge; ingen merge eller live-publicering före Thomas uttryckliga **Go Live**.
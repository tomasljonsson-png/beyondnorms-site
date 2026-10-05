# Prompt för ClickUp-webbagent — Beyond Norms

Arbeta **endast** med projektet Beyond Norms.

## Projektidentitet
- Varumärke: **Beyond Norms**
- Webbplats: `beyondnorms.se`
- GitHub-repo: `tomasljonsson-png/beyondnorms-site`
- Cloudflare-projekt: `beyondnorms-site`
- Positionering: Thomas är **energikonsult för fastigheter**.

## Källa och uttryck
Utgå från `BEYOND_NORMS_SPEC.md` och befintliga filer i repot. Sidan ska tydligt visa sambandet mellan energi, energisamordning i byggprojekt, bygg- och fastighetsteknik samt data/digitalisering.

Håll uttrycket professionellt, precist och avskalat: varm neutral bakgrund, mörk Beyond Norms-logotyp, mjukt rundade ytor, gott om luft, tydlig typografi och korta texter. Använd ordet energikonsult hellre än energikonsulting.

Undvik generiska konsultbolagsfraser, långa presentationer, stockbilder, tjänsteikoner och buzzwords. Ta inte med Brick, REB, Azure/Fabric, LoRa, kundnamn, referenser, certifieringar, resultat eller besparingssiffror om Thomas inte först godkänt dem.

Första versionen är svensk. Ingen CTA-knapp och inget formulär behövs. Behåll kontaktvägarna som vanliga länkar:
- E-post: `thomas.l.bn@outlook.com`
- Telefon: `+66 81 045 51 73`
- WhatsApp: `+46 73 944 13 50`

## Säker arbetsmodell
1. Kontrollera att uppgiften uttryckligen gäller Beyond Norms och använd bara repot ovan.
2. Läs befintlig kod före ändring.
3. Arbeta på separat branch från `main`; ändra aldrig `main` direkt.
4. Gör bara efterfrågade ändringar och skapa PR mot `main`.
5. Kontrollera Cloudflare Preview-builden och dela endast en verifierad Preview-URL.
6. Vänta på Thomas uttryckliga **Go Live** innan merge/publicering.
7. Ändra inte Cloudflare-konfiguration, DNS eller domänkoppling på eget initiativ.
8. Blanda aldrig filer, copy, branches eller PR:er med You, Me &.

Nuvarande Cloudflare-build använder `npx wrangler versions upload`; `wrangler.jsonc` pekar ut `./dist` som statisk asset-katalog. Ändra inte deploykonfigurationen utan att kontrollera behovet och buildresultatet.

## Leverans
Svara kort på svenska med vad som ändrats, PR-länk, verifierad Preview-URL (eller tydligt besked att den ännu saknas) och status att invänta Thomas godkännande/Go Live.
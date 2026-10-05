# Beyond Norms — previewpaket

Första svenskspår för en enkel konsultpresentation på `beyondnorms.se`.

## Filer

- `dist/index.html` — startsida på `/`
- `dist/sv/index.html` — svensk startsida på `/sv/`
- `dist/logo.svg` — logotyp
- `wrangler.jsonc` — anger `dist/` som statisk asset-katalog
- `BEYOND_NORMS_SPEC.md` — innehålls- och designkälla
- `WEB_AGENT_PROMPT.md` — prompt/arbetsregler för ClickUp-webbagent

Rotens `index.html` och `logo.svg` är en arbetskopia för enkel lokal granskning.

## Cloudflare

Cloudflare Workers & Pages-projektet heter `beyondnorms-site`. Buildens deploy-kommando använder Wrangler och konfigurationen i `wrangler.jsonc`. PR-preview ska verifieras innan ändringar godkänns. En lyckad build-check ensam är inte bevis på att en publik preview-rutt fungerar.

## Kontakt som visas på sidan

- E-post: `thomas.l.bn@outlook.com`
- Telefon/WhatsApp: `+46 73 944 13 50`

## Säkerhet

Ändra inte DNS, domänpekning eller publicering till live utan Thomas uttryckliga godkännande. Merg:a inte till `main` före **Go Live**.
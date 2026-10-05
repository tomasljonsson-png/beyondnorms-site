# Beyond Norms — bilingual preview

A Swedish and English presentation of Thomas as an energy consultant for real estate.

## Files
- `dist/index.html` — Swedish default page at `/`
- `dist/sv/index.html` — Swedish page at `/sv/`
- `dist/en/index.html` — English page at `/en/`
- `dist/logo.svg` — shared logo
- `wrangler.jsonc` — static assets configuration pointing to `dist/`
- `BEYOND_NORMS_SPEC.md` — content and design source
- `WEB_AGENT_PROMPT.md` — ClickUp web-agent prompt and project-specific release rules

## Language navigation
Each page includes a compact `SV / EN` switch to its language counterpart. The root route remains Swedish by default.

## Cloudflare
Workers & Pages project: `beyondnorms-site`. Wrangler uses the config in `wrangler.jsonc`. Verify the PR Preview before approval. A successful build alone does not prove the public route works.

## Contact displayed
- Email: `thomas.l.bn@outlook.com`
- Phone: `+66 81 045 51 73`
- WhatsApp: `+46 73 944 13 50`

Do not change DNS or domain routing, or merge/publish live, without Thomas's explicit “Go Live”.
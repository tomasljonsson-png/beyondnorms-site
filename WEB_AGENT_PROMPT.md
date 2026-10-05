# ClickUp web-agent prompt — Beyond Norms

Work **only** on Beyond Norms.

## Project identity
- Brand: **Beyond Norms**
- Website: `beyondnorms.se`
- GitHub repo: `tomasljonsson-png/beyondnorms-site`
- Cloudflare project: `beyondnorms-site`
- Positioning: Thomas is an **energy consultant for real estate**.

## Source and expression
Use `BEYOND_NORMS_SPEC.md` and the existing repo files. Present the relationship between energy, energy coordination in construction projects, building systems and property data/digitalisation.

The site is bilingual: Swedish at `/sv/` and English at `/en/`, with a clear language switch linking equivalent pages. Keep the root route Swedish. Preserve parallel content and structure across both languages.

Use a precise, professional, restrained tone: warm neutral background, dark Beyond Norms branding, rounded surfaces, generous whitespace and short copy. Prefer “energikonsult” over “energikonsulting” in Swedish.

Do not add generic consulting copy, long biographies, stock photos, generic service icons, buzzwords, customer names, references, certifications, performance claims or savings figures unless Thomas approves them. No CTA button or form is needed; use direct contact links only.

Contact links:
- Email: `thomas.l.bn@outlook.com`
- Phone: `+66 81 045 51 73`
- WhatsApp: `+46 73 944 13 50`

## Safe workflow
1. Confirm the request is for Beyond Norms and use only the repo above.
2. Read existing code before changes.
3. Work on a separate branch from `main`; never change `main` directly.
4. Make only requested changes and open a PR to `main`.
5. Verify Cloudflare Preview and share only a verified preview URL.
6. Wait for Thomas's explicit “Go Live” before merging or publishing live.
7. Do not change Cloudflare configuration, DNS or domain routing independently.
8. Never mix assets, copy, branches or PRs with You, Me &.

Cloudflare currently uses `npx wrangler versions upload`; `wrangler.jsonc` points to `./dist` as its static asset directory. Do not change deployment configuration without first checking why it is necessary and verifying the build result.

## Delivery
Reply briefly in Swedish with changes, PR link, verified Preview URL (or clearly state it is unavailable), and that approval/Go Live is pending.
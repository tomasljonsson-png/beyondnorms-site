# Beyond Norms — first bilingual preview specification

## Project
- Brand: **Beyond Norms**
- Website: `beyondnorms.se`
- GitHub: `tomasljonsson-png/beyondnorms-site`
- Cloudflare Workers & Pages: `beyondnorms-site`
- Keep this project entirely separate from You, Me &.

## Purpose and audience
A concise, professional presentation of Thomas as an **energy consultant for real estate**. The page is for property owners and project teams needing support with energy, energy coordination in construction projects, building systems or property data.

## Core message
- Positioning: **Energy consultant for real estate**.
- Lead: **Energy, technology and data working together.**
- Show energy coordination in construction projects as a natural part of the profile.
- Explain the connection: construction projects → building systems → data → follow-up.
- Describe the work, not the website.

## Page structure
1. Header with Beyond Norms logo and language switch.
2. Hero with positioning and concise introduction.
3. Three areas: Energy; Construction & building systems; Data & digitalisation.
4. Short lifecycle section: construction projects through existing properties.
5. Example assignments.
6. Direct contact links: email, phone and WhatsApp.
7. Simple footer.

## Languages and routes
- Swedish: `/sv/`
- English: `/en/`
- Root `/` remains Swedish by default and includes the same language switch.
- Every language page links directly to its counterpart.
- Use consistent copy, structure and contact details across languages.

## Design and tone
- Warm neutral background, dark Beyond Norms brand, rounded surfaces and generous whitespace.
- Senior specialist, not a large consulting firm.
- Large clear type, short copy and calm rhythm.
- No stock imagery, generic service icons or exaggerated color blocks.
- Mobile-readable; respect `prefers-reduced-motion`.

## Copy limits
- Prefer “energikonsult” in Swedish and “energy consultant” in English.
- Avoid unverified customer references, credentials, quantified outcomes or savings.
- Do not list Brick, REB, Azure/Fabric or LoRa on the landing page unless Thomas approves.
- No CTA button or contact form; simple contact links only.

## Cloudflare asset layout
- `dist/index.html` — Swedish default.
- `dist/sv/index.html` — Swedish page.
- `dist/en/index.html` — English page.
- `dist/logo.svg` — shared logo.
- `wrangler.jsonc` points to `./dist`.

## Contact
- Email: `thomas.l.bn@outlook.com`
- Phone: `+66 81 045 51 73`
- WhatsApp: `+46 73 944 13 50`

## Acceptance criteria
- `/`, `/sv/` and `/en/` load the intended language.
- Switch links connect Swedish and English counterparts.
- Logo and email, telephone and WhatsApp links work.
- No CTA button or form.
- No unverified customer, outcome or certification claims.
- Preview is verified before merge; no live release without Thomas's explicit “Go Live”.
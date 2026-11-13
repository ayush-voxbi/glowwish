# Glowwish — built from scratch

A mobile-friendly animated digital gifting website using plain HTML, CSS and JavaScript.

## Included
- Animated landing page with floating phone mockups, clouds, flowers and scroll reveals
- Occasion cards and greeting templates
- Personalised live preview with four themes
- Interactive gift box opening, sparkle burst and short synthesized chime
- Download greeting card as PNG
- Shareable gift URL (gift details encoded in URL hash; no database needed)

## Deploy with GitHub + Vercel
1. Create a GitHub repository named `glowwish`.
2. Upload `index.html` to the repository root and commit to `main`.
3. In Vercel, choose Add New → Project and import the GitHub repository.
4. Framework preset: Other. No build command is required; use `.` as the output directory if prompted.
5. Deploy.

To keep a previous Vercel URL, the old Vercel project/domain must still exist or the same domain must be available to assign. If the old Vercel project was deleted, create this project first, then check Vercel Project → Settings → Domains to add the old domain if it is available.

This is a static front-end starter. Gift content is encoded into each share URL. User accounts, database-backed storage, admin dashboard and server-side analytics are not included.

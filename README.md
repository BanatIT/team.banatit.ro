# team.banatit.ro

Landing page for the Banat IT Operational Team recruitment, July 2026.

## Files

- `index.html` — main landing page, self-contained
- `apply-form-spec.html` — visual reference for the Google Form (not functional, spec only)

## Deploy

Any static host works. Recommended:

- **Cloudflare Pages** — connect this repo, set build command to none, publish directory `/`
- **Netlify** — same idea
- **GitHub Pages** — enable in repo settings, source `main` branch, root

Once deployed, point `team.banatit.ro` DNS (CNAME) to the host.

## Application form

The Apply CTAs point to `https://bit.ly/BanatITOperationalTeam` (short link to a Google Form managed by Alecu Braescu).

If the Google Form gets updated to a new URL, update the short link target, not the HTML.

## Design system

Aligned with `banat.it`:

- Background `#18122D` (dark navy)
- Accent `#00FF00` (neon green)
- Text `#F8FAFF` (light neutral)
- Muted `#9893A9` (gray)
- Danger `#FF2E00` (red-orange, minimal use)
- Typography: Inter + JetBrains Mono (Google Fonts)

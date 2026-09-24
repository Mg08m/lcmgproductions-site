# lcmgproductions.com

Studio site for LCMG Productions. Last Chance is the game brand.

## Is the branding enough?

Yes, for a studio landing page.

Already locked and used here:
- Chassis colours: ground `#191617`, panel `#241F21`, ink, dim
- Rugby accent `#C8102E` + tagline **THE REF CAN'T SEE EVERYTHING.**
- Hurling accent `#F7A800` + tagline **WIN IT AT THE LAST PUCK.**
- Anton wordmark
- Both crests

Fonts are self-hosted in `fonts/` (Anton and Inter, both SIL Open Font License 1.1, latin subsets
from Google Fonts) so the page makes no third-party request.

`og:image` and `canonical` point at `lcmgproductions.com` (live on GitHub Pages via Cloudflare DNS since 2026-09-24).

Site extras in `assets/`:
- `favicon.ico` — 32 / 64 / 128 charcoal crests
- `og-1200x630.jpg` — lock-up crop for Reddit, X, WhatsApp
- Page stays dark. No light lock-up. No bee, no spoons. v3 is the mark.

Not needed for this page: Steam capsules, key art, or a drawn LCMG logo. A studio wordmark is enough until a monogram is commissioned.

What this page does **not** do:
- Promise Steam URLs that are not live
- Put the social tagline on a fake capsule
- Invent press quotes, dates, or wishlist numbers

## Deploy

Static files. Point `lcmgproductions.com` at any static host.

Cloudflare Pages / Netlify / GitHub Pages:
1. Upload this folder (or push the repo).
2. Set the domain to `lcmgproductions.com`.
3. Create the mailbox `hello@lcmgproductions.com` or change the mailto.

Live: four A records to GitHub Pages + `www` CNAME to `mg08m.github.io`, all DNS-only in Cloudflare; Pages custom domain set.

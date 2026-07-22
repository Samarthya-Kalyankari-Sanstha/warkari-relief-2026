# warkari-relief-2026
Emergency shelter and hygiene relief for 300 Warkari pilgrim families stranded by the July 2026 Pune floods during the 21-day Ashadhi Wari to Pandharpur. A route-intercept distribution model that walked alongside the Sant Dnyaneshwar and Sant Tukaram Palkhis. By Samarthya Kalyankari Sanstha, with Amazon through DonateKart Foundation.

## Photo Gallery (`index.html`)

104 field photographs across 8 categories, organized into three narrative groups:

- **Group A — Emergency, Logistics & Route**: When the Rains Came, Transportation & Team Carrying Kits, Samarthya Team Demo of Kits (44 photos)
- **Group B — Verification & Accountability**: Dindi Schedule Scans, Beneficiaries with Kits (18 photos)
- **Group C — Human Impact & Credits**: What a Kit Became, Human Smiles, Team & Credits (42 photos)

**What's deliberately excluded from this public gallery:**
- The "Beneficiaries with Tokens" category — the physical token card carries Amazon/DonateKart branding by design, kept in the private donor reporting channel instead.
- The "Registration Documentation Accountability" category — contains real beneficiary names, villages, and signatures.
- Any individual photo elsewhere with visible donor banner branding in frame.

This split follows Samarthya's two-stream photo policy: donor-branded and beneficiary-PII material stays in private donor reporting; only the public-safe subset is published here. See `manifest.json` for the exact photo inventory per category.

### Running locally
This page fetches `manifest.json`, so it needs to be served over HTTP (not opened directly as a `file://` URL):
```
python3 -m http.server 8000
```
Then visit `http://localhost:8000`. On GitHub Pages this works automatically.

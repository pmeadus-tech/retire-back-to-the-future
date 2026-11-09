# Retire Back to the Future Calculator

**Reverse Engineer Your Retirement**  
from The Crude Dude (Perry Meadus, Alberta sole proprietor)

Static web app. Snap pay stubs and bills on your phone — **photos stay on the device, never uploaded** — and reverse-engineer a retirement / TFSA plan so you never miss your targets.

## Live intent
Host on **GitHub Pages** from a public repo named `retire-back-to-the-future` (not pushed yet — wait until GitHub is connected).  
Placeholder URL in drafts: `{{CALC_URL}}`.

## Contents
| File | Purpose |
|---|---|
| `index.html` | Calculator (countdown, hitch/TFSA math, debt, crew, feedback) |
| `privacy.html` | Privacy Policy (web + phone app) |
| `terms.html` | Terms of Use |
| `delete-account.html` | Account deletion instructions (Play / App Store) |
| `manifest.webmanifest` | Installable web app |
| `icons/`, `favicon.ico`, `og/og-share.jpg` | Branding (pill-eyes, no-mouth mascot) |
| `vendor/` | Local tesseract.js + pdf.js |

## Privacy (web)
Everything stays on this device (`localStorage` + IndexedDB). No ads, no analytics. Feedback boxes save locally only.

## Legal contact
hello@crudedude.ca · Effective date on legal pages: November 9, 2026

## Local preview
```bash
python3 -m http.server 8765
# open http://127.0.0.1:8765/
```

## GitHub Pages (when connected)
1. Create empty GitHub repo `retire-back-to-the-future`.
2. From this folder:
   ```bash
   git remote add origin git@github.com:<USER>/retire-back-to-the-future.git
   git push -u origin main
   ```
3. Settings → Pages → Deploy from branch `main` / root (or `/docs` if you prefer).
4. Fill `{{CALC_URL}}` in newsletter / blog / video plan drafts, then ask Perry before publishing.

**Do not push until Perry connects GitHub and says to.**

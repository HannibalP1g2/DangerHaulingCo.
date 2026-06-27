# Danger Hauling Co.

Marketing site for Danger Hauling Co. — junk removal, debris hauling, and cleanouts.

A single self-contained `index.html` (HTML + CSS, no build step, no dependencies).

## View it locally

Open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

Repo **Settings → Pages → Build and deployment → Deploy from a branch → `main` / root**.
The site goes live at `https://hannibalp1g2.github.io/DangerHaulingCo./`.

## Before going live — swap the placeholders

The following are sample values in `index.html`:

- **Phone:** `(555) 555-0199` (appears in hero, quote section, footer, and `tel:` links)
- **Email:** `dispatch@dangerhauling.co` (quote section, footer, and the form's `mailto:` action)
- **Service area:** "Greater Metro Area"
- **Hours:** Mon–Sat 7am–7pm
- **Stats:** loads hauled, rating, etc. in the hero

The quote form uses a `mailto:` action so it works with no backend. For a real
submission flow, point it at a form service (Formspree, Basin) or your own endpoint.

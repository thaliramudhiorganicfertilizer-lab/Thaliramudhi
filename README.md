# Thalir Amudhi — organic fertilizer website

A responsive, bilingual static website for Thalir Amudhi. Supplied posters were used as source material for readable product details; the website uses a custom generated farm hero visual rather than embedding text-heavy posters.

## Files
- `index.html` — website content
- `style.css` — responsive styling and pastel product cards
- `script.js` — English/Tamil switcher, mobile navigation, WhatsApp enquiry form
- `assets/organic-farm-hero.png` — custom generated hero image
- `assets/origin-farm-story.png` — custom generated farm story image
- `assets/thalir-amudhi-logo.png` — supplied brand logo
- `assets/faa-ingredients-garden.png` — custom generated ingredient visual
- `assets/product-fish-amino.png`, `assets/product-neem.png`, `assets/product-groundnut.png`, `assets/product-erukku.png` — coordinated illustrative product photography used in each product card

## Preview locally
Open `index.html` in a browser. Google Fonts need an internet connection; the remaining assets are local.

## Publish with GitHub Pages
1. Create a repository and upload the files and `assets` folder so `index.html` is at the repository root.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
4. After the Pages workflow succeeds, open the site URL shown in Settings.

## Notes
- Prices and ingredients were transcribed from the supplied posters. Confirm current prices, availability and label instructions before ordering.
- The enquiry form opens WhatsApp with a draft for the visitor to review and send. It does not save details to a server.
- The WhatsApp recipient comes from the supplied website code. Static sites expose the recipient number in the link destination.
- This is an informational portfolio, not an online store or checkout.

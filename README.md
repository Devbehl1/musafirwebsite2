# Musafir Gateaways — frontend website

Responsive static website matching the bright blue, white and orange travel-brand visual direction.

## Files
- `index.html` — page structure and package detail dialog
- `styles.css` — responsive layout and visual styling
- `script.js` — package filters, package detail popups, trip enquiry to WhatsApp
- `assets/musafir-gateaways-logo.png` — supplied logo

## Publish on GitHub Pages
1. Extract this ZIP.
2. Create a GitHub repository and upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Add your domain under **Custom domain** and configure the DNS records at your domain provider as GitHub instructs.

## Notes
Frontend only: no server, database, booking engine, payment gateway or admin panel. The trip search opens WhatsApp with the visitor's selections. Package cards open detail popups and enquiry links. Sample packages are inspiration only; quote, itinerary and availability must be confirmed directly. Destination photos and Google Fonts load from external services, so internet access is needed.

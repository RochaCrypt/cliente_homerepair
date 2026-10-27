# Home Repair website

Static, responsive website prepared for Vercel.

## Deploy to Vercel

1. Extract this ZIP file.
2. Log in to Vercel and select **Add New > Project**.
3. Import the folder from GitHub, or use the Vercel CLI from this folder.
4. Framework preset: **Other**.
5. Build command: leave empty.
6. Output directory: leave empty (project root).
7. Deploy.

## Local preview

Open `index.html` directly or run a local static server:

```bash
npx serve .
```

## Configuration

- WhatsApp: `353852274149` in `script.js`
- Email: `homerepairsolution2@gmail.com` in `index.html`
- Languages: English is default. Portuguese is available in the header.
- Theme: light/dark toggle, with the visitor's preference saved locally.
- Form: data is not stored; it creates a prefilled WhatsApp message.
- Hero photography uses hosted Unsplash images and therefore requires internet access.

## Recommended before production

- Add your final domain in Vercel.
- Replace remote photos with licensed local files in `/assets` if you want the site to work fully offline.
- Review the service wording and ensure all regulated electrical or plumbing work is performed by appropriately qualified professionals.

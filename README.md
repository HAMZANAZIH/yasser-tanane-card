# Yasser TANANE — Digital Business Card

A responsive, static digital business card for GitHub Pages. No build tools, login, or paid service required.

## What's included

- `index.html` — the website with mobile-friendly layout
- `assets/background.jpg` — first supplied photo (background)
- `assets/profile.jpg` — second supplied photo (profile)
- `assets/favicon.png` — browser icon
- `yasser-tanane.vcf` — contact download (name, company, job title, phone, Instagram, WhatsApp, profile photo)

## Publish to GitHub Pages

1. Create a **public** repository, for example `yasser-tanane-card`.
2. Upload **all files and the `assets` folder**, with `index.html` at the repository root. Do not upload only the ZIP.
3. Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch**, `main` and `/(root)`, then **Save**.
4. Your site URL will be `https://YOUR-USERNAME.github.io/yasser-tanane-card/` (replace YOUR-USERNAME). It may take a few minutes to become live.

## Change details

Edit the name, title, and action links in `index.html`; replace images in `assets/` with the same filenames.
If you change phone, name, or other details, also regenerate the `yasser-tanane.vcf` file so the Save Contact download is up to date.

## Notes

- WhatsApp link: `https://wa.me/212612636839`.
- Phone link: `tel:+212612636839`.
- Instagram: `https://www.instagram.com/palermo2005tn/`.
- Saving a contact requires confirmation by the visitor's phone. vCard photo handling may vary by iPhone/Android software and browser.
- For a personal NFC tag or QR code, encode the public GitHub Pages URL after publishing.

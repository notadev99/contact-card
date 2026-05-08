# Contact card

QR landing page with a one-tap Save Contact. Pure static — `index.html`, a `.vcf`, some images. That's the whole project.

Open `index.html` in a browser to view it. Push to any static host (GitHub Pages, Netlify, Vercel, S3) — they all serve `.vcf` with the right MIME so iOS triggers the Add-to-Contacts sheet.

## Forking it

Open `index.html` and follow the checklist at the top of the file. The bits to change are marked `EDIT >` so you can grep for them:

- `EDIT > META` — page title, description, Open Graph tags
- `EDIT > COLOURS` — light + dark mode CSS variables
- `EDIT > PROFILE` — photo, name, role, tagline
- `EDIT > LINKS` — contact links (wrap two in `<div class="row">` to pair them side-by-side)
- `EDIT > SAVE CONTACT` — the vCard href (rename `thomas.vcf` to match)
- `EDIT > FOOTER` — footer text and logo

Drop your photo files into `images/` and your own `.vcf` at the root. That's it.

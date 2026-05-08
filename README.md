# Contact card

QR landing page with a one-tap Save Contact. Pure static — `index.html`, a `.vcf`, some images. That's the whole project.

Open `index.html` in a browser to view it. Push to any static host (GitHub Pages, Netlify, Vercel, S3) — they all serve `.vcf` with the right MIME so iOS triggers the Add-to-Contacts sheet.

To use it for someone else: edit `index.html` and `thomas.vcf`, swap the photos in `images/`, and rename the `.vcf` to match.

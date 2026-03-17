# Digital Business Profile Page (Dheeraj Panchal)

Simple static page you can host anywhere (GitHub Pages, Netlify, your own domain) or open locally.

## Files
- `index.html` : the page
- `Style.css` : styling
- `profile.jpg` : profile photo (replace with the real photo, keep the same filename)
- `contact.vcf` : vCard for “Save Contact”

## Edit content
Update the text and links directly in `index.html`:
- Phone (Call + WhatsApp): `tel:+919351600811` and `https://wa.me/919351600811`
- Email: `mailto:pdhiraj015@gmail.com`
- Website: `https://www.archigroup.in/`
- Location (Google Maps search link)
- LinkedIn URL
- Instagram URLs (personal + corporate)
- ARCHI project sections: project links + photo URLs are embedded directly from `archigroup.in` to keep the repo lightweight
- ARCHI + Aishwarya logos are embedded as `data:` images (rendered from your provided PDF logos)

Update `contact.vcf` if any phone/email/address changes.

## Preview locally
Option 1: Open `index.html` directly in a browser.

Option 2: Run a local server:
```bash
python3 -m http.server 5173
```
Then open `http://localhost:5173`.

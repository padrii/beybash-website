# Beybash Mining and Construction — Website

Static website for Beybash Mining and Construction (Tanzania).

## Preview locally

- Option 1: Open `index.html` directly in your browser.
- Option 2: Serve locally (recommended for routing and assets):

```bash
# Python 3
python -m http.server 5173
# Then visit http://localhost:5173
```

> ℹ️ The contact form uses FormSubmit and requires the site to be served over HTTP/HTTPS. When testing locally, make sure you use option 2 (or any other local server) so submissions reach `wilsonpadri@gmail.com`.

## Structure

- `index.html` — Landing page with highlights and gallery
- `about.html` — Company profile and differentiators
- `services.html` — Detailed service catalogue
- `projects.html` — Featured project summaries
- `contact.html` — Contact details and enquiry form
- `thanks.html` — Confirmation page after successful form submission
- `styles.css` — Styles with responsive layout and branding colors
- `assets/` — Image assets (`logo.svg`, `excavator1.jpg`, `gari1.jpg`, `loading.jpg`, `koko.jpg`)

## Customize

- Replace contact info (phone, email, address) across pages
- Update copy blocks and add real project imagery
- Swap `assets/logo.svg` with your official logo

## Deploy

This is a static site; you can host it on any static hosting service:

- GitHub Pages, Netlify, Vercel, Cloudflare Pages, or your own server



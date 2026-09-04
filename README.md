# Manthana

Professional static website for Manthana — discovering the nectar within you.

Source copy: company overview PPT, consulting-portfolio notes, founder profile at [linkedin.com/in/balajisubbaram](https://www.linkedin.com/in/balajisubbaram/), and the Manthana logo.

## Pages

- `index.html` — Home
- `about.html` — Practice and founder
- `services.html` — Full consulting portfolio
- `workshops.html` — Facilitated sessions
- `contact.html` — Enquiry (opens a mail draft)
- `privacy.html` — Privacy note

## Run locally

```text
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Hosting

Upload this folder to GitHub and connect it to Cloudflare Pages. Leave the build command empty; output directory is the repository root. Add a custom domain later when you have one.

## Before launch

- Confirm the phone number on the site.
- Add a founder photograph on About if desired.
- Replace the contact form with Formspree or similar if mailto is unreliable for visitors.

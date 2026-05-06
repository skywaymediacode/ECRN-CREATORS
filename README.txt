ECRN Creator Recruitment Landing Page
=====================================

WHAT IS IN THIS FOLDER
- index.html  -> the page (open it directly to preview)
- app.js      -> pre-compiled React bundle (loaded by index.html)
- README.txt  -> this file

HOSTING (it is just static files)
Easiest free options:
  Cloudflare Pages    https://pages.cloudflare.com   (drag and drop the folder)
  Netlify Drop        https://app.netlify.com/drop   (drag and drop the folder)
  Vercel              https://vercel.com             (drag and drop or CLI)
  GitHub Pages        push the folder to a repo, enable Pages

Traditional cPanel / GoDaddy / Bluehost:
  Upload index.html and app.js into public_html (or whatever the web root is).
  Keep them in the same folder.

Pointing a custom domain:
  All the hosts above let you connect your own domain in their dashboard.

DEPENDENCIES (no install required, loaded from CDN)
- React 18              unpkg.com
- Tailwind CSS Play     cdn.tailwindcss.com

WIRE UP THE FORM BEFORE LAUNCH
The <form> in the Apply section does not submit anywhere yet. Connect it to:
  - GoHighLevel (GHL) form webhook
  - Formspree    https://formspree.io
  - Zapier / Make webhook
  - Your CRM API
The Submit button is type="button" right now so it does not POST. Change it to
type="submit" and add an action / onSubmit handler when you wire it up.

EDITS / DESIGN CHANGES
Ask Claude to update the page and re-export, or edit app.js directly if you
are comfortable with React + Tailwind.

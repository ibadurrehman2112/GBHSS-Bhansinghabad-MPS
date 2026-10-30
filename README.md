# Govt. Boys Higher Secondary School Mirpurkhas — Website (Part 1: static frontend) — SEMIS 405030386

Classes 6–12. Plain HTML/CSS/JS; works on GitHub Pages with no PHP.

## Images
Put these in `images/`: `logo.png`, `image1.jpg`, `image2.jpg`, `image3.jpg` (optional `principal.jpg`). Different names/extensions: edit `index.html` (Gallery + Stream Activities sections, header/footer logo).

## Deploy on GitHub Pages
Push to a repo → Settings → Pages → deploy from branch root. `index.html` is the entry point.
PHP does not run on GitHub Pages: the forms show an honest "unavailable" message there. Alternatives: PHP hosting, or a form service (Formspree, etc.).

## Edit content
- Notices/events: `js/notices-data.js` (sample data — remove before launch)
- Principal message: block marked in `index.html`; captions: Gallery/Stream sections
- Stats, contact details, map, testimonials: bracketed placeholders in `index.html`

## Coming in Part 2
PHP backend: `index.php`, `includes/`, `handlers/admission.php`, `handlers/contact.php`, `database.sql`, `notices.php`, `.htaccess`, XAMPP guide. Not yet tested on a server.

# NorthPeak Digital — website starter

A complete responsive **single-page** agency website with five navigation sections (Home, Services, Our Work, About, Contact). It is not five separate HTML pages.

## Preview (no coding required)
1. Unzip the folder.
2. Double-click `index.html` to open it in Chrome or Safari.
3. For a more realistic preview, open the folder in VS Code and use the Live Server extension, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.
4. Resize your browser window to check mobile layouts.

## Edit
- Open `index.html` in VS Code. Find the text you want to replace, change it, save, refresh your browser.
- Change colors near the top of `styles.css` (look for `--accent`, `--bg`).
- Replace fictional portfolio concepts with clearly labeled real work when available.
- Verify brand name and domain availability before using NorthPeak Digital commercially.

## Contact form — IMPORTANT
The contact form is a **demo**. It validates fields in the browser but does **not** store or deliver leads by default. Do not publish it as a live lead collection system yet. Connect a form provider such as Formspree or Netlify Forms (following its current setup guide), verify delivery and spam protection, and add a privacy notice before launch. A mailto fallback is included in `script.js` but requires replacing `YOUR_EMAIL@example.com` and depends on visitors having an email application configured.

## Publish with GitHub Pages (static website)
1. Create a GitHub account and a new public repository (e.g. `northpeak-digital`).
2. Upload `index.html`, `styles.css`, and `script.js` at the repository root.
3. Open repository Settings → Pages → Build and deployment → Deploy from a branch → `main` and `/ (root)` → Save.
4. Wait for the published URL shown on the Pages screen and test it.
5. Add a custom domain later through Pages settings and your domain registrar's DNS settings. Check GitHub's current docs for exact steps.

## Before selling or publishing
- Replace all placeholder branding and content.
- Add real contact details, privacy information, and a functional tested contact form.
- Verify accessibility, mobile performance, link behavior, SEO, and business-specific claims.
- Do not present concept portfolio pieces as real customer work.
- Get approval before using a client's photos, logos, or testimonials.

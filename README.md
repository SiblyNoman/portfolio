# Minimal Engineering Portfolio — Template

This is a minimal, modern portfolio template tailored for engineering and technology professionals. It is intentionally lightweight, semantic, and optimized for clarity.

Included files:
- index.html — Single-page layout (Home / About / Projects / Skills / Experience / Contact).
- css/styles.css — Styling with CSS variables, grid layout, responsive rules.
- js/script.js — Small JS for nav toggle, scroll reveal, active section highlighting.
- assets/photo.jpg — Replace with your professional photo.
- assets/cv.pdf — Place your CV here (same filename) so "Download CV" works.

How to customize:
1. Replace NAME, BIO, project entries, timeline entries, and links with your own content.
2. Put your portrait as `assets/photo.jpg` and CV as `assets/cv.pdf`.
3. Update social links (GitHub, LinkedIn, email).

Contact form:
- The form posts to Formspree by default (`action="https://formspree.io/f/your-id"`). Create a free Formspree form and replace `your-id`, or replace the form action with your preferred backend endpoint. Alternatively, use `mailto:` or a serverless function to handle submissions.

Accessibility & SEO:
- The template uses semantic HTML, proper headings, ARIA attributes for nav, and a skip link.
- Meta description and Open Graph tags are included in `index.html`. Update them to reflect your profile.

Deployment:
- GitHub Pages: push to a repo and enable Pages (use `main` or `gh-pages` branch).
- Netlify / Vercel: drag & drop or connect the repo for continuous deployment.
- Ensure `assets/cv.pdf` is present if you want the CV download to work.

Performance improvements (optional):
- Optimize `assets/photo.jpg` (compress and provide WebP alternatives).
- Add critical CSS inline for first paint.
- Serve fonts locally or use preconnect/preload optimizations.

License:
- Use and adapt freely. No dependencies required.

If you want, I can:
- Convert this into a multi-page site with separate pages for Projects and Publications.
- Generate optimized images, sample project markdown files, or a small build setup (Parcel / Vite) for modular development.
- Produce ready-to-deploy GitHub Pages instructions or a GitHub repository with these files.

# Khan — Personal Portfolio

Plain HTML/CSS/JS portfolio. No build tools, no npm, no frameworks —
just open `index.html` in a browser or host it directly on GitHub Pages.

## Files
- `index.html` — main portfolio page (navbar, hero, about, skills, education, experience, projects, contact, footer)
- `project-cvd.html`, `project-jute.html`, `project-maternal.html` — project detail pages
- `style.css` — all styling (dark theme)
- `script.js` — mobile navbar toggle only
- `assets/` — placeholder images + resume folder

## Things to personalize before publishing
1. **Photo:** replace `assets/profile-placeholder.svg` with your real photo
   (e.g. `assets/profile.jpg`) and update the `src` in `index.html`.
2. **Resume:** add your real resume file as `assets/resume.pdf` — the
   Download Resume button already points to it.
3. **Social links:** replace the `#`/placeholder URLs in the navbar-less
   hero section and footer with your real GitHub/LinkedIn/Twitter/Facebook.
4. **Contact info:** update email, phone, and WhatsApp number in the
   Contact section of `index.html`.
5. **Project links:** in each `project-*.html` file, replace the
   "Live Project / Demo" and "GitHub Repository" button links (`#`) with
   your real links.

## How to publish with GitHub Pages
1. Create a new GitHub repository (e.g. `my-portfolio`).
2. Upload all these files to the repository (keep the folder structure,
   especially the `assets/` folder).
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your live link will appear at:
   `https://<your-username>.github.io/<repo-name>/`

That's it — no installation, no dependencies, just upload and it runs.

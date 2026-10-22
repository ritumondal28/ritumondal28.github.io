# ritumondal28.github.io

Personal academic website for **Ritu Mondal** — Electrical & Electronic Engineer, Research Assistant, and Adjunct Lecturer.

Built as a static site for GitHub Pages: plain HTML + CSS, no build step, light/dark theme with system detection.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The full single-page site (hero, about, publications, experience, education, projects, skills, contact). |
| `style.css` | All styling and the light/dark theme tokens. |

## Deploy to GitHub Pages

Because the repo is named `ritumondal28.github.io`, GitHub Pages serves it automatically at **https://ritumondal28.github.io** — no extra config needed.

1. Create (or open) the repo `ritumondal28.github.io` on GitHub under your account.
2. Push these files to the **main** branch:

   ```bash
   git init
   git add index.html style.css README.md
   git commit -m "Add personal website"
   git branch -M main
   git remote add origin https://github.com/ritumondal28/ritumondal28.github.io.git
   git push -u origin main
   ```

3. In the repo, go to **Settings → Pages** and confirm the source is **Deploy from a branch → main / (root)**.
4. Wait ~1 minute, then visit **https://ritumondal28.github.io**.

## Customize

- **Edit text/links:** everything lives in `index.html`.
- **Colors/fonts:** change the CSS variables under `:root` (and `:root[data-theme="dark"]`) at the top of `style.css`.
- **Add a photo:** drop an image in the repo and replace the `<div class="avatar">RM</div>` block in `index.html` with `<img src="photo.jpg" alt="Ritu Mondal" class="avatar" />`.
- **Add your CV:** place `Ritu_CV.pdf` in the repo and add a link, e.g. in the hero actions: `<a class="btn btn-ghost" href="Ritu_CV.pdf" target="_blank">Download CV</a>`.

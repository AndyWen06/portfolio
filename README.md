# Engineering Portfolio

A static portfolio site (plain HTML + CSS, no build step) that you can host for free on GitHub Pages.

## Files

| File | Purpose |
|---|---|
| `index.html` | Home page: intro, project cards, about, skills, contact |
| `project.html` | Template for a single project write-up (duplicate per project) |
| `style.css` | All styling. Colors/fonts are variables at the top |
| `images/` | Create this folder for your project photos and renders |
| `resume.pdf` | Optional: add your résumé so the button works |

## Deploy on GitHub Pages (free, no domain needed)

Your site will live at `https://YOUR-USERNAME.github.io`.

1. Sign in at github.com and click **New repository**.
2. Name it **exactly** `YOUR-USERNAME.github.io` (replace with your real username, all lowercase). Set it to **Public**.
3. On the repo page, click **Add file → Upload files**, drag in everything from this folder (`index.html`, `project.html`, `style.css`, and any images), then click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then **Save**.
5. Wait 1 to 2 minutes, then visit `https://YOUR-USERNAME.github.io`.

### Updating later
Edit files directly on GitHub (pencil icon) or upload new versions. The site rebuilds automatically after each commit.

### Alternative: a project-style URL
If you'd rather name the repo something like `portfolio`, the site will be at `https://YOUR-USERNAME.github.io/portfolio/`. This works fine since all links here are relative.

## Customizing

1. **Text:** search for `Your Name`, `you@example.com`, and `your-username` and replace them.
2. **Projects:** in `index.html`, copy one `<a class="card">` block per project. For each project, copy `project.html` to a new name (e.g. `robot-arm.html`) and point the card's `href` at it.
3. **Images:** put files in an `images/` folder. Replace each placeholder like
   `<div class="thumb placeholder">…</div>` with `<div class="thumb"><img src="images/robot-arm.jpg" alt="Robot arm CAD render"></div>`.
   Keep photos under ~500 KB (resize or export as JPG/WebP) so the page loads fast.
4. **Colors:** edit the variables in the `:root` block at the top of `style.css`. The accent color is `--accent`. Dark mode follows the visitor's system setting automatically.

## Preview locally
Just double-click `index.html` to open it in your browser. No server needed.

## Tips for a strong engineering portfolio
- Lead with 3 to 5 of your best projects rather than everything.
- For each one, show the **problem → your design reasoning → analysis/test data → result**.
- Include real numbers (mass saved, cost reduced, accuracy achieved).
- Link CAD files, code, or a short video where you can.

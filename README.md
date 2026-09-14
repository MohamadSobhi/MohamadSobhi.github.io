# Mohamad Sobhi

A minimal personal homepage for Mohamad Sobhi, PhD Researcher at Arts et Métiers.

**Homepage:** https://mohamadsobhi.github.io/

## Files

- `index.html` — homepage content and project cards.
- `style.css` — responsive styling using system fonts.
- `README.md` — editing and publishing instructions.

No JavaScript, framework, external fonts, analytics, tracking, or build step.

## Add a project

Copy this block inside `<div class="projects">` in `index.html`, then replace its link, title, and description:

```html
<a class="project-card" href="https://example.com/your-project/">
  <h3>Your project title</h3>
  <p>A short description of your project.</p>
</a>
```

## Preview locally

Open `index.html` directly in a browser, or run:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Publish updates

GitHub Pages publishes from **main → /(root)** in repository Settings → Pages.

Edit the files through GitHub and commit to `main`, or use Git:

```sh
git add index.html style.css README.md
git commit -m "Update homepage"
git push origin main
```

GitHub Pages redeploys automatically. This account homepage links to the existing CSID presentation without modifying its repository.

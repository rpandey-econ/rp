# Personal website

A simple static academic homepage (Home, CV, Research, Teaching) for GitHub Pages.

## Put it online (about 5 minutes)

1. Create a GitHub account if you don't have one.
2. Create a new **public** repository named exactly `your-username.github.io`
   (replace `your-username` with your GitHub username).
3. Click **Add file → Upload files** and drag in everything from this folder:
   `index.html`, `research.html`, `teaching.html`, `cv.html`, `contact.html`, `style.css`, plus your
   `photo.jpg` and `cv.pdf`. Commit.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
5. After a minute or two your site is live at `https://your-username.github.io`.

## Customise

- Replace every "Your Name", email, and link in the five HTML files.
- The CV page shows a short summary and links to `cv.pdf` for the full version.
- Add `photo.jpg` (square works best) and `cv.pdf` to the same folder.
- Put paper PDFs in a `papers/` folder and link them from `research.html`.
- Colours live at the top of `style.css` (`--accent` is the link colour).

## Custom domain (optional)

If you own a domain (like `yourname.com`), add it under **Settings → Pages →
Custom domain**, then point your domain's DNS to GitHub Pages as GitHub
instructs. GitHub will create a `CNAME` file for you.

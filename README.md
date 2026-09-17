# My Portfolio

Built on the same open-source template structure as AshishA26's GitHub Pages site
(the "iPortfolio" Bootstrap template). Sections: Home / About / Experience / Projects.

## What to edit

Everything you need to change lives in **`index.html`** — search for `TODO` comments
inside it. In short:

1. **Header (sidebar)** — your name, headshot (`assets/img/profile-placeholder.png`),
   GitHub/LinkedIn links.
2. **Hero section** — your name + the typed "roles" text + resume link.
3. **About section** — your bio paragraphs, two photos, and the 3 "focus area" cards.
4. **Experience section** — one block per job/internship (duplicate the `timeline-row`
   div for each).
5. **Projects section** — one block per project (duplicate a `portfolio-item` div for
   each). Filter buttons at the top are controlled by the `filter-*` classes on each item
   — rename/add categories to match what you actually work on.

## Adding photos

- Drop image files into `assets/img/` (for profile/about photos) or
  `assets/img/projectPics/` (for project images), then update the `src="..."` paths in
  `index.html` to match your filenames.
- Click-to-enlarge works automatically via the `portfolio-lightbox` class — no JS
  changes needed.

## Adding videos

You don't need to embed a video player. Just point a project's lightbox link at a
video URL and it plays inline when clicked:

```html
<div class="portfolio-links">
  <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" data-gallery="portfolioGallery"
    class="portfolio-lightbox"><i class="bx bx-image"></i></a>
  ...
</div>
```

This works with YouTube/Vimeo links, or a local `.mp4` file placed in
`assets/img/projectPics/`. The thumbnail `<img>` above it is still a normal static
image — just a nice-looking frame from the video works well.

## Running it locally

No build step needed, it's plain HTML/CSS/JS. Just open `index.html` in a browser,
or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publishing on GitHub Pages

1. Create a new GitHub repo named exactly `YOUR_USERNAME.github.io`.
2. Push everything in this folder to the `main` (or `master`) branch.
3. In the repo's **Settings → Pages**, set the source branch to `main`/root.
4. Your site will be live at `https://YOUR_USERNAME.github.io` within a minute or two.

```bash
cd myportfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

## Credits

Template structure based on the free "iPortfolio" Bootstrap template
(vendor libraries: Bootstrap, AOS, GLightbox, Isotope, Swiper, Typed.js, Boxicons —
all included in `assets/vendor/`, unmodified, under their original open-source licenses).

# Dina Magdy — Portfolio Website

A responsive, dark editorial portfolio starter for GitHub Pages.

## Files
- `index.html` — page content and project cards
- `style.css` — colors, typography, layout and responsive styling
- `script.js` — project filters and mobile menu
- `assets/` — add your own images and media here

## Publish on GitHub Pages
1. Create a **public** repository named exactly `dinamagdy.github.io` under the GitHub account `dinamagdy`.
2. Upload all files and folders in this package to the repository root (not the ZIP file itself).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then Save.
6. Wait a few minutes and visit `https://dinamagdy.github.io`.

## Personalize before sharing
Search in `index.html` and replace:
- `hello@dinamagdy.com` with your real professional email.
- The Behance, Vimeo, LinkedIn and Instagram URLs with your actual profiles.
- Starter project names, descriptions, dates and decorative artwork with your real projects.
- The showreel placeholder with a Vimeo embed.

### Add a Vimeo showreel
In Vimeo, open your video → Share → Embed, copy the iframe code. In `index.html`, find `YOUR SHOWREEL GOES HERE` and replace the entire `<div class="reel-placeholder">...</div>` block with your iframe, for example:

```html
<div class="reel-placeholder">
  <iframe
    src="https://player.vimeo.com/video/YOUR_VIDEO_ID"
    title="Dina Magdy showreel"
    frameborder="0"
    allow="autoplay; fullscreen; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>
```

Add this to the bottom of `style.css` to make the player fill the area:

```css
.reel-placeholder iframe {
  width: 100%;
  height: 100%;
  border: 0;
}
```

### Replace a starter project visual with an image
1. Upload an image to `assets/images/`, for example `brand-project-cover.jpg`.
2. In the relevant project card, replace the decorative content inside its `<a class="project-visual ...">` with:

```html
<img src="assets/images/brand-project-cover.jpg" alt="Brand identity project">
```

3. Add this CSS:

```css
.project-visual img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
```

Keep images optimized for web (WebP or JPG, ideally around 1600px wide and a few hundred KB). Do not upload private client source files or large editable project files.

## Important
This starter uses fictional placeholder project concepts and a placeholder email. Replace these before sending the website to recruiters or clients.

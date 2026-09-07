# Engineering Portfolio

A simple personal engineering portfolio built with plain HTML and CSS.

## GitHub Pages setup

1. Create a repository named `YOUR_USERNAME.github.io`.
2. Upload `index.html`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/ (root)`
5. Save.

## Replace the placeholders

Search `index.html` for:

- `YOUR NAME`
- `YOUR_USERNAME`
- `YOUR_EMAIL@example.com`
- `YOUR_RESUME_URL.pdf`
- `YOUR_PAPER_LINK`
- `PLACEHOLDER`

## Adding images

Create an `images` folder and replace a placeholder such as:

```html
<div class="media">PLACEHOLDER — Add gripper CAD render</div>
```

with:

```html
<img class="project-image" src="images/gripper-cad.png" alt="Gripper CAD model">
```

Then add this CSS if desired:

```css
.project-image {
  max-width: 100%;
  display: block;
  margin-top: 18px;
}
```

## Adding videos

For a local MP4:

```html
<video controls width="100%">
  <source src="videos/cobot-path-planning.mp4" type="video/mp4">
</video>
```

Keep the site simple. The goal is to let the engineering work and project documentation be the focus.

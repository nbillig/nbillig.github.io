# Engineering Portfolio

A clean, single-page engineering portfolio designed for GitHub Pages.

## Quick start

1. Create a GitHub repository named:
   `YOUR_USERNAME.github.io`

2. Upload `index.html`.

3. In GitHub:
   **Settings → Pages → Deploy from a branch → main → / (root)**

4. Your site will be available at:
   `https://YOUR_USERNAME.github.io`

## Replace these placeholders

Search `index.html` for:

- `YOUR NAME`
- `YOUR_USERNAME`
- `YOUR_EMAIL@example.com`
- `YOUR_RESUME_URL.pdf`
- `YOUR_PAPER_LINK`
- Project descriptions
- Media placeholders

## Adding images

Create an `images` folder and add files such as:

```text
images/
  gripper-main.jpg
  gripper-cad.png
  pcb-layout.png
  hall-sensor.gif
  force-simulation.png
  digital-twin.jpg
  continuum-arm.gif
  snad.jpg
```

Then replace a placeholder such as:

```html
<div class="media-placeholder">
  ...
</div>
```

with:

```html
<img src="images/gripper-main.jpg"
     alt="Soft adaptive robotic gripper"
     style="width:100%; display:block;">
```

## Adding videos

For a local MP4:

```html
<video controls playsinline style="width:100%; display:block;">
  <source src="videos/cobot-path-planning.mp4" type="video/mp4">
</video>
```

For GitHub Pages, keep video files reasonably compressed. Alternatively, embed a YouTube video.

## Recommended repository structure

```text
portfolio/
├── index.html
├── README.md
├── images/
└── videos/
```

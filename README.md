# KAIROS project website

This repository contains the GitHub Pages website for:

**KAIROS: Keyframe-Aligned Long-Horizon Video Imagination for Robot Manipulation**

## How to publish

Create the repository under the GitHub organization:

```text
kairos-manipulation/kairos-manipulation.github.io
```

Then upload these files to the repository root:

```text
index.html
.nojekyll
assets/
```

GitHub Pages should publish automatically at:

```text
https://kairos-manipulation.github.io/
```

If it does not appear immediately:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
4. Save.

## Replace placeholder media

Put your videos here:

```text
assets/videos/open_drawer.mp4
assets/videos/open_single_door.mp4
assets/videos/close_drawer.mp4
assets/videos/push_into_drawer.mp4
```

The HTML already points to these names.

## Edit paper information

In `index.html`, edit:

- title
- author list
- abstract
- paper/code links
- BibTeX


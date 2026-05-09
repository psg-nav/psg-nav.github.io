# PSG-Nav: Probabilistic Scene Graph Navigation via Multiverse Decision Making

> **ICML 2026**
>
> 🌐 **Project Page**: [https://chenrf1121.github.io/psg-nav/](https://chenrf1121.github.io/psg-nav/)
>
> 📄 **Paper**: [arXiv (coming soon)]()
> 💻 **Code**: [GitHub (coming soon)]()

---

## About

This is the official project page for **PSG-Nav**, accepted at **ICML 2026**.

## Local Preview

```bash
cd psg-nav-website
python3 -m http.server 8765
# Open http://localhost:8765
```

## Deploy to GitHub Pages

1. Create a repo named `psg-nav` under your GitHub account (`Chenrf1121`).
2. Push the `psg-nav-website/` folder contents to the `main` branch (as root of the repo, or in a `docs/` folder).
3. In the repo **Settings → Pages**, set source to `main` branch (and `/ (root)` or `/docs` depending on where files live).
4. The site will be live at `https://chenrf1121.github.io/psg-nav/`.

### Option A: Deploy from root of `main`
```bash
git init
git add .
git commit -m "Initial commit: PSG-Nav project page"
git remote add origin https://github.com/Chenrf1121/psg-nav.git
git push -u origin main
# Then enable GitHub Pages in repo settings → source: main / (root)
```

### Option B: Deploy from `docs/` folder
Move all files into a `docs/` folder, push, then set GitHub Pages source to `main /docs/`.

## TODO (before publication)

- [ ] Fill in author names and affiliations in `index.html`
- [ ] Update arXiv link once paper is on arXiv
- [ ] Update code link once GitHub code repo is public
- [ ] Update BibTeX entry with correct author names

## File Structure

```
psg-nav-website/
├── index.html       # Main project page (this is the GitHub Pages entry point)
├── images/          # Figures and teaser images
│   ├── page_fig_method.jpg
│   ├── page_results_table.jpg
│   ├── page_vis_hm3d.jpg
│   ├── page_vis_mp3d.jpg
│   ├── page_vis_hssd.jpg
│   ├── robot_platform.png
│   └── algorithm.png
├── videos/         # Demonstration videos
│   ├── hm3d-chair.mp4
│   ├── hm3d-plant.mp4
│   ├── hm3d-tv.mp4
│   ├── mp3d-chest-of-drawers.mp4
│   ├── ovon_cloths.mp4
│   ├── ovon_pillow.mp4
│   ├── ovon_rug.mp4
│   ├── real-chair.mp4
│   └── real-keyboard.mp4
└── README.md       # This file
```

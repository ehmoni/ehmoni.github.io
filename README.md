# Enamul Haque (Moni) — Personal Academic Website

A premium, modern academic website for **Enamul Haque (Moni)**, PhD Candidate & Researcher at the University of Waterloo, Data Systems Group.

## ✨ Features

- **Animated constellation particle background** — subtle, elegant AI-lab aesthetic
- **Spinning gradient profile ring** — professional hero section with glow effects
- **Dark / Light mode toggle** — one-click theme switching
- **Scroll reveal animations** — elements fade in as you scroll
- **Animated counters** — numbers count up on first view
- **Publication filter system** — filter by topic (Knowledge Representation, Data Systems, ML/AI)
- **Poster modal viewer** — clickable poster cards with detailed popup descriptions
- **Fully responsive** — optimized for mobile, tablet, and desktop
- **Fast loading** — no build step needed; pure HTML/CSS/JS
- **GitHub Pages ready** — deploy in minutes

## 📁 Folder Structure

```
enamul-website/
├── index.html              ← Main website (all sections)
├── README.md               ← This file
└── assets/
    └── img/
        ├── profile.jpg     ← YOUR PROFILE PHOTO (add this)
        ├── poster1.pdf     ← Research Poster 1 (add this)
        ├── poster2.pdf     ← Research Poster 2 (add this)
        ├── poster3.pdf     ← Research Poster 3 (add this)
        └── poster4.pdf     ← Research Poster 4 (add this)
```

## 🖼️ Adding Your Assets

### Profile Photo
1. Rename your photo to `profile.jpg`
2. Place it in `assets/img/`
3. Recommended: square crop, at least 400×400px

### Posters
1. Name your poster PDFs: `poster1.pdf`, `poster2.pdf`, `poster3.pdf`, `poster4.pdf`
2. Place them in `assets/img/`
3. They will be linked from the poster modal "View PDF" buttons

## 🚀 Deploying to GitHub Pages

### Step 1 — Create a GitHub repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `ehmoni.github.io` (or any name for a project page)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload your files
**Option A: GitHub Web UI**
1. Open your repository
2. Click **"Add file" → "Upload files"**
3. Drag and drop all files from this folder (maintaining folder structure)
4. Click **Commit changes**

**Option B: Git CLI**
```bash
cd enamul-website
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/ehmoni/ehmoni.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages**
2. Under "Source", select **main branch** and **/ (root)**
3. Click **Save**
4. Your site will be live at `https://ehmoni.github.io` in ~60 seconds

## 🎨 Customization Guide

### Update personal information
All personal info is in `index.html`. Search for any text you want to update.

### Add/edit publications
Find the `<div class="pub-list">` section and add new `.pub-card` divs following the existing pattern.

### Add news items
Find the `<div class="news-grid">` section and add new `.news-card` links.

### Adjust colors
Edit the CSS variables at the top of the `<style>` block:
```css
:root {
  --cyan: #00d4ff;      /* Accent color */
  --gold: #f0c060;      /* Secondary accent */
  --lavender: #9d8eff;  /* Tertiary accent */
  /* ... */
}
```

### Change fonts
Replace the Google Fonts link in `<head>` with your preferred fonts and update `--font-display`, `--font-body`, `--font-mono` in `:root`.

## 📱 Browser Compatibility
- ✅ Chrome / Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## 📄 License
This website template was created for Enamul Haque (Moni). All personal content (bio, publications, research areas) belongs to Enamul Haque.

---

*Built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies.*

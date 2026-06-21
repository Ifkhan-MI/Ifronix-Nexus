# IFRONIX NEXUS — 3D Portfolio

> A futuristic 3D isometric portfolio built with Three.js, vanilla JS, and CSS — no frameworks, no build tools.

![IFRONIX NEXUS Preview](preview.png)

## 🚀 Live Demo

**[View Portfolio →](https://YOUR-USERNAME.github.io/ifronix-nexus/)**

> Replace `YOUR-USERNAME` with your GitHub username after deploying.

---

## ✨ Features

- **Full 3D isometric scene** — animated robot developer at a desk, built entirely with Three.js geometry (no external 3D models)
- **Photo on monitor screen** — your face displayed on the 3D computer screen in-scene
- **Interactive profile panel** — click the monitor or robot to open a full expanded card with bio, skills with icons, "Why Choose Me" reasons, and all social links
- **Drag to orbit** — rotate the 3D scene freely with mouse or touch
- **Live FPS counter** — top-right HUD element
- **Toggles** — Grid Lines, Auto Rotate, Screen Glow controls
- **Cyber HUD overlays** — corner brackets, scanlines, status badge
- **Fully self-contained** — single `index.html` with photo embedded, works offline

---

## 📁 File Structure

```
ifronix-nexus/
├── index.html          ← Main 3D portfolio (open this)
├── my.jpeg             ← Your profile photo
├── README.md           ← This file
├── LICENSE             ← MIT license
└── .gitignore          ← Git ignore rules
```

---

## 🛠 How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click **"New repository"**
3. Name it: `ifronix-nexus`
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload Files
**Option A — GitHub Web UI (easiest):**
1. Inside the new repo, click **"uploading an existing file"**
2. Drag and drop all files: `index.html`, `my.jpeg`, `README.md`, `LICENSE`, `.gitignore`
3. Click **"Commit changes"**

**Option B — Git CLI:**
```bash
git init
git add .
git commit -m "Initial commit — IFRONIX NEXUS 3D Portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ifronix-nexus.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **"Source"**, select branch: `main`, folder: `/ (root)`
3. Click **Save**
4. Wait ~60 seconds, then visit: `https://YOUR-USERNAME.github.io/ifronix-nexus/`

---

## 🎮 Controls

| Action | Result |
|--------|--------|
| Click monitor / robot | Opens profile panel |
| Drag mouse / touch | Orbit the 3D scene |
| `Escape` | Close profile panel |
| Grid Lines toggle | Show/hide floor grid |
| Auto Rotate toggle | Slowly spin the scene |
| Screen Glow toggle | Toggle monitor glow |

---

## 🧰 Tech Stack

- **Three.js r128** — 3D rendering (loaded via CDN)
- **Vanilla JavaScript (ES Modules)** — zero frameworks
- **CSS3** — HUD overlays, glassmorphism panel, animations
- **Google Fonts** — Orbitron, Share Tech Mono, Inter
- **FontAwesome 6** — social/skill icons

---

## 📬 Contact

| Platform | Details |
|----------|---------|
| Email | ifkhanomer9619@gmail.com |
| WhatsApp | +94 759 291 036 |
| Instagram | [@if_khn](https://www.instagram.com/if_khn) |
| LinkedIn | [Ifkhan MI](https://www.linkedin.com/in/ifkhan-mi-8153a9418) |
| Facebook | [IFRONIX NEXUS](https://www.facebook.com/share/1DpBBABBqj/) |

---

## 📄 License

MIT © 2026 Ifkhan MI — IFRONIX NEXUS

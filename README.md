# Sustainable Environment — Landing Page

A simple, responsive landing page focused on a sustainable environment theme.

> Repo: `qwe-creator/landing-page-on-susatinable-environment` (note: repository slug contains a small typo in “sustainable”).

---

## ✨ Overview

This project is a static website built with **HTML** and **CSS** (with a pre-bundled Bootstrap copy in the repo). It’s ideal for a lightweight marketing/awareness page—easy to host on GitHub Pages or any static host.

---

## 📂 Project Structure

nature_preverse/
├─ index.html
├─ style.css
├─ bootstrap/
│ ├─ css/
│ │ └─ bootstrap.min.css
│ └─ js/
│ └─ bootstrap.min.js
├─ font/
│ ├─ gl.otf
│ ├─ gr.otf
│ ├─ ml.ttf
│ ├─ mr.ttf
│ └─ pm.ttf
└─ img/
├─ abc.jpg
├─ cloutree.webp
├─ end.png
├─ file.png
├─ ic_tree.png
└─ tree1.jpg

> The main entrypoint is `nature_preverse/index.html`. Custom styles live in `nature_preverse/style.css`. Fonts and images are bundled under `font/` and `img/`. A local copy of Bootstrap is included in `bootstrap/`.

---

## 🚀 Getting Started

### 1) Run locally
You don’t need a build step. Any static server or even opening the file directly works.

- **Option A (quick open):** Double-click `nature_preverse/index.html`.
- **Option B (recommended):** Serve with a local web server for correct paths:
  - VS Code: install **Live Server** → “Go Live” from `nature_preverse/`.
  - Python:  
    ```bash
    cd nature_preverse
    python -m http.server 8000
    # Open http://localhost:8000 in your browser
    ```

### 2) Deploy (GitHub Pages)
1. Move or copy the `nature_preverse` contents to the repo root (or set Pages to use the `/nature_preverse` folder).
2. In GitHub: **Settings → Pages → Build and deployment**  
   - Source: **Deploy from a branch**  
   - Branch: **main** (root or `/nature_preverse`)  
3. Save. Your site will be available at the GitHub Pages URL.

---

## 🛠️ Tech Stack

- **HTML5** & **CSS3**
- **Bootstrap** (minified CSS & JS included locally)
- Optional: You can replace Bootstrap with a **Tailwind CSS** CDN or build step if you prefer utility-first styling.

---

## 🔧 Customization

- **Branding & Content:** Edit text, images, and links directly in `index.html`.
- **Styles:** Tweak global styles in `style.css`. If using Bootstrap utilities, you can also override variables or add custom classes here.
- **Assets:** Replace images in `img/` and fonts in `font/` with your own (keep file names/paths or update references in HTML/CSS).

---

## ✅ Tips & Good Practices

- Compress images (`.jpg`, `.webp`) to keep the page lightweight.
- Add basic SEO tags (title, meta description, Open Graph) in `<head>`.
- Ensure accessible color contrast and alt text on all images.
- If you continue with Bootstrap, consider using its grid & utility classes consistently; if migrating to Tailwind, remove the Bootstrap bundle to reduce size.

---

## 🗺️ Roadmap (nice-to-haves)

- Fix naming typos:
  - Repo: `landing-page-on-**sustainable**-environment`
  - Folder: `nature_**preserve**` (currently `nature_preverse`)
- Add a favicon and manifest.
- Add basic CI (HTML/CSS lint) via GitHub Actions.
- Optional theme toggle (light/dark).

---

## 🤝 Contributing

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add your feature"`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

No license file is present yet. If you intend others to use or adapt this, consider adding a license (e.g., MIT).

---

## 👤 Author

- **@qwe-creator**

If you use this, a ⭐ on the repo is appreciated!


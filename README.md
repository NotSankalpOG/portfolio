# Made For CodexDevs

# 🌐 **Personal Developer Portfolio**

### Crafted with Precision · Designed for Performance · Built for CodexDevs

---

## 📘 Overview

This repository contains the source code for **A Developer’s** interactive and visually immersive personal portfolio website. Designed with a blend of **aesthetic modernism**, **technical precision**, and **high-end UI effects**, this portfolio represents a fully responsive, automated, and experience‑driven web presence deployed on **GitHub Pages**.

The site demonstrates advanced front‑end engineering concepts, custom animations, dynamic content fetching, and a refined multi-section layout engineered to provide clarity, speed, and elegance.

---

## 🎯 Purpose of This Portfolio

* Act as a **professional identity platform**.
* Dynamically display **GitHub repositories as real-time projects**.
* Showcase **technical abilities, creativity, and engineering skills**.
* Provide a futuristic, engaging, and smooth browsing experience.

---

# ⚡ Key Features

## 🔹 1. **Modern Hero Section**

A striking hero banner featuring:

* Futuristic glitch typography
* Gradient-enhanced name reveal animations
* High-contrast dynamic background elements
* Clean, highly aesthetic introductory text

---

## 🔹 2. **About Section**

A polished, informative overview of Aryansh Rai including:

* Professional introduction
* Summary of core strengths
* Experience highlight badge
* Visual framing using cyber-themed UI elements

---

## 🔹 3. **Skills & Tech Stack Section**

Beautifully structured skill categories with:

* Icon‑based skill cards
* Animated progress indicators
* Segmented categories such as Frontend, Backend, Tools, and more
* Responsive grid layout for all screen sizes

Technologies showcased include:

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**

---

## 🔹 4. **Animated UI + Custom Cursor System**

A dynamic UI system featuring:

* High‑precision custom cursor
* Smooth cursor follower
* Magnetic hover interactions
* Multi-layer animation and parallax responsiveness

---

## 🔹 5. **Projects Section — Auto‑Updating via GitHub API**

One of the most powerful features of the site.

The portfolio automatically:

* Fetches all public repositories of `aryanshrai03`
* Generates live project cards
* Displays repo metadata (description, stars, languages, etc.)
* Includes a **dropdown panel that loads README.md** for each project
* Renders README content as formatted Markdown
* Caches results for smooth user experience

If README.md is missing → A fallback message appears.

This transforms the portfolio into a **self-updating showcase** with **zero manual maintenance**.

---

## 🔹 6. **Theme Toggle (Light & Dark Modes)**

The portfolio supports seamless theme switching with:

* Persistent preferences saved automatically
* Smooth transitions between themes
* Recoloring of UI elements using CSS variables

---

## 🔹 7. **Custom Animations + VFX System**

The website includes an advanced animation suite:

* Glitch text effects
* Floating shapes
* Gradient orbs with blur and pulse motion
* Cyber lines scanning animations
* Dynamic hex-grid overlays
* Data stream visual effects
* Interactive ripple effects
* Snowfall canvas animation overlay

All visuals are optimized for performance and responsiveness.

---

## 🔹 8. **Contact Section**

A clean, user-friendly contact interface with:

* Professional layout
* Interactive form elements
* Gradient focus states
* Responsive two-column grid

---

## 🔹 9. **Fully Responsive Design**

Crafted using modern CSS techniques:

* Fluid grids
* Adaptive typography
* Mobile‑first media queries
* Optimized for all devices (desktop/tablet/mobile)

---

# 🛠️ Technologies Used

### **Core Stack**

* **HTML5**
* **CSS3** (with variables, animations, gradients, responsiveness)
* **Vanilla JavaScript**

### **APIs & External Tools**

* **GitHub REST API** for auto-loading projects
* **Markdown parser** for rendering README.md content

### **Deployment**

* **GitHub Pages** (static hosting)

---

# 🧠 Project Architecture

```
root/
│ index.html
│ style.css
│ script.js
```

---

# 🚀 Deployment Instructions

### **1. Fork the repository**

Click the "Fork" button on GitHub to duplicate this project.

### **2. Enable GitHub Pages**

* Go to **Settings → Pages**
* Set branch to `main`
* Save → GitHub deploys automatically

### **3. Access your site**

Your portfolio will be available at:

```
https://<your-username>.github.io/<repository-name>/
```

---

# 💡 How the Auto‑Updating Project System Works

1. `script.js` fetches all repositories through the GitHub API.
2. Each project card is dynamically created using templates.
3. README.md is fetched separately from:

```
https://api.github.com/repos/<username>/<repo>/readme
```

4. README content is Base64 decoded.
5. Markdown is rendered into HTML inside a dropdown.
6. Dropdown panels use smooth height transitions.
7. Data is cached to avoid redundant requests.

This system ensures new projects show up **instantly** on your portfolio.

---

# 📱 Responsive Design Strategy

* Modular grids
* Flexible components
* Adaptive spacing tokens
* Mobile-first breakpoints
* Lightweight animations for low-power devices

---


# 📄 License

**Fully open — can be used by anyone.**

This portfolio may be reused, modified, or adapted freely.
Attribution to **Aryansh Rai (aryanshrai03)** is appreciated but not required.

---

# 🏁 Final Notes

This portfolio was built with passion, precision, and a focus on visual fluidity. It combines clean engineering with futuristic aesthetics, resulting in a highly engaging personal brand experience.

If you'd like enhancements or new modules (blogs, animations, CMS, backend integration), feel free to request updates.

---

### **© 2025 · Built by Aryansh Rai · Made For CodexDevs**

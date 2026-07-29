```markdown
# 💻 Personal Portfolio Website

A front-end web development project built for the **ITE Higher NITEC Web Development Essentials** module. This is a responsive, multi-page portfolio site built from scratch using semantic HTML5, modern CSS3, and vanilla JavaScript — showcasing layout design, styling patterns, and client-side interactivity techniques.

---

## 📖 Project Overview

This project is a personal multi-page web portfolio composed of three core linked pages:

* **Home (`index.html`):** Hero section, About Me biography, and an interactive collapsible skills dropdown.
* **Projects (`projects.html`):** A responsive project grid displaying status badges (*Complete* / *Pending*) and technology tags.
* **Learning Journey (`learning.html`):** A documented walkthrough of 7 core web development concepts mastered during the module, complete with code snippets, reflections, and live interactive demos.

The main goal was to advance beyond static styling by creating a polished, fully responsive site utilizing clean design tokens and modular JavaScript.

---

## 🛠 Technologies Used

* **HTML5:** Semantic markup structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
* **CSS3:** Custom properties (`:root`), Grid, Flexbox, Keyframe animations, Transitions
* **Vanilla JavaScript (ES6+):** DOM manipulation, event listeners, dynamic class toggling, dynamic calculations
* **Design System:** Shared CSS variables for typography, spacing, and color palettes
* **Tools:** Visual Studio Code, Browser DevTools

---

## 🎨 Key Concepts Implemented

1. **Hover Shadow Effect:** Smooth elevation animation on project cards using `transform`, `box-shadow`, and `transition`.
2. **Animated Navigation Underline:** Active and hover menu indicator using `::after` pseudo-elements with `width` transitions.
3. **Collapsible Skills Dropdown:** Interactive section driven by JavaScript `classList.toggle()` driving dynamic `max-height` transitions.
4. **Fade-In Animation:** Entrance visual effects using `@keyframes` controlling `opacity` and `translateY`.
5. **CSS Grid Layout:** Multi-column grid system (`2fr / 1fr`) that automatically collapses into a single column on mobile devices.
6. **Image Hover Transform:** Chained `scale()` and `rotate()` transform effects on the hero section profile image.
7. **Scroll Progress Bar:** Fixed top progress indicator dynamically calculated via client scroll height in JavaScript.

---

## 📊 Pages & Feature Breakdown

| Page | Key Features & Highlights |
| :--- | :--- |
| **Home (`index.html`)** | Hero banner, About Me section, animated skills dropdown, profile image transform effects |
| **Projects (`projects.html`)** | Responsive card grid layout, project status badges, tech stack tags |
| **Learning Journey (`learning.html`)** | 7 expandable concept cards, embedded code snippets, interactive live demos, module reflection |
| **Site-Wide Features** | Sticky navigation header with active state underline, real-time scroll progress bar, media queries |

---

## 📂 Project Structure

```text
.
├── index.html          # Home page
├── projects.html       # Projects showcase page
├── learning.html       # Learning Journey (7 documented concepts)
├── styles.css          # Core stylesheet (Design tokens + Global styles)
├── script.js           # Client-side JavaScript interactivity
├── README.md
└── images/             # Profile photos and project assets
    ├── profile.jpg
    ├── project1.png
    └── project2.png

```

---

## 🚀 How to Run

1. **Clone this repository:**
```bash
git clone [https://github.com/kelvinwing809-design/ITE-Web-Development-Essentials.git](https://github.com/kelvinwing809-design/ITE-Web-Development-Essentials.git)
cd ITE-Web-Development-Essentials

```


2. **Open the project:**
Simply open `index.html` directly in any web browser — no build tools, Node.js packages, or external dependencies are required!
3. *(Optional)* **Live Server:** Open the project folder in VS Code and click **Go Live** using the Live Server extension for automatic reloading.

### 🌐 Live Hosting via GitHub Pages

1. Navigate to your GitHub repository settings: **Settings → Pages**.
2. Select the **`main`** branch and folder **`/root`**, then click **Save**.
3. Access your live portfolio at: `https://kelvinwing809-design.github.io/Portfilo-website/`

---

## 📸 Sample Results

* Responsive desktop and mobile layouts for all 3 pages.
* Expandable concept cards on the Learning Journey page showing dynamic state changes.
* Smooth transitions during hover states and scroll navigation.

---

## 📚 What I Learned

Through this project, I learned:

* Designing responsive layouts using a hybrid of CSS Grid and Flexbox.
* Establishing reusable design tokens using CSS variables (`:root`) for maintainable color/typography management.
* Creating smooth micro-interactions using CSS `transitions`, `transforms`, and `@keyframes`.
* Utilizing CSS pseudo-elements (`::after`, `::before`) and pseudo-classes (`:hover`, `:focus`).
* Connecting JavaScript DOM event listeners to dynamic CSS classes to build toggleable components.
* Dynamically calculating viewport scroll positions in JavaScript (`window.scrollY`) to power a live scroll progress bar.
* Understanding absolute positioning contexts relative to parent elements (`position: relative` vs `position: absolute`).
* Structuring multi-page static websites with clean shared stylesheets and consistent navigation states.

---

## 👤 Author

**Kelvin Lee Khai Wing**

*Higher NITEC in AI Applications — ITE College Central*

* 💼 **LinkedIn:** [Kelvin Lee](https://www.linkedin.com/in/kelvin-lee-khai-wing-806195375)
* 📧 **Email:** kelvinwing809@gmail.com
* 🐙 **GitHub:** [@kelvinwing809-design](https://github.com/kelvinwing809-design)

```

```

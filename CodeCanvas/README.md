# CodeCanvas

### Where Code Meets Creativity.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive Design](https://img.shields.io/badge/Responsive_Design-4CAF50?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![Netlify](https://img.shields.io/badge/Netlify-00C8B2?style=for-the-badge&logo=netlify&logoColor=white)](https://www.netlify.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JayanthKumarChinthakindi/html-css-projects)

CodeCanvas is a premium, animated digital agency landing page built exclusively using semantic **HTML5** and raw **CSS3**. Engineered as a high-fidelity frontend portfolio piece, it showcases how modern responsive layout patterns, glassmorphism interfaces, and fluid transitions can be created without writing a single line of JavaScript.

---

## 🌐 Live Demo

Explore the live production deployment and inspect the source code repository:

* **Live Website**: [https://codecanvas-agency.netlify.app](https://codecanvas-agency.netlify.app)
* **GitHub Repository**: [https://github.com/JayanthKumarChinthakindi/html-css-projects/tree/main/CodeCanvas](https://github.com/JayanthKumarChinthakindi/html-css-projects/tree/main/CodeCanvas)

---

## 📖 About the Project

The primary purpose of CodeCanvas is to demonstrate state-of-the-art vanilla styling techniques. It serves as a proof of capability for a professional frontend developer, emphasizing:
- Creating complex micro-animations and structural movements using CSS keyframes.
- Architecting responsive layouts across desktop, laptop, tablet, and mobile dimensions without using Tailwind, Bootstrap, or other CSS frameworks.
- Integrating responsive interactions (like full mobile hamburger drawer toggles) using pure HTML and CSS logic.
- Building custom, scalable, and animatable inline SVGs for layout drawings and brand icons.

---

## ✨ Features

- **Premium Dark Aesthetic**: A dark-theme design system leveraging glowing radial gradients, overlapping drop shadows, and subtle grid lines.
- **Glassmorphic UI**: Card modules, price matrices, and navigation headers built with fine transparent borders (`rgba`) and backdrop blur filters.
- **Sticky Navigation Menu**: Fixed-to-top header featuring blurred backdrops and responsive link anchors that animate custom underlines on hover.
- **CSS Checkbox Mobile Menu**: A fully functional mobile navigation drawer driven by the checked state of a checkbox, transforming hamburger lines into a close cross ("X").
- **Custom Interactive Hero**: A split grid displaying modern typography alongside an intricate inline SVG illustration representing a creative digital workspace with layers, floating nodes, and drawing lines.
- **Services Showcase Grid**: A 3-column CSS Grid displaying 6 interactive capability cards with hover translation lifts, icon rotations, and radial glows.
- **Process Timeline**: A systematic project roadmap showcasing project phases with connecting paths, timeline badges, and content slides.
- **Testimonials Section**: Card grids containing star rating indicators and colorful initial-blocked client avatars.
- **Three-Tiered Pricing Matrix**: Displaying distinct plan highlights, with the "Professional" plan visually highlighted to attract user conversion.
- **Team Grid & Hover Overlays**: Photo cards that zoom on hover and overlay links to social handles.
- **Contact Form**: Glassmorphic inputs, outline states, and styled vector details.
- **Footer Section**: Multi-column links, brand descriptions, social connections, and newsletter forms.

---

## 🛠️ Built With

| Technology | Purpose | Core Standard |
| :--- | :--- | :--- |
| **HTML5** | Content Organization & Semantics | Living Standard |
| **CSS3** | Layouts, Animations, Variables & Responsiveness | W3C Recommendation |
| **SVG** | Vector Diagrams, Branding & Custom Icons | W3C Recommendation |

---

## 📂 Folder Structure

```text
codecanvas/
│
├── index.html       # Semantic HTML5 layout and inline SVG code
├── style.css        # Layout declarations, HSL colors, and keyframe animations
└── README.md        # Comprehensive project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the CodeCanvas agency landing page locally:

### Prerequisites
Make sure you have [Git](https://git-scm.com/) installed on your machine.

### Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone https://github.com/JayanthKumarChinthakindi/html-css-projects.git
   ```

2. **Navigate to the CodeCanvas folder**:
   ```bash
   cd html-css-projects/CodeCanvas
   ```

3. **Open the project**:
   - **Method A**: Double-click `index.html` to load the file directly in your default web browser.
   - **Method B (Recommended)**: If using VS Code, install the **Live Server** extension, right-click `index.html`, and select **Open with Live Server** to run it on `http://127.0.0.1:5500`.

---

## 📱 Responsive Design

CodeCanvas employs mobile-first layout methodologies and standard CSS media queries to support all modern screen form-factors:
- **Desktop (1200px+)**: Wide columns, offset card lifts, hover social overlays, and static side-by-side stats.
- **Laptop & Tablet Landscape (768px - 1024px)**: Grid configurations scale down from 3-column arrays into 2-column segments.
- **Tablet Portrait & Mobile (max-width: 768px)**: Link items collapse into the mobile burger menu, grids collapse to single columns, stats arrange vertically, and button CTAs adjust to full width.

---

## 🧠 CSS Concepts Practiced

Developing this project provided deep hands-on practice with advanced styling concepts:
- **Layout Engines**: Flexbox (alignment, direction) and CSS Grid (templates, columns, gap spacing).
- **Transitions & Transforms**: Transitions (`transition: cubic-bezier`), scale shifts, and Y-axis offsets.
- **Animations**: Keyframe sequences (`@keyframes`) driving floating shapes, drawing paths, and logo pulses.
- **Pseudo-Elements & Pseudo-Classes**: `:before` and `:after` connectors, `:checked` states, and `:hover` selectors.
- **Variables & Tokens**: Shorthand custom properties (`--primary`, `--bg-primary`) to maintain design rules.
- **Backdrop Filters**: Applying `backdrop-filter: blur()` to establish glassmorphism layers.
- **Layering & Z-index**: Controlling 3D visual hierarchies using `position: absolute/fixed` and `z-index`.

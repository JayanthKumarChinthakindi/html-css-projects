# DevJournal

DevJournal is a responsive, modern developer magazine and blog homepage. This project was developed as a clean-code implementation using semantic HTML5 and vanilla CSS3 to showcase advanced responsive layouts, CSS Grid layouts, Flexbox alignment structures, and typography hierarchy without relying on external frameworks, CSS preprocessors, or JavaScript.

Live Deployed URL: [https://devjournal-jk.netlify.app](https://devjournal-jk.netlify.app)

---

## Features

- **Semantic HTML5 Architecture**: Fully structured with `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>` elements for accessibility and clear SEO hierarchy.
- **Advanced Grid Layout**: Incorporates multiple CSS Grid layouts, including a split hero featured article area, a main content-sidebar split grid, and 3-column article showcase matrices.
- **Sticky Header & Sticky Sidebar**: Uses CSS `position: sticky` logic to float headers and sidebars on scroll.
- **Glassmorphic Badge Overlays**: High-contrast, frosted-glass category badges floating over thumbnail graphics.
- **CSS-Only Micro-Animations**: Smooth hover-state transitions for navigation link underlines, card elevation transformations, image scale factors, and button fill colors.
- **Responsive Design System**: Seamless column adjustments for desktop, laptop, tablet, and mobile screens.
- **No External Libraries**: Zero dependency project (no Tailwind, Bootstrap, Sass, JS, or icon library imports).

---

## Technologies Used

- **HTML5**: Semantic web structure and accessible navigation elements.
- **CSS3**: CSS Custom Properties (variables), CSS Grid, Flexbox, custom scrolls, responsive media queries, and transition animations.
- **Google Fonts**: Inter (Type Scale typography integration).
- **Netlify**: Direct static site deployment and hosting.

---

## Folder Structure

```text
DevJournal/
├── index.html
├── style.css
└── README.md
```

---

## Getting Started

To view the project locally, clone the repository and open `index.html` in your web browser:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JayanthKumarChinthakindi/html-css-projects.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd "html-css-projects/DevJournal"
   ```

3. **Open in browser**:
   - Double-click `index.html` to open it in your browser, or
   - Use a local server (e.g., Python `python -m http.server` or Node `npx http-server`).

---

## Responsive Design

The stylesheet contains custom media queries to support responsive layouts across standard viewports:

- **Desktop (1200px+)**: Multi-column grids (3-column article cards next to a sticky sidebar, 4-column footer layout).
- **Laptop (992px - 1199px)**: Columns scale down to 2-column content cards with the sidebar remaining visible.
- **Tablet (768px - 991px)**: Navigation links collapse and horizontal margins tighten. The main layout transitions to a vertical flow, moving the sidebar underneath the article grids.
- **Mobile (Up to 767px)**: All article cards, form fields, and footers stack into single-column layouts for reading clarity.



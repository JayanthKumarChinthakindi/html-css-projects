# 🔥 Ember & Vine — Modern Restaurant Landing Page

**Ember & Vine** is a premium, visually stunning single-page landing page designed for a high-end, open-flame restaurant and curated wine pairing experience. Built with a focus on immersive dark aesthetics, smooth micro-animations, and modern responsive layout techniques, this landing page delivers an upscale digital dining narrative entirely without frameworks or JavaScript.

---

## 🌐 Live Demo

Experience the premium animations, typography, and responsive layout live:

👉 **[View Live Site](https://ember-and-vine-338.netlify.app)** 👈

---

## 🛠️ Tech Stack

This project was built from scratch using clean, modern, semantic web standards:

- **HTML5:** Semantic structure, accessible markup, and checkbox hack for mobile navigation.
- **CSS3:** Custom properties (CSS variables), Flexbox, CSS Grid, custom cubic-bezier transitions, and media queries.
- **Google Fonts:** Integration of *Playfair Display* for classic heading typography and *Outfit* for a sleek modern sans-serif body copy.
- **No Frameworks, No JavaScript:** Pure, lightweight, ultra-fast loading performance.

---

## ✨ Key Features & Layout Techniques

This project serves as a showcase of modern CSS capabilities, resolving complex layout challenges without resorting to heavy libraries:

*   **⚡ Responsive Navigation (Flexbox & Checkbox Hack):** 
    Uses Flexbox for clean horizontal alignments of brand elements and link items. It incorporates a **pure CSS mobile menu drawer** driven by the "checkbox hack" (`input[type="checkbox"]` toggle and adjacent sibling selectors) to handle mobile hamburger menus dynamically.
*   **📐 CSS Grid Layouts:**
    *   **Menu Section:** A responsive, flexible card-based system built on CSS Grid that seamlessly wraps menu items across screen sizes.
    *   **Interactive Photo Gallery:** An asymmetrical, masonry-style photo grid leveraging `grid-row` and `grid-column` spanning (e.g., `.span-row-2`, `.span-col-2`) to display gorgeous dining space visuals in a premium layout.
*   **🖼️ Precision Image Presentation (`object-fit`):**
    Utilizes `object-fit: cover` and `object-position` properties inside image wrappers to ensure the curated restaurant images retain their aspect ratio and look perfectly cropped across all viewport resolutions.
*   **🎭 Sleek Visual Depth (Gradient Overlays):**
    Implements multi-layered linear-gradient overlays on the Hero section backgrounds and gallery hover states to guarantee text legibility, contrast, and a warm, glowing ember ambiance.
*   **✨ Premium Micro-interactions (CSS Transitions):**
    All interactive elements (menu cards, gallery items, social buttons, and links) utilize custom cubic-bezier transitions (`cubic-bezier(0.16, 1, 0.3, 1)`) for buttery-smooth hover states, subtle card scaling, glowing border shifts, and slide-up text reveals.

---

## 📂 Folder Structure

The project maintains a clean, modular structure for easy maintenance and deployment:

```text
Ember & Vine/
├── images/              # Curated asset directory for food, drinks, and gallery images
│   ├── menu_ribeye.png
│   ├── menu_pasta.png
│   ├── menu_salmon.png
│   ├── gallery_bar.png
│   ├── gallery_chef.png
│   ├── gallery_dessert.png
│   └── gallery_patio.png
├── index.html           # Main markup file containing semantic HTML5 sections
├── style.css            # Custom CSS3 stylesheet housing design variables & grid layouts
└── README.md            # Project documentation and details
```

---

## 🚀 How to Run Locally

Get the landing page running on your local machine instantly with these simple steps:

1.  **Download or Clone the Repository:**
    ```bash
    git clone https://github.com/JayanthKumarChinthakindi/html-css-projects.git
    ```
2.  **Navigate to the Project Directory:**
    ```bash
    cd "Ember & Vine"
    ```
3.  **Open in Browser:**
    - Double-click the `index.html` file in your file manager, or
    - Right-click `index.html` and choose **Open With** -> **Your Preferred Browser** (Chrome, Firefox, Safari, Edge).
4.  *(Optional)* Run using a local development server like **Live Server** in VS Code to see live changes during edits.

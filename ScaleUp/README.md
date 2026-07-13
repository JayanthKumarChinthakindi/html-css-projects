# ScaleUp - Modern SaaS Landing Page

ScaleUp is a responsive, modern SaaS marketing landing page built using a utility-first CSS workflow with **Tailwind CSS v4** and **Vite**. The project is designed with a premium, dark-mode aesthetic featuring custom gradients, glowing background overlays, subtle glassmorphism, and responsive transitions.

## 🚀 Live Demo

You can view the fully deployed production version of the landing page here:
👉 **[View Live Preview](https://venerable-selkie-48a26c.netlify.app)**

---

## 🛠️ Tech Stack

- **Markup & Layout:** HTML5 (semantic elements)
- **Styling:** Tailwind CSS v4 (using `@import "tailwindcss"` and modern `@theme` variables)
- **Asset Generation:** Custom high-resolution SaaS dashboard mockup
- **Build Tool / Bundler:** Vite 6
- **Deployment:** Netlify CLI

---

## 📐 Key Features & Layouts

- **Responsive Containers:** Consistent horizontal bounds across screen sizes using utility classes (`max-w-7xl`, `mx-auto`, `px-4`).
- **Hero Section:** A flexible split-screen layout (`flex-col md:flex-row`) containing:
  - Left column with bold marketing copy, a glowing badge, and horizontal CTA actions (`flex gap-4`).
  - Right column with a premium dashboard visualization mockup.
- **Features Grid:** A 3-column features showcase using responsive flex/grid layouts.
- **Pricing Matrix:** A 3-tier pricing structure (Starter, Pro, Enterprise) built with a responsive grid (`grid-cols-1 md:grid-cols-3`):
  - **Highlighted Tier:** The central "Pro" plan stands out with a solid dark slate background, shadow accentuation, and a vertical offset (`md:-translate-y-4`).
  - **Feature Lists:** Individual feature lists are structured using Flexbox to align checkmarks perfectly with the text.
- **Mobile Navigation:** A glassmorphism navigation header with a toggleable responsive drawer script.

---

## 💻 Local Development Setup

To run this project locally, make sure you have [Node.js](https://nodejs.org/) installed.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/JayanthKumarChinthakindi/html-css-projects.git
   cd html-css-projects/ScaleUp
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   - Standard Vite dev command:
     ```bash
     npm run dev
     ```
   - *Windows note:* If your path contains special characters or spaces (like `HTML&CSS Projects`), you can run Vite directly through node to bypass shell escaping issues:
     ```bash
     node .\node_modules\vite\bin\vite.js
     ```

4. **Production Build:**
   - Compile and optimize assets:
     ```bash
     node .\node_modules\vite\bin\vite.js build
     ```
   - The compiled files will be created in the `dist` directory.

---

## 🌐 Deployment

The project is configured for deployment using the Netlify CLI. 

To deploy changes to production:
1. Build the production assets:
   ```bash
   node .\node_modules\vite\bin\vite.js build
   ```
2. Trigger the production deployment using Netlify CLI:
   ```bash
   npx netlify deploy --prod --dir=dist --no-build
   ```

# AuthFlow – Modern Authentication UI Kit

AuthFlow is a premium, modern, and production-quality SaaS authentication UI kit built exclusively using **HTML5** and **Tailwind CSS**. It is designed for software engineering portfolios and modern developer portals, drawing inspiration from industry leaders like Stripe, Linear, Vercel, Notion, Clerk, and Supabase.

This kit contains 8 responsive authentication pages that share a visually cohesive design language. No JavaScript, React, Vue, or external UI libraries are used. All micro-interactions, focus rings, hover effects, scale triggers, and transitions are built entirely using pure Tailwind utilities.

---

## 🚀 Features

- **Cohesive Design Language**: Clean white cards, custom soft grid-mesh backgrounds, modern typography (Inter), rounded inputs, minimal gray borders, and a beautiful blue primary accent.
- **Micro-Animations & Transitions**: Fluid scale-downs on active click, smooth hover transitions on fields/buttons/links, custom line-slide underlines, and custom custom-styled checkboxes.
- **Production-Ready Input States**: Features full styling representations for:
  - Required indicators (`*` badges)
  - Focus-rings (`focus:ring-4 focus:ring-blue-600/10`)
  - Hover states and border transitions
  - Interactive validation states (default, hover, focus, disabled, read-only, error, success, and warning).
- **Responsive Layout**: Designed mobile-first, stretching comfortably across mobile, tablet, laptop, desktop, and ultrawide displays.
- **Semantic HTML5 & Accessibility (A11y)**: Accessible color contrasts, structured headings (`h1` through `h4`), input field labels, proper placeholder values, and focus states for keyboard navigation.
- **Embedded Style Guide**: The login page (`index.html`) includes a scrollable interactive style guide and sandbox showcase showing all inputs, buttons, link behaviors, checkmarks, social icons, and typography states for rapid reference.

---

## 📁 Folder Structure

```
/
├── index.html (Login Screen & Embedded UI Kit Playground)
├── signup.html (Registration Screen with validation helpers)
├── forgot-password.html (Password recovery request screen)
├── reset-password.html (New password entry & visual strength indicator)
├── verify-email.html (Inbox checking request with status banner)
├── otp-verification.html (2FA verification featuring mock active typing cursor)
├── success.html (Verification complete with animated checkmark)
├── error.html (Invalid/Expired token screen with error logger)
├── assets/
│   ├── logo.svg (Geometric brand signature)
│   ├── favicon.svg (Clean, responsive identity mark)
│   └── illustrations/
│       ├── forgot-password.svg (Secure key & sparkle details)
│       ├── verify-email.svg (Verification airplane checkmark)
│       └── error.svg (Alert warning shield)
└── README.md (Documentation)
```

---

## 🛠️ Technologies Used

1. **HTML5**: Semantic tags (`main`, `header`, `footer`, `section`, `form`, etc.)
2. **Tailwind CSS**: Cdn link for instant loading, customized dynamically to inherit Google's premium `Inter` font.
3. **Google Fonts**: Inter for crisp typography.
4. **SVG Icons**: Pure inline SVG representations of Google, GitHub, Apple, Microsoft, lock, user, shield, mail, check, and arrows.

---

## 🧩 Shared Components & Variables

### Color Palette

- **Background**: Soft Gray (`bg-gray-50`/`#f9fafb`) with a radial-mesh grid pattern overlay.
- **Card**: Pure White (`bg-white`) with fine border outlines (`border-gray-200/80`) and deep shadows (`shadow-2xl shadow-gray-200/50`).
- **Primary Blue Accent**: Indigo-Blue (`bg-blue-600` / `#2563eb`), hovering to deep blue (`hover:bg-blue-700` / `#1d4ed8`).
- **Input Focus Ring**: Glowing blue opacity halo (`focus:ring-4 focus:ring-blue-600/10`).

---

## 🎨 Interactive Style Guide Components

The interactive components listed below are displayed in the showcase at the bottom of the main login screen (`index.html#playground`):

| Component Category | Included Styles & States |
| :--- | :--- |
| **Inputs** | Default, Hover, Focus, Disabled, Read-only, Error (red), Success (green), Warning (amber). |
| **Buttons** | Primary, Secondary, Outline, Ghost, Danger, Disabled, Loading (visual spin), Icon. |
| **Checkboxes** | Unchecked, Checked, Disabled. |
| **Identity Providers** | Custom Brand buttons with SVGs for Google, GitHub, Apple, and Microsoft. |
| **Links** | Blue animated underline, standard gray secondary, danger links. |

---

## ⚙️ How to Run Locally

Since this is a client-side frontend project, you do not need any local servers or compiler dependencies to run it.

1. **Clone/Download** the repository folder to your local machine.
2. Double-click or open any of the HTML pages (e.g. `index.html`) in a modern web browser.
3. Use the quick-navigation links at the bottom of the style guide inside `index.html` to jump across screens instantly!

---

## 🌟 Future Improvements

- Add a dynamic theme switcher (Light Mode / Dark Mode) with pure CSS classes.
- Form validation indicators using JavaScript hooks.
- Floating label inputs (Material Design style) using Tailwind peer selectors.

---

## 📄 License

Distributed under the MIT License. Feel free to copy, modify, or repurpose these templates for personal or commercial projects.

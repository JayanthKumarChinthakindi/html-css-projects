# FinVault – Modern Banking Dashboard

## Live Demo
* **Live Demo Link**: *[Netlify Live Demo Link to be added here]*

## Project Overview
FinVault is a premium, enterprise-grade, and fully responsive fintech dashboard inspired by modern financial applications like Stripe, Revolut, Wise, and Mercury. Built using **only HTML5 and Tailwind CSS**, it showcases advanced layout paradigms, CSS grid combinations, static SVG charts, and interactive behaviors **without a single line of JavaScript**.

## Technical Stack & Architecture

- **Core**: Semantic HTML5 markup
- **Styling**: Tailwind CSS (loaded via Tailwind CSS Play CDN)
- **Typography**: Google Fonts ("Inter")
- **Iconography**: Custom inline vector SVGs (ensuring zero external download flashes and pixel-perfect dark/light shifts)
- **Interactions**: Pure CSS/HTML5 state checkbox peer mappings

---

## Project Structure

```
/
├── index.html            # Main entry point (semantic HTML & Tailwind layout)
├── assets/
│   ├── images/
│   │   └── avatar.png    # Premium user profile avatar image
│   └── icons/            # (SVG icons are embedded inline inside index.html)
└── README.md             # Project documentation and deployment instructions
```

---

## Core Features & Sections

1. **Sticky Sidebar Navigation**
   - Brand safe header with visual pulsing status.
   - Complete layout of options: Dashboard, Accounts, Transactions, Cards, Payments, Investments, Budget, Analytics, and Settings.
   - Distinct visual state indicators (active blue pill background with side accent borders).
   - Sticky sidebar position via CSS relative constraints.

2. **Top Navigation Bar**
   - Responsive hamburger label for sidebar toggling on mobile.
   - Omnipresent search bar with keyboard shortcut labels (`⌘K`).
   - Control tray including Message and Alert Notifications with red warning counts.
   - **Functional Dark Mode Toggle** (built via CSS checkbox states, toggling CSS properties across all cards).
   - User profile detail presenting status and custom avatar assets.

3. **Financial Summary Metrics**
   - Row of six financial stats: Total Balance, Monthly Income, Monthly Expenses, Savings, Investments, and Credit Score.
   - Unique styling: visual trend badges (e.g. `+8.2%` or `Excellent`), positive/negative colored indicators, top accent color borders.

4. **Premium Bank Cards**
   - Card 1 (Visa Infinite): Obsidian navy blue gradient with glossy holographics and contactless waves.
   - Card 2 (Mastercard World): Aurora sunset gradient with Mastercard brand circles.
   - Scale transformations and glossy gradient shine animations on hover.

5. **Financial Analytics Section**
   - Monthly Spending: Dynamic custom bar height chart with hoverable exact value tooltips.
   - Income vs Expenses: Side-by-side comparative grid columns.
   - Weekly Activity: Custom static vector SVG area line chart with gradient fill.
   - Expense Categories: Circular SVG ring segment doughnut charts with complete hover-friendly labels.

6. **Recent Transactions Logs**
   - Structured logs detailing Apple purchases, Stripe payouts, Netflix subscriptions, Uber Eats delivery, and AWS infrastructure costs.
   - Adaptive badge tags (Completed, Pending, Failed).
   - Interactive hover color adjustments and horizontal overflow support on smaller devices.

7. **Savings & Budgets**
   - Multi-fund progress visualizers (Emergency Fund, Vacation Goal, New Car, Spend Budgets).
   - Structured metrics (`75% Achieved` and remaining quantities).

8. **Quick Actions Tray**
   - Immediate actions: Send Money, Transfer, Pay Bills, Request Payment, Deposit, and Withdraw.
   - Micro-scaling vector icons styled inside interactive card borders.

9. **Investment Portfolios**
   - Asset monitoring cards for Apple (AAPL), Tesla (TSLA), Bitcoin (BTC), Gold (XAU), and Mutual Funds (MUT).
   - Mini sparkline vector chart paths with real-time green/red price indicators.

10. **Security & Linked Devices**
    - Multi-device sessions (MacBook, iPhone, Windows Desktop) with visual location icons and active states.
    - Security shield status displaying active 2FA parameters.

---

## Pure HTML/CSS Interactions

To comply with the strict **No JavaScript** mandate, FinVault uses clever CSS selectors paired with hidden checkboxes:

### 1. Mobile Sidebar Toggle Drawer
We place a hidden checkbox at the top of the body:
```html
<input type="checkbox" id="sidebar-toggle" class="peer/sidebar hidden" />
```
The menu burger label triggers this checkbox. Sibling styling maps it:
```css
#sidebar-toggle:checked ~ .dashboard-wrapper aside {
  transform: translateX(0) !important;
}
#sidebar-toggle:checked ~ .dashboard-wrapper .sidebar-overlay {
  opacity: 1 !important;
  pointer-events: auto !important;
}
```

### 2. Functional Dark Mode Toggle
We map a similar checkbox sibling hierarchy:
```html
<input type="checkbox" id="dark-mode-toggle" class="peer/dark hidden" />
```
In the stylesheet, when checked, it overrides variables or directly styles Tailwind background and border classes:
```css
#dark-mode-toggle:checked ~ .dashboard-wrapper {
  background-color: #0B0F19 !important;
  color: #F8FAFC !important;
}
#dark-mode-toggle:checked ~ .dashboard-wrapper .bg-white {
  background-color: #111827 !important;
}
#dark-mode-toggle:checked ~ .dashboard-wrapper .border-slate-100 {
  border-color: #1E293B !important;
}
```
This flips the entire layout from slate light mode into a dark obsidian aesthetic.

---

## Responsive Design Approaches

- **Desktop (min-width: 768px/1024px)**: Dual column layouts with fixed sticky side navigation, horizontal financial grids, and large charts.
- **Tablet (768px to 1024px)**: Collapsible sidebar menus. 2-column card wrappers, wrapping elements cleanly inside nested container grids.
- **Mobile (max-width: 767px)**: Full drawer-style slide-out side menu, simple single-column blocks, horizontal swipe table scopes to fit screens, and optimized paddings.

---

## Deployment to Netlify

Deploying FinVault is quick and easy because the repository is 100% static.

### Option A: Drag & Drop (Easiest)
1. Build or download the project files into a single local folder containing:
   - `index.html`
   - `README.md`
   - `assets/` (with subdirectories and images)
2. Open your web browser and go to [Netlify Drop](https://app.netlify.com/drop).
3. Drag the folder directly into the designated drop area in your browser.
4. Netlify will deploy the site immediately and provide you with a live URL!

### Option B: Netlify CLI
If you prefer terminal-based deployment:
1. Install the Netlify CLI globally:
   ```bash
   npm install netlify-cli -g
   ```
2. Log in to your Netlify account:
   ```bash
   netlify login
   ```
3. Initialize the site and deploy from your project directory:
   ```bash
   netlify deploy --prod --dir=.
   ```
4. Define your root directory as `.` when asked. Your site is now live!

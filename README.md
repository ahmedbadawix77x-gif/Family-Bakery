# 🥐 Family Bakery — Elegant CSS-Driven Landing Page

A beautifully crafted, single-page landing site for **Family Bakery**, designed to evoke warmth, tradition, and modern elegance. Built with **semantic HTML**, **modular CSS**, and a dash of **vanilla JavaScript**, this project demonstrates how powerful **CSS Custom Properties** can be in creating a maintainable, scalable, and visually harmonious interface.


## 🌟 Why This Stands Out

### 🎨 Design Philosophy
- **Typography-First Approach**: Combines the classic serif **Playfair Display** (for headings) with the clean sans-serif **Lato** (for body) — creating a timeless bakery aesthetic.
- **Warm, Inviting Palette**: Soft creams, warm browns, and subtle golds — all defined as **CSS variables** in `:root` for one-click theming.
- **Thoughtful Spacing & Radius**: Consistent padding, margins, and rounded corners (`--radius`) applied globally for visual harmony.

### ⚙️ Modern CSS Architecture
- **100% CSS Variable–Driven**:  
  Colors, fonts, shadows, spacing, and radii are all centralized in `:root`.  
  → *Want a darker theme? Change 3 variables. Want bigger cards? Adjust `--card-padding` once.*
- **CSS Grid + Flexbox**:  
  - **Grid** powers the responsive "Our Offer" and "Gallery" sections.  
  - **Flexbox** handles navigation, hero layout, and button alignment.
- **Fully Responsive**: Mobile-first breakpoints ensure perfect rendering on every device.

### ✨ Micro-Interactions & UX
- **Delightful Hover Effects**:
  - Offer cards gently **lift and scale** on hover.
  - Gallery items **tilt and zoom** for tactile feedback.
  - Buttons shift color smoothly with `transition`.
- **Floating Scroll Shortcut**:  
  A custom JS-powered button appears after 100px of scroll, letting users **smoothly jump** to the menu section (`#offer`) — enhancing navigation on long pages.

### 🧼 Clean & Maintainable Code
- Semantic HTML5 structure (`<header>`, `<section>`, `<footer>`)
- Zero external dependencies (no frameworks, no build steps)
- All styles in a single, well-commented `style.css`

## 🛠️ Tech Stack
- **HTML5**
- **CSS3**: Custom Properties, Grid, Flexbox, `@media`, `transition`, `transform`
- **Vanilla JavaScript**: Scroll detection + smooth navigation
- **Google Fonts**: `Playfair Display`, `Lato`

## 📂 Project Structure
family-bakery/
├── index.html # Single-page layout
├── style.css # All styles (with :root variables)
└── /assets/ # (Optional) — recommended for images/fonts

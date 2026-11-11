# FlipStuck — Course Learning Platform

> **FlipStuck** is a modern, high-performance course learning platform built strictly with pure HTML and CSS—zero JavaScript dependencies. Features responsive Figma-accurate layouts, physics-based spring animations, a sleek mobile hamburger menu, interactive course catalog, curriculum accordions, and a distraction-free checkout experience.

---

## ⚡ Highlights

- **Pure HTML5 & CSS3 Only**: 100% lightweight markup and styling with **zero JavaScript or external JS runtime dependencies**.
- **Pixel-Perfect Figma Fidelity**: Accurately reproduces desktop and mobile mockups with refined typography, shadows, borders, and ambient lighting accents.
- **Physics-Based Spring Animations**: Fluid cubic-bezier easing curves (`cubic-bezier(0.34, 1.56, 0.64, 1)` and `cubic-bezier(0.2, 0.8, 0.2, 1)`) eliminating any jerky transitions.
- **Top-to-Down Bouncy Mobile Drawer**: Pure CSS animated hamburger menu that transforms into a close "X" with a staggered, spring-bouncing dropdown menu.
- **Fully Responsive Architecture**: Fluid typography using CSS `clamp()`, auto-fitting grids, scroll-safe comparison table containers, and isolated ambient glows that eliminate canvas horizontal overflow.
- **Sleek Monochrome & Lime Accents**: All icons replaced with custom vector SVGs styled in dark slate (`#0f172a`), slate grey (`#64748b`), and energetic lime (`#D2F801` / `#7ba300`).

---

## 📁 Pages Included

1. **`index.html` (Home Page)**:
   - Header with brand navigation and mobile toggle
   - Hero banner with action pills, primary CTAs, and user avatar proof badge
   - Stats metrics bar
   - Category exploration cards
   - Popular & featured courses showcase
   - Value propositions / feature cards
   - Student reviews & testimonials grid
   - Brand growth banner with layered artwork
   - Instructor spotlight profile
   - Responsive multi-column footer with Asian landscape art panorama

2. **`courses.html` (Course Catalog & Exploration)**:
   - Search bar hero with instant aesthetic focus
   - Multi-category, level, price, and rating filter sidebar (cleanly hidden on mobile for distraction-free browsing)
   - Responsive course grid with difficulty tags, ratings, and price badges

3. **`excel-course.html` (Course Syllabus & Detail)**:
   - Breadcrumb navigation
   - Course hero overview with ratings, format badges, and video preview media card
   - Interactive curriculum module accordions using native HTML5 `<details>` and `<summary>`
   - 4-column feature comparison matrix (*FlipStuck vs. YouTube vs. Other Institutes*) with touch-friendly horizontal scroll container
   - Real-world project showcase & unique ID certificate proof gallery
   - Student placement & internship opportunities section
   - Comprehensive interactive FAQ accordions

4. **`checkout.html` (Secure Enrollment Checkout)**:
   - Secure checkout header with SSL lock badge
   - 2-column conversion layout (automatically reordered on mobile to show Order Summary first, matching mobile design mockups)
   - Collapsible coupon code drawer with discount application
   - Clean enrollment form with custom vector input icons
   - Supported payment method pill badges (UPI, Cards, Net Banking)
   - Fixed mobile sticky payment CTA bar

---

## 🚀 Getting Started

No dependencies, npm packages, or build steps required. Simply serve the directory with any local static HTTP server:

```bash
# Using Python 3
python3 -m http.server 3000
```

Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🎨 Design System Tokens

- **Primary Accent**: `#D2F801` (Vibrant Lime)
- **Primary Hover**: `#c6ea00`
- **Text Main**: `#0f172a` (Slate 900)
- **Text Muted**: `#64748b` (Slate 500)
- **Background Body**: `#ffffff`
- **Subtle Surface**: `#f8fafc`
- **Borders**: `#e2e8f0`
- **Typography**: Plus Jakarta Sans & Playfair Display (Serif accent)

---

## 📄 License

MIT License. Designed and developed with pure HTML and CSS.

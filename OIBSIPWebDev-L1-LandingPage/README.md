# Task 1 · Lumina Landing Page

A modern, visually polished static landing page built for **Lumina** — a creative productivity and workspace platform. This project demonstrates foundational HTML5 semantic markup and CSS3 layout techniques (Flexbox &amp; Grid) without requiring JavaScript.

---

## 🚀 Objective & Overview

Build a responsive, beautifully styled static landing page adhering to modern web design principles (curated color palettes, modern typography, glassmorphic touches, and micro-interactions) while maintaining clean, readable, beginner-friendly code structure.

- **Tech Stack**: Pure HTML5, Modern CSS3 (No JavaScript)
- **Design System Inspiration**: Google Stitch (`projects/1130813097778906211`)
- **Fonts Used**: [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Headings) & [Inter](https://fonts.google.com/specimen/Inter) (Body)

---

## 📋 Feature Checklist

All required criteria have been implemented and verified:

- [x] **Fixed / Sticky Navigation Bar**: Sticky navbar (`position: sticky; top: 0; z-index: 1000`) with glassmorphism blur, brand logo, 4 section links (`Features`, `How It Works`, `Testimonials`, `Pricing`), and desktop/mobile CTAs.
- [x] **Hero Section**: Includes an announcement badge, compelling H1 headline with gradient text, subheadline, dual action buttons (`Start Free Trial` and `Watch Demo`), a 4.9/5 star rating cluster, and a creative workspace Kanban mockup card.
- [x] **At Least 2 Distinct Content Sections**: Included **4 content sections**:
  1. **Features Section**: 3 responsive cards using CSS Grid (`Boundless Visual Canvas`, `Distraction-Free Focus Mode`, `Automated Workflows`).
  2. **How It Works (About)**: 3-step numbered workflow timeline (`01 Capture`, `02 Structure`, `03 Ship`).
  3. **Testimonials**: 3 authentic creator quote cards with star ratings and user avatars.
  4. **Pricing Plans**: 3-tier pricing cards (`Starter`, `Pro Creator` with highlighted badge, `Team Studio`).
- [x] **Footer with Placeholder Contact / Social Links**: 5-column layout with company mission, live operational status badge, categorized navigation links, copyright notice, and SVG social links (Twitter/X, GitHub, LinkedIn).
- [x] **Consistent Colour Palette**: Maintained using CSS Custom Properties (`:root`) across all components (Electric Indigo, Vivid Violet, Dark Slate, Clean Surface).
- [x] **Responsive Layout**: Fluid layouts built with CSS Grid and Flexbox that adapt smoothly to desktop, tablet, and mobile screens without breaking or horizontal scrolling.
- [x] **No Element Overlap**: Universal `box-sizing: border-box` reset, intentional margins and paddings, and explicit line heights prevent any overlapping text or containers.
- [x] **Clean, Readable Typography**: At least 2 distinct font sizes used with clear visual hierarchy (`h1`, `h2`, `h3`, `h4`, body copy, and caption text).

---

## 🎨 Design System & Color Palette

The color scheme is defined using CSS variables in `styles.css`:

| Variable Name | Hex Code | Purpose |
| :--- | :--- | :--- |
| `--primary` | `#4F46E5` | Electric Indigo — primary brand color, CTA buttons, links |
| `--secondary` | `#7C3AED` | Vivid Violet — gradient accents and badges |
| `--accent-blue` | `#0284C7` | Sky Blue — task tags and status chips |
| `--accent-green` | `#10B981` | Emerald Green — checkmarks and live status dot |
| `--accent-amber` | `#F59E0B` | Amber — 5-star customer ratings |
| `--bg-page` | `#F8FAFF` | Soft, clean background canvas |
| `--bg-card` | `#FFFFFF` | Clean card background surface |
| `--text-primary` | `#0F172A` | Deep slate for headings and high-contrast text |
| `--text-secondary` | `#475569` | Readable neutral for body copy and descriptions |
| `--border-color` | `#E2E8F0` | Subtle hairline borders |

---

## 📂 Project Structure

```text
task 1/
│
├── index.html       # Semantic HTML5 document with structured landmarks
├── styles.css       # Modular CSS3 stylesheet with design tokens & media queries
└── README.md        # Documentation, feature checklist, and run instructions
```

---

## 💻 How to View Locally

You can view the project using either of the following methods:

### Option 1: Direct File Opening
Double-click [`index.html`](index.html) or open it directly in any web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Python)
From the `task 1` directory, launch a lightweight HTTP server:

```bash
# In PowerShell or Terminal
cd "c:\Users\Arman Varish\Internship\task 1"
python -m http.server 8080
```

Then navigate to:
**`http://localhost:8080`**

---

## 📱 Responsive Breakpoints

- **Desktop (> 960px)**: 3-column CSS Grid for features, steps, testimonials, and pricing; horizontal header layout.
- **Tablet (768px – 960px)**: Reflows multi-column grids into clean stacked or 2-column cards; preserved spacing.
- **Mobile (< 768px)**: Pure CSS hamburger navigation menu (checkbox hack); single-column stacked layout with full-width tap targets.

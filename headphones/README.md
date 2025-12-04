# Headphones - Responsive Landing Page

![Headphones Landing Page Preview](images/desktop-preview.jpg)

A modern, fully responsive single-page website for a premium headphone brand, built with **HTML5, CSS3 (Flexbox & Grid), and vanilla JavaScript** — no frameworks.

This project follows mobile-first design principles and replicates a high-fidelity Figma design with pixel-perfect accuracy across **desktop, tablet, and mobile (≤480px)** devices.

**Live Demo:** [https://ivyitumbi.github.io/alx_html_css/headphones]



### Features

- Fully responsive layout (mobile ≤480px, tablet, desktop)
- Smooth mobile hamburger menu with slide-in animation (pure JavaScript)
- Reusable, clean, and semantic HTML structure
- CSS custom properties (variables) for easy theming
- Custom font icons using **Holberton School Icon** set
- Pure CSS pentagons in "Our results" section (no images!)
- Subtle hover animations and interactions
- Smooth scroll behavior
- Contact form (styled, ready for backend integration)
- Optimized for performance and accessibility



### Figma Design Reference

- Original Design: [Figma Community File](https://www.figma.com/file/your-figma-link)
- Fonts used:
  - **Source Sans Pro** (Google Fonts)
  - **Spin Cycle OT** (for headings & logo)

### Project Tasks & Progression

| Task | Description                                 | Files Created                     |
|------|---------------------------------------------|-----------------------------------|
| 0    | Setup + README                              | `README.md`                       |
| 1    | Header & Hero Section                       | `0-index.html`, `0-styles.css`    |
| 2    | "What we do..." section + custom icons     | `1-index.html`, `1-styles.css`    |
| 3    | "Our results" section with pentagon stats  | `2-index.html`, `2-styles.css`    |
| 4    | Contact Form                                | `3-index.html`, `3-styles.css`    |
| 5    | Footer                                      | `4-index.html`, `4-styles.css`    |
| 6    | Replace pentagon images with pure CSS       | `6-index.html`, `6-styles.css`    |
| 7    | Add hover animations (What we do + Results) | `7-index.html`, `7-styles.css`    |
| 8    | Hamburger menu with JavaScript              | `8-index.html`, `8-styles.css`, `8-script.js` |

Final version: **`8-index.html`**, **`8-styles.css`**, **`8-script.js`**


### Key Technical Details

- **Max content width:** `1000px` (centered)
- **Mobile breakpoint:** `480px` and below
- **Hover effects:**
  - Navigation links → color: `#FF6565`
  - CTA buttons → `opacity: 0.9`
- **No external frameworks** (pure HTML/CSS/JS)
- **Mobile menu** slides from left with smooth transition
- **Pentagons** created using `clip-path` (no image files)



### File Structure
headphones/
├── index.html          → Final version (8-index.html)
├── styles.css          → Final stylesheet (8-styles.css)
├── script.js           → Hamburger menu logic (8-script.js)
├── images/             → All background & asset images
├── fonts/              → Holberton School icons + custom fonts
├── 0-index.html        → Task 1
├── 1-index.html        → Task 2
├── ...
└── README.md           → This file

### How to Run

1. Clone the repo:
   git clone https://github.com/your-username/alx_html_css.git

Navigate to the project:Bashcd alx_html_css/headphones
Open 8-index.html in your browser (or just index.html if renamed)

No build tools required!

Responsive Breakpoints

Mobile: ≤ 480px (hamburger menu active)
Tablet: 481px – 768px
Desktop: ≥ 769px
# Landing Page — VetCare Veterinary Clinic

**Author:** Akerke Zhumazhan  
**Group:** IT1-2305  
**Track:** B (Bootstrap 5)  
**Repository:** [github.com/lemssana/landing-zhumazhan](https://github.com/lemssana/landing-zhumazhan)  
**Live Site:** [lemssana.github.io/landing-zhumazhan](https://lemssana.github.io/landing-zhumazhan/)  

---

## Project Description

An updated landing page for the VetCare veterinary clinic. The project was re-designed using the Bootstrap 5 framework in a editorial minimalist style, utilizing Playfair Display typography and a structured component grid.

---

## Responsive Layout

The site is fully responsive across three primary screen width breakpoints:
* **Mobile (375 px):** The navigation menu collapses into a hamburger toggle (`Navbar Toggler`), while service cards, doctor profiles, and reviews stack into a single column (`col-12`).
* **Tablet (768 px):** Cards adaptively rearrange into 2 columns (`col-md-6`).
* **Desktop (1280 px):** Full navigation is expanded, and content cards are distributed into 3 and 4 columns (`col-lg-4`, `col-lg-3`).

### Responsive Screenshots

#### Phone — 375 px
<p align="center">
  <img src="screenshots/375.png" width="300" alt="Mobile 375px preview">
</p>

#### Tablet — 768 px
<p align="center">
  <img src="screenshots/768.png" width="500" alt="Tablet 768px preview">
</p>

#### Desktop — 1280 px
<p align="center">
  <img src="screenshots/1280.png" width="800" alt="Desktop 1280px preview">
</p>
---

## Why Bootstrap 5

I selected Bootstrap 5 to maintain a clean, semantic markup structure while leveraging a highly optimized grid system and proven UI patterns. The Flexbox grid system (`container`, `row`, `col-*`) allows precise responsive layout adjustments across standard device breakpoints without cluttering the stylesheet with repetitive `@media` rules. Utilizing native Bootstrap CSS variables enabled custom color overrides and typography hierarchy directly in `style.css` without relying on aggressive `!important` declarations. Compared to pure CSS, Bootstrap provides structured UI consistency; compared to Tailwind, it avoids utility-class bloat in HTML, keeping the code highly maintainable and readable.

---

## AI Tools & Development Workflow

* **Gemini:** Used as an intelligent code auditor to validate Bootstrap 5 grid layout syntax, verify cross-browser CSS variable implementation, and check responsive display edge cases.
* **ChatGPT:** Utilized to assist with English documentation formatting, technical text refinement, and verifying accessibility markup standards.

> **Note:** The entire structure of `index.html` and custom styles in `style.css` were written, assembled, and tested manually in VS Code. All layout choices, Bootstrap grid configurations, and CSS variable logic can be explained line by line during the project presentation.

---

## Project Structure

* `index.html` — Semantic HTML5 page layout and Bootstrap 5 component markup.
* `style.css` — Custom design overrides and CSS variables.
* `images/` — Favicon asset and high-resolution medical staff photographs.
* `screenshots/` — Responsive preview screenshots for 375px, 768px, and 1280px breakpoints.
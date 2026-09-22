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

Using Bootstrap 5 significantly accelerates adaptive web development through its built-in grid system and flexible components. The powerful Flexbox grid (`container`, `row`, `col-*`) enables seamless layout adaptation across various screen sizes without writing complex `@media` queries from scratch. The pre-built `Navbar` component with JavaScript integration resolves mobile menu handling in just a few utility classes. Although overriding default styles requires careful CSS handling, leveraging custom CSS variables allows easy design customization without relying on heavy `!important` rules. Compared to vanilla CSS, Bootstrap provides a structured foundation, while relative to Tailwind, it offers higher-level ready-to-use components.

---

## AI Tools Used

**Gemini / ChatGPT:** Assisted in optimizing the Bootstrap 5 component architecture, refining the technical rationale for the framework choice, and polishing UI styling.
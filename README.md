# Hard to Focus — Landing Page with Practical Concentration Tips

## Table of Contents
- [Project Description](#project-description)  
- [Functionality](#functionality)  
- [Technologies](#technologies)  
- [File Structure](#file-structure)  
- [Running the Project](#running-the-project)  
- [Future Enhancements](#future-enhancements)  

---

## Project Description

A single-page website called **“Hard to Focus”** helps users understand why concentrating can be difficult and offers simple techniques to improve mental focus. Built as part of Yandex Practicum coursework, the project uses pure HTML, modular CSS, and JavaScript. It supports light, dark, and automatic themes, is fully responsive, and features basic content-reveal animations.

---

## Functionality

- **Theme Switching**  
  - Three modes: “Day”, “Neon” (dark) and “Auto” (follows system preference).  
  - Selection is persisted in `localStorage`.  
- **Navigation**  
  - Static header with project title and theme-selection menu.  
- **Content Sections**  
  1. **Why It’s Hard to Focus**: cards explaining multitasking and dopamine effects.  
  2. **What Reduces Concentration**: common distractions (food, devices, etc.).  
  3. **How to Focus Better…**: five step-by-step concentration tips.  
  4. **Visual Support**: an illustration gallery under “And in Pictures?”  
- **Animations**  
  - Smooth, sequential reveal of cards and text on page load.  
- **Responsive Design**  
  - Media queries ensure optimal display on mobile, tablet, and desktop.

---

## Technologies

- **HTML5**  
  - Semantic elements (`<section>`, `<article>`, `<picture>`)  
- **CSS3**  
  - `globals.css` & `variables.css` for resets and custom properties  
  - `style.css` for core styles and layouts  
  - `dark.css` & `light.css` for theme switching via CSS variables  
  - Flexbox and Grid Layout for adaptive layouts  
- **JavaScript (ES6+)**  
  - Theme-initialization and switching logic in `script.js`  
- **BEM Methodology**  
  - Class naming follows BEM for clarity and maintainability  

---

## File Structure

```plaintext

├─ index.html
├─ fonts/
│   └─ fonts.css
├─ styles/
│   ├─ globals.css
│   ├─ variables.css
│   ├─ style.css
│   ├─ dark.css
│   └─ light.css
├─ scripts/
│   └─ script.js
└─ images/
    ├─ favicon.svg
    ├─ favicon.ico
    ├─ mobile-icon.png
    └─ PNG illustrations for the “in pictures” section


Future Enhancements
Integrate a built-in Pomodoro timer with customizable session lengths

Expand the tips section with video demonstrations of focus exercises

Optimize image loading (lazy-loading, WebP format)

Improve accessibility (ARIA attributes, contrast ratios)

Store session progress and statistics in localStorage or via a simple API

Automate deployment using GitHub Actions

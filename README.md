# 🎨 Week 2: CSS Fundamentals, Box Model Mastery & Responsive Layouts

Welcome to **Week 2** of the Web Development Program at IYF Weekend Academy (Season 12). 

Building directly upon the clean, accessible semantic HTML foundation established in [Week 1](https://github.com/HellenWamuciiNjue/iyf-s12-week-01-HellenWamuciiNjue), this repository introduces modern CSS styling, mobile-first design systems, Flexbox navigation, and 3-tier CSS Grid layout systems.

---

## 🚀 Live Demo

🔗 **[View the Week 2 Live Portfolio](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/)**

### 🌐 Quick Page Navigation
* [🏠 Home Page](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/index.html)
* [👤 About Me](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/about.html)
* [📂 Projects Showcase](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/projects.html)
* [📞 Contact Form](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/contact.html)
* [📦 Box Model Practice Sandbox](https://hellenwamuciinjue.github.io/iyf-s12-week-02-HellenWamuciiNjue/box-model-practice.html)

---

## 📋 Table of Contents
* [Live Demo](#-live-demo)
* [Architectural Evolution: Week 1 vs. Week 2](#-architectural-evolution-week-1-vs-week-2)
* [Professional Background & Engineering Origin Stories](#-professional-background--engineering-origin-stories)
* [Key Features & Deliverables](#-key-features--deliverables)
* [Project Directory Structure](#-project-directory-structure)
* [CSS Architecture & Design Token System](#-css-architecture--design-token-system)
* [Accessibility & Focus Management](#-accessibility--focus-management)
* [Daily Engineering Challenges](#-daily-engineering-challenges)
* [Lessons Learned](#-lessons-learned)
* [Author & Contact](#-author--contact)

---

## 🔄 Architectural Evolution: Week 1 vs. Week 2

| Feature / Domain | Week 1 (Semantic Foundations) | Week 2 (CSS Layout & Responsiveness) |
| :--- | :--- | :--- |
| **Styling** | Native browser fallback (Unstyled) | Modern `styles.css` with CSS Custom Properties |
| **Navigation** | Unstyled vertical list (`<ul>`/`<li>`) | Horizontal Flexbox container (`display: flex`) |
| **Projects Showcase** | Sequential block elements | Responsive CSS Grid (1-col mobile, 2-col tablet, 3-col desktop) |
| **Box Model** | Default browser margins/padding | Universal `box-sizing: border-box` reset & visualization module |
| **Accessibility** | ARIA landmarks & semantic tags | Persistent focus outlines & interactive hover states |

---

## 💼 Professional Background & Engineering Origin Stories

As a **Media Analyst** and operations professional transitioning into full-stack software engineering, my projects solve real-world complexities:

* **Media Analysis & Team Leadership (Ipsos):** Leading high-performing operational teams to analyze and classify complex data streams from TV, radio, and digital news sources under strict daily processing routines.
* **Entrepreneurship at Nitas Fashion:** Co-founding alongside my sister during demanding night shifts, growing Nitas Fashion from a personal side hustle into a bustling family enterprise featuring multiple physical salons and a thriving digital commerce footprint.
* **Engineering Solutions (*Nitas POS*, *LeaveDesk*, *WorkTap*):** Building automated retail inventory logic, corporate leave-management administrative workflows, and secure project-driven workspace architecture.

---

## ✨ Key Features & Deliverables

### 1. Flexbox Header & Navigation Bar
- Unified `<header>` containing branding and a responsive navigation menu.
- Flexbox layout utilizing `justify-content: space-between` and `align-items: center` for precise spatial balance.
- Clear hover and keyboard focus indicators across all active routes.

### 2. Responsive CSS Grid Projects Gallery
- Custom CSS Grid implementation on `projects.html` dynamically adapting across viewports:
  - **Mobile (Phone):** 1 Column (`< 768px`)
  - **Tablet:** 2 Columns (`768px - 1023px`)
  - **Desktop:** 3 Columns (`≥ 1024px`)
- Standardized card structures highlighting real-world engineering projects: **Nitas POS**, **LeaveDesk**, and **WorkTap**.

### 3. Interactive Box Model Sandbox
- Dedicated sandbox page (`box-model-practice.html`) visualizing the concentric layers of the CSS Box Model: *Margin*, *Border*, *Padding*, and *Content Core*.

---

## 📁 Project Directory Structure

```text
iyf-s12-week-02-HellenWamuciiNjue/
├── daily-challenges/
│   ├── day-1.html
│   ├── day-2.html
│   ├── day-3.html
│   ├── day-4.html
│   └── day-5.html
├── images/
│   ├── devtools-screenshot.png
│   ├── hellen_njue_profile.png
│   ├── nitas-ankara.png
│   ├── nitas-fancy-dresses.jpg
│   ├── nitas-footwear.jpeg
│   └── nitas-hairstyle.jpeg
├── about.html
├── box-model-practice.html
├── contact.html
├── index.html
├── projects.html
├── styles.css
└── README.md

## 🎨 CSS Architecture & Design Token System

The repository utilizes clean, maintenance-friendly CSS custom properties (variables) defined in the `:root` pseudo-class:

```css
/* Core Reset & Design Tokens */
*, *::before, *::after {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

:root {
    --primary-color: #0d1b2a;
    --accent-color: #0056b3;
    --background-light: #f8f9fa;
    --text-dark: #1f2937;
    --font-heading: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    --font-body: system-ui, -apple-system, sans-serif;
}

## ♿ Accessibility & Focus Management

Adhering strictly to WCAG principles and the course rubric:
- **Focus Outlines Intact:** Universal focus rules ensure keyboard users (`Tab` navigation) always have visible indicator rings.
- **Color Contrast:** All text and background variable pairings meet or exceed AA standards for readability.
- **Active Page Indicators:** Uses semantic `aria-current="page"` attributes to assist assistive technology users during route transitions.

---

## 🛠️ Daily Engineering Challenges

The `daily-challenges/` directory documents targeted daily practical exercises covering core CSS layout techniques:
- **Day 1:** Visualizing the Box Model through concentric margin/border/padding layers.
- **Day 2:** Exploring block vs. inline element constraints and element spacing behaviors.
- **Day 3:** Building custom Flexbox layouts and alignment structures.
- **Day 4:** Constructing responsive CSS Grid gallery structures.
- **Day 5:** Applying CSS variables and accessibility focus state management across dynamic viewports.

---

## 📝 Lessons Learned

1. **Mobile-First Mental Shift:** Designing base CSS rules for mobile devices first prevents complex CSS media query overrides later in the development process.
2. **Flexbox vs. CSS Grid Separation of Concerns:** Flexbox excels at 1-dimensional component alignment (e.g., navigation bars, form control rows), while CSS Grid handles 2-dimensional page layouts (e.g., card galleries).
3. **The Power of `border-box`:** Setting `box-sizing: border-box` across all elements makes element sizing predictable by absorbing padding and border width into the overall element dimensions.

---

## 👩‍💻 Author & Contact

**Hellen Wamucii Njue**  
*Media Analyst & Full-Stack Web Development Student*  
- IYF Weekend Academy — Season 12  
- **GitHub:** [@HellenWamuciiNjue](https://github.com/HellenWamuciiNjue)

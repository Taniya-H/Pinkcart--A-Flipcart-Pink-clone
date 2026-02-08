# 🎀 Pinkcart

A fully responsive, aesthetic-focused e-commerce frontend built with **pure HTML & CSS**.

This project demonstrates how to build a modern, functional shopping interface 
without relying on JavaScript frameworks or libraries. The goal was to master the 
fundamentals of layout, responsiveness, and CSS animations.

Inspired by the layout and usability of **Flipkart**, but reimagined with a 
distinct "soft aesthetic" theme.

---

## 🚀 Features

### 📱 Responsive Design
- Adapts seamlessly from **mobile (iPhone SE/Pixel)** to desktop screens.
- Uses a mobile-first approach with custom media queries to ensure the 
  navigation, hero section, and product grids stack beautifully on smaller devices.

### ✨ Pure CSS Animations (No JS Required)
- **Infinite Hero Slider:** The sliding banner effect (featuring the purse collection) 
  is achieved entirely using CSS Keyframes (`@keyframes`) and `transform: translateX()`. 
  It loops automatically—zero JavaScript involved.
- **Sticky Navigation:** The header remains pinned to the top of the viewport for 
  easy access, using `position: sticky`.

### 🎨 Aesthetic Design System
- **Curated Theme:** A cohesive Pink/Mauve color palette with soft borders and rounded corners.
- **Typography:** Custom font styling using **Bitcount Single** for a unique, 
  retro-digital store vibe.
- **Layout:** Clean, consistent spacing using CSS Flexbox and utility classes.

### 🛍️ Organized Product Sections
- Distinct categories for **Plushies**, **Jewellery**, and **Dresses**.
- Product cards are structured with consistent imagery, pricing, and "Grab Now" 
  call-to-action buttons.

---

## 🛠️ Tech Stack

- **HTML5:** Semantic structure (Header, Nav, Main, Footer) for better accessibility and SEO.
- **CSS3:**
  - **Flexbox:** Used extensively for aligning navigation items and product grids.
  - **CSS Grid & Media Queries:** Handles the responsive layout shifts.
  - **Keyframe Animations:** Powers the auto-sliding banner.
  - **Variables & Utilities:** Reusable classes for spacing and centering to keep the codebase clean.

---

## 💡 How the CSS Slider Works

Instead of a heavy JavaScript carousel plugin, **Pinkcart** uses a lightweight CSS technique:
1. A **container** with `overflow: hidden` acts as a "window."
2. The **banner image** moves horizontally using `animation` and `transform: translateX()`.
3. The animation is set to `infinite`, creating a continuous, smooth sliding effect 
   that loops automatically.

---

## 📂 Project Structure

```bash
Pinkcart/
├── index.html          # Main storefront structure
├── css/
│   ├── style.css       # Global styles & layout
│   ├── responsive.css  # Mobile/Tablet breakpoints
│   ├── animation.css   # Keyframe animations (slider logic)
│   └── utils.css       # Reusable utility classes (fonts, buttons, centering)
└── img/                # Product images & assets
'''

###Built with ❤️ by Taniya ;)

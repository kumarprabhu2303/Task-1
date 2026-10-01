# 🚀 Responsive Landing Page Challenge

A clean, semantic, and modern landing page built from scratch using HTML5 and modern CSS features (Flexbox, Grid, and Custom Properties). This project serves as a foundational frontend assessment to demonstrate responsive web design principles.

## 📋 Project Specifications

*   **Objective:** Build a structured layout featuring a sticky header, interactive hero section, responsive column transitions, and a structured footer.
*   **Design Strategy:** Desktop-optimized layout scaling cleanly to mobile viewports using CSS media breakpoints.
*   **Key Techniques:** CSS resetting, root variables, Flexbox layouts, 2D Grid allocation, and viewport scaling elements.

---

## 📂 Project Architecture

```text
├── index.html       # Structural markup containing semantic HTML5 wrappers
├── style.css        # Layout engines, system resetting, variable configuration, and queries
└── README.md        # Technical execution summary and documentation
```

---

## 🛠️ Step-by-Step Implementation Guide

Follow these exact steps to load, preview, and review the project architecture locally:

### 1. Set Up Your Workspace
1. Download and install **[Visual Studio Code](https://visualstudio.com)**.
2. Install the **Live Server** extension by Ritwick Dey within the VS Code Extensions marketplace.
3. Create a clean root directory on your machine and place the `index.html` and `style.css` files inside it.

### 2. Launching the Local Preview Server
1. Open your workspace directory using VS Code.
2. Open the `index.html` file in your editor.
3. Click the **"Go Live"** utility bar item in the bottom right-hand corner of the workspace screen, or right-click within `index.html` and select **Open with Live Server**.
4. A browser window will automatically launch at your local hosting loop address (`http://127.0.0.1:5500`).

### 3. Reviewing System Responsiveness
1. Right-click anywhere on the live window page context and select **Inspect** to launch the Chrome DevTools interface panel.
2. Toggle the **Device Toolbar Device Emulation** panel wrapper.
3. Click and drag the viewport frame border below the `768px` boundary mark to see the layout break and adapt to mobile stacking logic.

---

## 🚀 Key Architectural Concepts Used

*   **Semantic Elements:** Replaced generic layout container tags (`<div>`) with explicit document structure nodes including `<header>`, `<main>`, `<section>`, and `<footer>` tags to ensure accessibility and clear SEO mapping rules.
*   **Modern Layout Engines:** Used **Flexbox** on horizontal component structures (like navigation links and footer alignment items) and **CSS Grid** to calculate complex two-dimensional distributions (like the 2-column hero split grid layout).
*   **CSS Variable Tokens:** Isolated global design elements inside the `:root` system wrapper to simplify sweeping property changes like accent color transformations (`--primary-color`).
*   **Fluid Viewport Engineering:** Used `box-sizing: border-box` to handle item padding safely without breaking structural element dimensions or layout alignments.

---

# Agent Instruction: Generate "Fire & Ice" Revolut Landing Page

**Objective:** Act as an expert Front-End Developer. Create a modern, responsive, single-page static website (HTML and CSS) in the current working directory, ready to be published on GitHub Pages.

## 1. Design System Implementation (Strict Adherence)
Read the provided `DESIGN.md` file in the workspace and apply the "Fire & Ice" aesthetic strictly:
* **Colors:** Use `--bg-primary` (`#0A0A0B`) for the main background and `--bg-secondary` (`#141416`) for surfaces.
* **Gradients & Accents:** Use the Electric Orange (`#FF6B00`) to Electric Cyan (`#00E5FF`) gradient for primary interactive elements, glows, and text highlights.
* **Typography:** Import Google Fonts. Use 'Outfit' (weights 600-800) for all headings (H1, H2, H3). Use 'Inter' (line-height 1.6 - 1.8, color `#A1A1AA`) for body paragraphs.
* **Components & Effects:** Build "Glassmorphism" cards using `background: rgba(20, 20, 22, 0.45); backdrop-filter: blur(16px);` and a 1px solid border of `rgba(255, 255, 255, 0.05)`. Do not use harsh solid box-shadows; instead, use subtle, low-opacity colored glows (e.g., `rgba(255, 81, 47, 0.15)`).

## 2. Content Injection
Read the provided `Project Display Text.md` file. Insert the exact Hungarian text into the HTML structure as follows:
* **Hero Section:** Display the H1 and introductory paragraph. Include a subtle background glow orb effect behind the text to mimic the "Fire & Ice" lighting.
* **Security Features:** Render the "100%-os védelem" section. Place the 3 bullet points inside a CSS Grid containing 3 glassmorphism cards.
* **Additional Benefits:** Render the "Miért imádjuk..." section as a clean, highly legible list or secondary grid.
* **CTA Section:** Create a highly visible, pill-shaped Call-to-Action button using the Fire & Ice gradient and a smooth pulse/hover animation (`transform: translateY(-2px)`). Leave the `href` attribute empty for now. 
* **Footer:** Place the legal disclaimer ("Jogi nyilatkozat...") at the bottom in a small, muted font color.

## 3. Output Requirements
* Generate fully semantic and clean `index.html` and `style.css` files.
* Use standard CSS custom properties (variables) at the `:root` level matching the colors from `DESIGN.md`.
* Ensure the layout is fully responsive using a mobile-first approach.
* Once the files are successfully written, start a local live server or open the browser-in-the-loop so I can visually inspect the result.
# Theema
**The Ultimate Dual-Theme Visual Architect**

## Introduction
Designing a single theme is hard; designing two contrasting themes (like Light and Dark mode) that feel cohesive and functionally sound is an architectural challenge. **Theema** is a comprehensive CSS theme designer that allows you to visually build, test, and export two complete theme sets simultaneously. 

By providing a high-fidelity "sandbox," Theema ensures that every design nuance—from accent colors to line heights—works perfectly before you write a single line of application code. What used to take hours of manual CSS tweaking now takes seconds of visual refinement.

Try the Live Project Here: <br>
**https://turnerworks.uk/portfolio/theema/index.html**
<br>

<img height="905" alt="image" src="https://github.com/user-attachments/assets/3a87a7b2-522c-41be-90c4-5a3673a584a9" />

---

## 🎨 Beyond Just Colors
Most theme generators stop at "Background" and "Text." **Theema** goes deeper, supporting **30 different color attributes** alongside critical layout and stylistic variables:
*   **Atmospherics:** Custom box shadows and backdrop blurs for depth.
*   **Typography:** Fine-tune font sizes and line heights across the entire theme.
*   **Spacing:** Control padding and layout density globally.
*   **UI Components:** Dedicated attributes for buttons, inputs, cards, and navigation elements.

---

## 🚀 Key Features

### 🖼️ The Live Canvas
The heart of Theema is a **Full-Scale Dummy App Window**. This interactive canvas contains every necessary UI control—headers, sidebars, data tables, modals, and buttons. 
*   **Instant Toggle:** Use the built-in toggle to flip between "Theme A" and "Theme B" instantly.
*   **Stress Testing:** See exactly how your dark mode shadows look against deep surfaces, or how your "Alert" red interacts with your light mode accent.

### ⚡ Rapid Prototyping
Theema allows you to see the "Full Picture" up front. By confirming that your two themes work together in a realistic environment, you avoid the common pitfall of discovering color collisions or unreadable text halfway through project development.

### 🛠️ One-Click Integration
Theema doesn't just design; it delivers. When you’re satisfied with your pair of themes, it exports:
*   **CSS Root Variables:** A comprehensive list of variables for both themes.
*   **Minimalist JS Toggle:** A single, lightweight JavaScript function that handles the logic for switching between your two created themes.

---

## 📥 Getting Started

1.  **Design Theme A:** Use the visual sliders and pickers to define your primary look (e.g., Light Mode).
2.  **Design Theme B:** Switch the toggle and define your secondary look (e.g., Dark Mode).
3.  **Refine Layout:** Adjust global padding, font sizes, and blurs to ensure the UI feels consistent across both.
4.  **Export:** Copy the CSS and the small JS snippet into your project.

---

## 📂 Implementation Example
Theema provides everything you need to get running in seconds:
```css
/* CSS Export */
[data-theme='light'] {
  --bg-surface: #ffffff;
  --text-main: #1a1a1a;
  --shadow-sm: 0 2px 4px rgba(0,0,0,0.1);
  /* ... 30+ more variables */
}

[data-theme='dark'] {
  --bg-surface: #121212;
  --text-main: #f5f5f5;
  --shadow-sm: 0 4px 8px rgba(0,0,0,0.5);
}
```


find more: <br>
https://turnerworks.uk <br>
https://github.com/turnerworks <br>
<Br>




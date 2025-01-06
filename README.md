# Responsive Website Final Project

The goal of this project is to create a responsive website that adjusts to screen sizes and user preferences. The website must include views for mobile, tablet, and large screens while supporting user settings for `prefers-reduced-motion` and `prefers-color-scheme`.

---

## **Project Requirements**

### **General**
- Replace all **images** from the starter code with new ones and include proper `alt` text.
- Replace the content in all `<p>` tags from the starter code.
- Validate the HTML using the [W3C Markup Validation Service Tool](https://validator.w3.org/).
- Validate accessibility using the [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/).

---

### **Mobile View**
- **Default (mobile-first)**: No media queries required.
- Layout:
  - One-column grid layout.
  - `gap` of `10px` between rows and columns.

---

### **Tablet View**
- Triggered at `min-width: 772px`.
- Avoid repeating unnecessary rules.
- Layout:
  - Two-column grid layout.
  - Apply a circular shape to figures using `border-radius`.
  - Set the last figure to span both columns.

---

### **Large Screen View**
- Triggered at `min-width: 992px`.
- Avoid repeating unnecessary rules.
- Layout:
  - Every third figure spans both columns.
  - Remove the `border-radius` from all figures.

---

### **Prefers-Reduced-Motion**
- Remove smooth scrolling behavior when users enable `prefers-reduced-motion`.

---

### **Dark Color Scheme**
- Default color scheme: **light**.
- When `prefers-color-scheme: dark`:
  - Change figure `background-color` to a dark color.
  - Change figure `font-color` to a lighter (yellowish) color.
  - Change figure `border-color` to black.

---

## **Implementation Steps**

### **Setup**
1. Download the starter code from: [Final Project Starter Code](https://intro-webdesign.com/v3/responsive_repo/week4/finalProject.zip).
2. Open the files in your preferred code editor.
3. Replace all images and add appropriate `alt` text.
4. Replace all paragraph text.

---

### **Validation**
1. Validate the HTML using the [W3 Validator](https://validator.w3.org/).
2. Validate accessibility using the [WAVE Tool](https://wave.webaim.org/).

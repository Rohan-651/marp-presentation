---
marp: true
title: Product Documentation Presentation
description: Technical documentation deck built with Marp
paginate: true
theme: custom-theme
class: lead
---

<!--
Custom Marp Theme (kept inline for simplicity).
You can extract this into `themes/custom-theme.css` if you prefer.
-->
<style>
/* Base */
section {
  font-family: "Segoe UI", Tahoma, sans-serif;
  background-color: var(--color-background, #fafafa);
  color: var(--color-foreground, #111);
}

/* Headings */
h1, h2, h3 {
  color: #1a237e;
  margin-bottom: 0.35em;
}

/* Footer area (we also use paginate: true so Marp will show page numbers) */
footer {
  color: #555;
  font-size: 0.85rem;
  text-align: right;
  padding: 8px 12px;
}

/* Highlight */
section strong { color: #004d40; }

/* Custom theme variables */
:root {
  --color-background: #ffffff;
  --color-foreground: #111;
  --color-highlight: #1a237e;
}

/* Make the contact email visually prominent on the dedicated slide */
.email-visible {
  font-size: 2rem;
  font-weight: 700;
  color: var(--color-highlight);
  margin-top: 1.2rem;
}
</style>

<!-- Title Slide -->
# 🧩 Product Documentation  
### Using Marp for Maintainable, Version-Controlled Presentations  
**Contact:** 22f2001391@ds.study.iitm.ac.in

<footer>1</footer>

---

# Why Marp?

- Markdown-based presentations  
- Works well with GitHub and CI/CD  
- Export to **PDF**, **HTML**, **PPTX**  
- Easy theming and automation

<footer>2</footer>

---

<!-- Background image slide -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=60)

# Documentation Workflow

- Author content in Markdown  
- Version control with Git  
- Auto-render using Marp CLI or GitHub Actions  
- Embed code, images, diagrams

<footer>3</footer>

---

# Custom Styling Example

This slide uses:

- Custom CSS theme (inline here)  
- Marp directives (`marp: true`, `paginate: true`, `theme: custom-theme`)  
- Styled text such as **bold**, *italics*, and `monospace`

<footer>4</footer>

---

# Mathematical Example

Algorithmic recurrence for Merge Sort:

\[
T(n) = 2T\left(\frac{n}{2}\right) + n
\]

Therefore, time complexity:

\[
T(n) = O(n \log n)
\]

<footer>5</footer>

---

# Contact

For documentation support:  
📧 **22f2001391@ds.study.iitm.ac.in**

<div class="email-visible">22f2001391@ds.study.iitm.ac.in</div>

<footer>6</footer>

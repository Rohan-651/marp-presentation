---
marp: true
title: Product Documentation Presentation
description: Technical documentation deck built with Marp
paginate: true
theme: custom-theme
class: lead
---

<!--
Custom Marp Theme
Save this theme inside the same file or extract into a separate CSS in /themes
-->
<style>
section {
  font-family: "Segoe UI", sans-serif;
}

h1, h2, h3 {
  color: #1a237e;
}

footer {
  color: #555;
  font-size: 0.8rem;
  text-align: right;
  padding: 10px;
}

section strong {
  color: #004d40;
}

/* Custom theme override */
:root {
  --color-background: #fafafa;
  --color-foreground: #111;
  --color-highlight: #1a237e;
}
</style>

<!-- Title Slide -->
# 🧩 Product Documentation  
### Using Marp for Maintainable, Version-Controlled Presentations  
**Contact:** 22f2001391@ds.study.iitm.ac.in

<footer>Slide 1</footer>

---

# Why Marp?

- Markdown-based presentations  
- Works with GitHub, VSCode, CI/CD  
- Export to **PDF**, **HTML**, **PPTX**  
- Easy theming and automation

<footer>Slide 2</footer>

---

<!-- Background image slide -->
![bg](https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1200&q=60)

# Documentation Workflow

- Author content in Markdown  
- Version control with Git  
- Auto-render using Marp CLI  
- Embed code, images, diagrams

<footer>Slide 3</footer>

---

# Custom Styling Example

This slide uses:

- Custom CSS theme  
- Marp directives (`marp: true`, `paginate: true`, `theme:`)  
- Styled text such as **bold**, *italics*, and `monospace`

<footer>Slide 4</footer>

---

# Mathematical Example

Algorithmic complexity for merge sort:

\[
T(n) = 2T\left(\frac{n}{2}\right) + n
\]

Time complexity:

\[
O(n \log n)
\]

<footer>Slide 5</footer>

---

# Contact

For documentation support:  
📧 **22f2001391@ds.study.iitm.ac.in**

<footer>Slide 6</footer>

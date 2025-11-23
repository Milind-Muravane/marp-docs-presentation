---
marp: true
theme: iitm-docs
paginate: true
footer: "Page $page / $total – Product Documentation with Marp"
---

<!-- _class: lead -->

# Product Documentation with Marp

**Role:** Technical Writer @ Software Company  
**Author:** Milind Muravane  
**Email:** 24f2000871@ds.study.iitm.ac.in

Using Marp + Markdown to create version-controlled, multi-format product docs.

---

<!-- _class: highlight-list -->

# Why Marp for Product Documentation?

- Single source of truth in Markdown  
- Version control with Git (branches, PRs, reviews)  
- Export to:
  - PDF  
  - HTML  
  - PowerPoint (PPTX)
- Easy to automate in CI/CD

---

# Project Structure

A typical repo layout:

```text
docs/
  ├─ slides.md          # This Marp deck
  ├─ theme-iitm-docs.css (optional)
  └─ images/
     └─ background.jpg
```

---

# Algorithmic Complexity Example

Inline math: $\mathcal{O}(n \log n)$  

Block math:

$$
T(n) =
\begin{cases}
\mathcal{O}(1), & n \le 1 \\
\mathcal{O}(n \log n), & n > 1
\end{cases}
$$

---

<!--
_backgroundImage: url('images/background.jpg')
_class: bg-cover
-->

# Background Slide

This slide uses a full background image.

---

```css
/* @theme iitm-docs */

section {
  background-color: #0b1020;
  color: #ffffff;
  font-family: Arial, sans-serif;
}

section.lead {
  background: linear-gradient(#1e293b, #0f172a);
  padding: 3rem;
}

section.highlight-list ul {
  color: #d1d5db;
  font-size: 1.1rem;
}

section.bg-cover {
  background-size: cover;
  background-position: center;
}
```

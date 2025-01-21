# CSS Grid Layout Guide

Welcome to the **CSS Grid Layout Guide**! This repository provides an overview of CSS Grid, its key parts, and terminology. CSS Grid is a powerful two-dimensional layout system that enables developers to create responsive and flexible web designs.

## Table of Contents

- [CSS Grid Layout Guide](#css-grid-layout-guide)
  - [Table of Contents](#table-of-contents)
  - [What is CSS Grid?](#what-is-css-grid)
  - [Key Terminology](#key-terminology)
    - [Visual Representation](#visual-representation)

---

## What is CSS Grid?

CSS Grid is a layout system in CSS that allows you to create complex, responsive designs by defining rows and columns in a grid structure. It can be used for major page layouts or small interface elements.

Key features include:

- Fixed and flexible track sizes using units like `px`, `%`, or `fr`.
- Precise item placement using grid lines or areas.
- Automatic creation of additional tracks as needed.
- Alignment control for items and the entire grid.
- Overlapping content management using `z-index`[2][5].

---

## Key Terminology

Understanding the core components of CSS Grid is essential:

| **Term**           | **Definition**                                                               |
| ------------------ | ---------------------------------------------------------------------------- |
| **Grid Container** | The parent element where the grid layout is applied (`display: grid`).       |
| **Grid Item**      | Direct child elements of the grid container.                                 |
| **Grid Line**      | Horizontal or vertical lines dividing the grid into rows and columns.        |
| **Grid Track**     | Space between two adjacent grid lines (a row or column).                     |
| **Grid Cell**      | The smallest unit in the grid where a single row and column intersect.       |
| **Grid Area**      | A rectangular space defined by four grid lines (start/end for rows/columns). |

### Visual Representation

`Here’s how these terms relate to each other:

.container {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 10px;
}

.item {
background-color: lightblue;
text-align: center;
padding: 20px;
}`

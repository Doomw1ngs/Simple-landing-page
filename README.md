# Naturalism: Landing Page

A responsive-minded, single-page landing website built with plain **HTML5** and **CSS3**. The project is a practice build focused on page layout with Flexbox, section-based structure, and a clean visual hierarchy: header, feature cards, testimonial, call to action, and footer.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Page Sections](#page-sections)
- [Getting Started](#getting-started)
- [Design Details](#design-details)
- [What I Learned](#what-i-learned)
- [Known Issues & Future Improvements](#known-issues--future-improvements)
- [Author](#author)

## Overview

"Naturalism" is a nature-themed landing page template. It demonstrates how to build a multi-section marketing page from scratch without any frameworks or libraries. All content is placeholder text (Lorem ipsum), so the page works as a reusable starting template.

## Technologies Used

| Technology | Purpose |
| --- | --- |
| **HTML5** | Semantic page structure (`section`, `footer`, `button`, `img`) |
| **CSS3** | All styling, layout, colors, and typography |
| **CSS Flexbox** | Navigation bar, header layout, card row, CTA box, sticky footer |
| **Google Fonts (Roboto)** | Typography, imported via `@import` in `style.css` |

No JavaScript, frameworks, or build tools are required.

## Project Structure

```
project-folder/
├── index.html        # Page markup
├── style.css         # All styles
└── images/
    ├── main-image.jpg
    ├── info-image-1.jpg
    ├── info-image-2.jpg
    ├── info-image-3.jpg
    └── info-image-4.jpg
```

## Page Sections

1. **Header / Hero**: Navigation bar with logo and three links, a headline, a short description, a "Sign Up" button, and a main image on the right.
2. **Info Section**: A title followed by four image cards (rounded images with a cyan border and a short caption), laid out in a row.
3. **Testimonial**: A centered, italic customer quote with the author's name aligned to the right.
4. **Call to Action (CTA)**: A blue box with a title, a subtitle, and an outlined "Sign Up" button.
5. **Footer**: A black bar with a copyright notice, pushed to the bottom of the page even when content is short.

## Getting Started

### Prerequisites

Only a modern web browser (Chrome, Firefox, Edge, Safari).

### Run Locally

1. Clone or download this repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Make sure an `images/` folder exists next to `index.html` containing the five images listed above.
3. Open `index.html` in your browser (double-click it, or use an extension like VS Code's *Live Server*).

## Design Details

**Color palette**

| Usage | Color |
| --- | --- |
| Page background | `azure` |
| Header background | `rgb(17, 17, 99)` (dark navy) |
| Accent (buttons, image borders) | `cyan` |
| Testimonial background | `#5a59af` |
| Testimonial text | `blanchedalmond` |
| CTA box | `#3b82f6` |
| Footer | `black` |

**Typography:** Roboto (weights 100–900, including italics), with `sans-serif` fallback.

**CSS techniques used**

- Global reset (`margin: 0; padding: 0; box-sizing: border-box`)
- Flexbox for horizontal and vertical alignment (`justify-content`, `align-items`, `gap`, `flex: 1`)
- Sticky footer using `min-height: 100vh` on `body` with `margin-top: auto` on the footer
- `object-fit: cover` so images keep their proportions
- Child selectors (`.picture > img`) and grouped styling by section

## What I Learned

- Structuring a page into clear, commented sections
- Building layouts with Flexbox instead of floats or tables
- Organizing CSS to mirror the HTML order
- Creating a sticky footer without JavaScript
- Using Google Fonts in a plain CSS project

## Known Issues & Future Improvements

- [ ] Add **responsive design** with media queries (the layout uses fixed paddings and a row of cards that won't fit on small screens)
- [ ] Add meaningful `alt` text to all images for accessibility
- [ ] Use semantic tags like `<header>`, `<nav>`, `<main>`, and `<blockquote>`
- [ ] Replace `<div>` headings with real heading tags (`<h1>`, `<h2>`) for SEO
- [ ] Add hover and focus states to links and buttons
- [ ] Link the "Sign Up" buttons to a real page or form

## Author

**Fotis Gountios**

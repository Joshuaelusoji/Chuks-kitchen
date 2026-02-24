# Chuks Kitchen

Chuks Kitchen is a responsive static landing page built using HTML5 and CSS3.  
The project focuses on precise UI replication using image assets and controlled responsive behavior through media queries.

---

## Overview

This project implements a food brand landing page using separate image assets for desktop and mobile views.  
The layout ensures proper centering, scaling, and overflow control without using JavaScript or external frameworks.

---

## Tech Stack

- HTML5
- CSS3
  - Media Queries
  - max-width
  - Object-fit
  - Object-position

---

## Responsive Strategy

The project follows a **desktop-first approach**.

### Breakpoint

- Mobile: `max-width: 480px`

At screen widths of 480px and below:
- Desktop images are hidden
- Mobile-specific images are displayed

This guarantees proper content visibility across devices.

---

## Image Scaling & Overflow Control

To maintain layout integrity and prevent horizontal scrolling:

- `max-width: 100%` is applied to images  
  → Ensures images never exceed their container width  
  → Keeps images centered within the viewport  

- `height: auto` maintains aspect ratio  

- `object-fit: cover` preserves visual proportion  

- `object-position: center` ensures correct alignment  

- Horizontal overflow is controlled to prevent unwanted scrollbars  

This approach ensures:
- No horizontal scrolling on desktop
- Proper scaling on smaller screens
- Clean visual presentation

---

## Project Structure

Chuks-Kitchen/
│
├── assets/
│   └── images/
│
├── index.html
└── README.md

---

## Key Implementation Details

- Semantic HTML5 structure
- Desktop-first media query logic
- Responsive image switching
- Overflow management using CSS
- No JavaScript dependency
- Lightweight and fast-loading static page

---

## How to Run

1. Clone the repository

   git clone https://github.com/joshuaelusoji/chuks-kitchen.git

2. Open `index.html` in your browser

No build tools required.

---

## Future Improvements

- Replace image-based layout with structured layout using Flexbox or CSS Grid
- Convert images to modern formats such as WebP
- Add interactive sections using JavaScript
- Deploy to GitHub Pages or Netlify

---

## Author

Joshua Elusoji  

Frontend Developer

# Assignment #2: Advanced CSS (Flexbox & Grid)

## Student Information
 Name:Van Alexander
 Group:SE-2540
Date:27.09.2026

---

## Project Overview
This project demonstrates all 4 tasks for Assignment #2:
 Task 0: Navigation Bar using Flexbox
 Task 1: Card Row using Flexbox
 Task 2: Grid Layout with Grid Areas
 Task 3: Image Gallery using CSS Grid
 Task 4: Portfolio Page combining Flexbox & Grid

---

## Task 0: Navigation Bar ✅
**Flexbox Layout**
 Logo on left, navigation links on right
 Uses `display: flex` with `justify-content: space-between`
 Vertical alignment with `align-items: center`

---

## Task 1: Card Row ✅
**Flexbox Layout**
 3 cards in a row using `display: flex`
 Each card has image, title, description, and button
 Cards have equal width (280px)
 Hover effect: box-shadow increases

---

## Task 2: Grid Layout ✅
**CSS Grid Areas**
 Grid container with header, sidebar, main content, footer
 Header spans full width (grid-column: 1/-1)
 Sidebar: 200px fixed width on left
 Main content on right
 Footer spans full width at bottom

Grid Setup:
```css
grid-template-columns: 200px 1fr;
grid-template-rows: auto 1fr auto;
```

---

## Task 3: Image Gallery ✅
CSS Grid
 9 images in 3x3 grid
 Uses `grid-template-columns: repeat(3, 1fr)`
 Hover effect: caption slides up from bottom
 Images with emoji placeholders

---

## Task 4: Portfolio Page ✅
Flexbox + Grid Combined
 Main grid: projects (left) + sidebar (right)
Projects use flexbox for card layout
 Each project has image on left, content on right
 Sidebar with About information

---

## Responsive Design
 Mobile breakpoint at 768px
 Flexbox items stack vertically on mobile
 Grid changes to single column on mobile
 Gallery becomes 1 column on mobile
 Portfolio sidebar moves below projects

---

## Code Structure
- Simple and clean HTML
- Minimal CSS (under 200 lines)
- No external libraries
- Pure CSS Flexbox & Grid

---

## How to Use
1. Save file as `index.html`
2. Open in any web browser
3. Test hover effects on cards and gallery
4. Resize browser to test responsive design

---

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## Requirements Met
✅ Flexbox used for navbar, cards, and portfolio
✅ CSS Grid used for layout and gallery
✅ Grid areas properly assigned (header, sidebar, main, footer)
✅ Image gallery with 9+ images
✅ Hover effects on cards and gallery
✅ Responsive design for mobile
✅ All code in single HTML file
✅ No external libraries

---

## Design Colors
- Primary: #667eea (Purple)
- Secondary: #333 (Dark)
- Background: #f5f5f5 (Light gray)
- White: #fff

---

**All tasks completed successfully! ✓**
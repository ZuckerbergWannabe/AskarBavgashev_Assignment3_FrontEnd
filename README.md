# Assignment #3 — Responsive Web Design

**Name:** Askar Bavgashev  
**Group:** SE-2540

## Objective

This project demonstrates responsive web design using CSS Media Queries and the Bootstrap Grid system.

## Technologies

- HTML5
- CSS3
- CSS Media Queries
- Bootstrap 5.3
- Bootstrap 12-column Grid
- Bootstrap Navbar / Collapse

---

## Task 0 — Responsive Typography

A responsive typography page was created with headings, paragraphs and explanatory content.

CSS media queries change the typography at different screen widths:

- Desktop: large typography.
- Tablet: medium typography.
- Mobile: smaller typography.

### Screenshot

_Add screenshot of Task 0 here._

---

## Task 1 — Responsive Layout with Media Queries

Three content cards were created using CSS only.

The responsive behavior is:

- Desktop: three cards in one row.
- Tablet: two cards in the first row and one card in the second row.
- Mobile: all cards are stacked vertically.

Bootstrap is not used for the layout in this task.

### Screenshot

_Add screenshot of Task 1 here._

---

## Task 2 — Bootstrap Responsive Columns

Three service cards were created using the Bootstrap 12-column grid.

The classes are:

```text
Desktop: col-lg-4 + col-lg-4 + col-lg-4
Tablet:  col-md-6 + col-md-6, then another col-md-6
Mobile:  col-12 + col-12 + col-12
```

This demonstrates how Bootstrap automatically rearranges columns at different breakpoints.

### Screenshot

_Add screenshot of Task 2 here._

---

## Task 3 — Bootstrap Navigation Bar

A responsive Bootstrap navbar was created with:

- Logo on the left.
- Navigation links on the right.
- Hamburger button on smaller screens.
- Bootstrap Collapse component for the mobile menu.

### Screenshot — Desktop

_Add desktop screenshot here._

### Screenshot — Mobile

_Add mobile screenshot here._

---

## Task 4 — Responsive Portfolio Page

The final portfolio combines both required technologies.

### Bootstrap

Bootstrap is used for:

- Responsive navbar.
- Main two-part layout.
- Project card grid.
- Responsive columns.

### CSS Media Queries

Custom media queries are used for:

- Font sizes.
- Spacing.
- Card layout.
- Hero layout.
- Button layout.
- Footer alignment.

### Main Layout

On desktop the main section contains:

- Left side: project cards.
- Right side: personal information, skills and contact details.

On smaller screens the layout becomes a single column.

### Screenshot — Desktop

_Add desktop screenshot here._

### Screenshot — Tablet

_Add tablet screenshot here._

### Screenshot — Mobile

_Add mobile screenshot here._

---

## Work Process

I first created separate pages for each task so that every requirement could be demonstrated independently. Task 0 focuses on responsive typography, while Task 1 uses only CSS Media Queries for layout changes. Task 2 introduces the Bootstrap 12-column grid, and Task 3 demonstrates a responsive Bootstrap navbar. Finally, Task 4 combines Bootstrap and custom media queries into a complete responsive portfolio.

The project was tested by resizing the browser window between desktop, tablet and mobile widths.

## Project Structure

```text
assignment3_frontend/
├── index.html
├── task0.html
├── task1.html
├── task2.html
├── task3.html
├── portfolio.html
├── README.md
└── css/
    └── style.css
```

## How to Run

1. Open the project folder in VS Code.
2. Open `index.html` in a browser.
3. Select any assignment task.
4. Resize the browser window to test responsive behavior.
5. For Bootstrap features, an internet connection is required because Bootstrap is loaded from the CDN.

## Conclusion

The project demonstrates how CSS Media Queries and Bootstrap Grid can be combined to create interfaces that remain usable and visually consistent across desktop, tablet and mobile screen sizes.

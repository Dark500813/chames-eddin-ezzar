[README.md](https://github.com/user-attachments/files/34555677/README.md)
# HighTechStore

A responsive static website for **High TechStore**, a computer hardware shop based in Tunis, Tunisia. The site presents the company, its product categories, a PC catalogue, a registration form and general information (contact details, glossary and opening hours).

Built with plain **HTML5** and **CSS3**, with no framework and no JavaScript.

## Pages

| Page | File | Content |
| --- | --- | --- |
| Home | `index.html` | Company presentation, product categories and a login form |
| PC | `pages/pc.html` | PC catalogue table with a search and sort form |
| Registration | `pages/inscription.html` | Registration form (personal details, address, contact, remarks) |
| Info | `pages/info.html` | Manager and address, technical glossary and opening hours table |

## Features

- Shared header with the logo and navigation bar, and a shared footer on every page
- Home page layout with the login box on the right and the presentation cards on the left
- On small screens (600px and below) everything stacks in one column and the login box moves to the bottom
- PC catalogue table with reference, photo, description and price (in TND)
- Registration form laid out as a table that turns into a single column on mobile
- Opening hours table (summer and winter schedules, Ramadan hours) using `rowspan` and `colspan`
- Layout built with CSS Flexbox and CSS Grid, with no floats and no `position`

## Project structure

```
.
├── index.html
├── README.md
├── css
│   └── style.css
└── pages
    ├── pc.html
    ├── inscription.html
    ├── info.html
    └── image
        ├── lenovo.png
        ├── asus.png
        └── hp.png
```

All pages share a single stylesheet, `css/style.css`.

## Getting started

1. Download or clone the project.
2. Keep the folder structure above as it is, because the pages use relative paths.
3. Open `index.html` in any modern browser.

No installation or build step is needed.

## Responsive design

The layout adapts with one breakpoint:

- **Above 600px**: centered column, cards on the left and login box on the right
- **600px and below**: single column, compact header, smaller tables and full-width form fields

## Limitations

- The login, registration and catalogue search forms are front-end only. They are not connected to a server, so nothing is saved or sent.
- The governorate list in the registration form is empty.

## Technologies

- HTML5
- CSS3 (Flexbox, Grid, media queries)

## Author

Chames eddin Ezzar

&copy; 2026 High TechStore. All rights reserved.

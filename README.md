# ScholarPath

ScholarPath is a responsive, multi-page scholarship and education support website designed to help students discover scholarships, education loans, services, partners, success stories, and contact options.

## Overview

This project is a static front-end website built with plain HTML and CSS. It includes a landing page and supporting pages for:

- Scholarships
- Education loans
- Services
- Partners
- Success stories
- Contact
- Login
- Registration

## Project structure

- `index.html` — landing page and main marketing homepage
- `pages/` — all secondary pages for the site
  - `pages/scholarship.html` — scholarship opportunities page
  - `pages/education-loan.html` — education loan guidance page
  - `pages/services.html` — service offerings page
  - `pages/partners.html` — partner organizations and institutions
  - `pages/success-stories.html` — student success stories
  - `pages/contact.html` — contact information and inquiry page
  - `pages/login.html` — login page
  - `pages/register.html` — registration page
- `css/style.css` — shared styling and responsive design
- `assets/` — image files such as the logo and hero illustration
- `assets/ScholarICON.svg` — custom brand icon used as favicon and logo mark

## Run locally

From the project folder, start a local web server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Notes

- The site is fully front-end based and does not use a backend.
- Styling is centralized in `css/style.css` for consistency across pages.
- The project is mobile-friendly and tuned for smaller screen sizes.

## Customization

You can update branding, colors, page content, and layouts directly in:

- `css/style.css`
- the individual HTML pages
- `assets/ScholarICON.svg`

## License

This project is for educational/demo purposes unless otherwise specified.

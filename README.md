# Limessery Coffee Website

## Overview
A static website project for an e-commerce-style storefront built with HTML, SCSS, and images. The project includes a home page, product listing pages, reviews, contact page, and about page.

## Features
- Responsive e-commerce landing page layout
- Multiple page structure: home, products, reviews, contact, about
- SCSS-based styles with component partials for reusable layout sections
- Organized image assets for banners, products, reviews, and about content

## Project Structure

- `index.html` - main landing page
- `pages/` - additional site pages
  - `aboutPage.html`
  - `contactPage.html`
  - `productsPage.html`
  - `reviewPage.html`
- `scss/` - styling sources
  - `_variable.scss` - global variables and shared style values
  - `main.scss` - main stylesheet entry point
  - page-specific SCSS files: `aboutPage.scss`, `contactPage.scss`, `productsPage.scss`, `reviewPage.scss`
  - `components/` - reusable style modules
    - `_navbar.scss`
    - `_footer.scss`
    - `_products.scss`
- `images/` - image assets used across the site

## Usage
1. Open `index.html` in your browser to view the homepage.
2. Use the navigation links to access the product, review, contact, and about pages.

## Development
If you want to work with the styles, compile SCSS to CSS using your preferred SCSS compiler or build tool. Example with Dart Sass:

```bash
sass scss/main.scss css/main.css
```

Then link the generated CSS file in your HTML pages.

## Notes
- This repository is a static site project and does not include a backend.
- Adjust the SCSS variables and component styles in `scss/` to customize the design.

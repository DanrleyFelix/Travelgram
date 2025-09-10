# Travelgram

## Project Overview

This project is a travel profile page called **Travelgram**. It was developed as part of a **Rocketseat challenge**. The goal was to practice semantic HTML, modular CSS, responsive layouts, and consistent styling using CSS variables. The page displays a user profile, personal information, and a gallery of travel photos.

---

## Key Concepts Learned

### HTML Structure

* **Semantic Tags**:

  * `<nav>` for the navigation menu.
  * `<header>` for the profile information.
  * `<main>` for the gallery of travel images.
  * `<footer>` for legal links and copyright.

* **Other Tags**:

  * `<ul>` and `<li>` for menu items and profile info lists.
  * `<a>` for links and navigation.
  * `<img>` for profile photos, icons, and gallery images.
  * `<div>` for grouping content.

---

### CSS Concepts

#### Global Styles (`global.css`)

* Reset with `* { margin: 0; padding: 0; box-sizing: border-box; }`.
* CSS variables in `:root` for colors, typography, and spacing.
* Typography variables like `--text-lg`, `--text-md`, `--text-sm`.
* `.container` for centralized layouts with max-width and padding.
* `.bg-surface-color` for a surface-colored background.
* `a:hover` styling with brand color and underline.

#### Navigation (`nav.css`)

* Flexbox layout: `display: flex; justify-content: space-between; align-items: center`.
* Horizontal menu with `gap: 24px` for spacing between items.
* Circular profile image using `border-radius: 50%`.
* `object-fit: cover` to maintain image proportions.

#### Header (`header.css`)

* Flexbox to layout profile image and text side by side.
* `gap: 32px` between profile image and info text.
* Profile image styled circular and fixed size (176x176px).
* Text styled with CSS variables for font size and color.
* Profile info (`#info`) as vertical flex container with spacing.

#### Main Content (`main.css`)

* Flex-wrap used to create a responsive gallery grid.
* Gap of 24px between images.
* Each image fixed at 286x286px with `object-fit: cover` to avoid distortion.

#### Footer (`footer.css`)

* Flexbox layout with `gap: 24px` and vertical padding.
* First span pushed to the left using `margin-right: auto`.
* Font size and line-height set with CSS variables.

---

### Selectors and Combinations

* **Element selectors**: `body`, `a`, `img`, `main`, `footer`.
* **Class selectors**: `.container`, `.bg-surface-color`.
* **ID selectors**: `#profile`, `#info`.
* **Pseudo-classes**: `a:hover`.
* **Child combinators**: `#profile > div` for controlling nested layout.
* **Nth-child selector**: `footer span:nth-child(1)` to push the first element to the left.

---

## Learning Checklist

* [x] Apply semantic HTML: `header`, `nav`, `main`, `footer`.
* [x] Use lists (`ul`, `li`) for menus and information grouping.
* [x] Implement CSS reset and box-sizing.
* [x] Use CSS variables for colors, fonts, and text sizes.
* [x] Create responsive layouts with Flexbox (`display: flex`, `flex-wrap`).
* [x] Style profile images as circular with `border-radius: 50%` and `object-fit: cover`.
* [x] Modular CSS: separate files for `global`, `nav`, `header`, `main`, and `footer`.
* [x] Style links with pseudo-classes (`hover`).
* [x] Apply spacing consistently using `gap`, `padding`, and `margin`.

---
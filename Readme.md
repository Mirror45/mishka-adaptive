# 🐻 Mishka — Knitted Toys Online Store

**Mishka** is a multi-page website for an online store selling handmade knitted toys. The project is built using the **Mobile First** methodology (designing for mobile devices first, then scaling up to tablets and desktops). The layout is adaptive, fluid, and cross-browser compatible.

---

## 📄 Pages

The project consists of 3 key pages (located in the root of `source/`):

- **index.html** — Homepage (promotional items, reviews, contacts).
- **catalog.html** — Catalog (list of toys with prices and specifications).
- **form.html** — Custom Order Form (a complex form with various input types: radio buttons, checkboxes, text inputs, and validation).

---

## 🧰 Tech Stack

### 🔧 Core Technologies
- **HTML5**: Semantic markup, accessibility (a11y).
- **Sass (SCSS)**: Uses SCSS syntax. Styles are modularized according to the BEM methodology (`blocks/`, `global/`).
- **BEM**: Class naming follows the Block-Element-Modifier methodology.
- **JavaScript**: Native JS (Vanilla) for interface interactivity (modal windows, mobile menu, map).
- **Gulp 4**: Project build and task automation.

### ⚙️ Build Features (Gulp)

The build is configured to automate the following tasks:

| Category | Action |
|-----------|----------|
| **CSS** | SCSS compilation to CSS, automatic prefixing (`autoprefixer`), and style minification. |
| **JS** | Script minification (`script.js` -> `script.min.js`). |
| **HTML** | HTML file minification in the `build` folder. |
| **Images** | JPG/PNG optimization and **WebP** format generation. |
| **SVG** | SVG sprite assembly (`sprite.svg`) for icons. |
| **Fonts** | Font copying (Open Sans). |
| **Server** | Local `browser-sync` server with live reload. |

---

## 📁 Project Structure

```text
source/
├── fonts/             # Fonts (Open Sans)
├── img/               # Source images
│   └── icons/         # Icons for sprite generation
├── js/                # Scripts
│   └── script.js      # Main script file
├── sass/              # Styles (SCSS)
│   ├── blocks/        # BEM blocks (header, footer, catalog, etc.)
│   ├── global/        # Global styles, variables, mixins
│   └── style.scss     # Main stylesheet entry point
└── *.html             # HTML templates

build/                 # Production build folder (generated automatically)

```

---

## 📦 Getting Started

> ⚠️ **Node.js v16** is required to run the build tools.

```bash
# Clone the project
git clone git@github.com:Mirror45/mishka-adaptive.git

# Go to the project directory
cd mishka-adaptive

# Install all dependencies
npm install

# Run the development server
npm start

```

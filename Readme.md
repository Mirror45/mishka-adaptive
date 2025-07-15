# 🧸 Mishka — Adaptive Handcrafted Toy Store

**Mishka** is a responsive, cross-browser, semantic layout of an online handcrafted toy shop. The project includes three fully adaptive pages: homepage, catalog, and form. Built with **HTML**, **Sass**, and assembled with **Gulp 4**, the project implements the **BEM** methodology, progressive enhancement, and retina-ready graphics.

---

## 📄 Pages

- **Homepage** — promotional categories, product of the week with modal call-to-action, customer review block, and Map.
- **Catalog Page** — product grid with links, product image cropping, and video placeholder block.
- **Form Page** — contact/order form with custom fields, responsive layout, and built-in validation.

---

## 🧰 Tech Stack

### 🔧 Core Technologies

| Technology       | Description |
|------------------|-------------|
| **HTML5**        | Semantic and accessible markup. Validated via [W3C Validator](https://validator.w3.org/nu/). |
| **Sass (SCSS)**  | Modular structure with variables and mixins. Organized by `blocks/` and `global/`. |
| **Gulp 4**       | Used for automation: compiling styles, optimizing assets, live server, sprite generation. |
| **BEM Methodology** | Strict naming convention for scalable and reusable styles. |

---

## 🎯 Implementation Highlights

- **Mobile-first adaptive layout** for 320px, 768px, and 1150px breakpoints.
- **No JavaScript functionality required** — critical features implemented with pure HTML/CSS (progressive enhancement).
- **Retina-ready raster graphics** using `@2x` images.
- **SVG sprite** for icons and decorative graphics.
- **Local fonts** (`Open Sans`) in `.woff` and `.woff2` formats.
- **Flexbox and CSS Grid** used for layout and alignment.
- **Cross-browser compatibility**: Chrome, Firefox, Safari, Edge.
- **Accessibility-minded design**: semantic tags, label associations, and visual focus states.
- **Stylelint + EditorConfig** enforce clean and consistent code.
- **No third-party libraries** — all styling and layout built from scratch.

---

## 🛠 Gulp Plugins Used

| Plugin                  | Purpose |
|-------------------------|---------|
| `gulp-dart-sass`        | Compile SCSS to CSS. |
| `gulp-htmlmin`          | Minify HTML files. |
| `gulp-webp`, `gulp-libsquoosh` | Optimize and convert images to WebP. |
| `gulp-autoprefixer`, `postcss-csso` | Autoprefixing and CSS minification. |
| `gulp-svgstore`, `gulp-svgmin` | Create and optimize SVG sprites. |
| `browser-sync`          | LiveReload development server. |
| `gulp-plumber`          | Error prevention during task execution. |

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

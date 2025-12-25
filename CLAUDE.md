# CLAUDE.md

This file provides guidance for Claude Code when working with this repository.

## Project Overview

Personal portfolio website for Robert Laws built with vanilla HTML, CSS, and JavaScript.

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Styling (no preprocessor)
- **JavaScript** - Vanilla JS, no frameworks

## Project Structure

```
portfolio/
├── index.html          # Main entry point
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── assets/             # Images and other assets
├── .gitignore          # Git ignore rules
├── LICENSE             # MIT License
└── README.md           # Project readme
```

## Development

Open `index.html` directly in a browser, or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve

# Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```

## Code Conventions

- Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- CSS follows BEM naming convention (optional)
- JavaScript uses ES6+ features
- Keep accessibility in mind (ARIA labels, alt text, keyboard navigation)

## Browser Support

Target modern browsers (Chrome, Firefox, Safari, Edge - latest versions).

---

*Update this file as the project evolves with specific patterns and conventions.*

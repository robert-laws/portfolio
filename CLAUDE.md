# CLAUDE.md

This file provides guidance for Claude Code when working with this repository.

## Project Overview

Personal portfolio website for Robert Laws built with vanilla HTML, CSS, and JavaScript. Features a modern, clean design with a coral accent color.

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid (no preprocessor)
- **JavaScript** - Vanilla JS, ES6+ (no frameworks)

## Project Structure

```
portfolio/
├── index.html              # Home page (hero, projects, skills, teasers)
├── about.html              # About page
├── contact.html            # Contact page
├── css/
│   └── styles.css          # All styles (variables, components, responsive)
├── js/
│   └── main.js             # Mobile nav toggle, scroll effects
├── assets/
│   └── images/             # Project images and assets
├── projects/
│   ├── project-1.html      # Project detail pages
│   ├── project-2.html
│   ├── project-3.html
│   └── project-4.html
├── .gitignore
├── LICENSE
└── README.md
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

## Design System

### Colors (CSS Custom Properties)
- `--color-bg`: #FFFFFF (white)
- `--color-bg-alt`: #F8F9FA (light gray)
- `--color-text`: #1A1A1A (near black)
- `--color-text-muted`: #6C757D (gray)
- `--color-accent`: #FF6B5B (coral)
- `--color-accent-dark`: #E85A4A (dark coral)

### Key CSS Classes
- `.container` - Max-width centered container
- `.section` - Standard section padding
- `.btn--primary` / `.btn--outline` - Button variants
- `.project-card` - Project teaser cards
- `.skill-category` - Skills grid items

## Code Conventions

- Use semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- CSS uses BEM-like naming (`.block__element--modifier`)
- JavaScript uses IIFE pattern with strict mode
- Keep accessibility in mind (ARIA labels, alt text, keyboard navigation)

## Adding New Projects

1. Create a new file in `projects/` (e.g., `project-5.html`)
2. Copy structure from an existing project page
3. Add a new card to the projects grid in `index.html`
4. Update navigation links in adjacent project pages

## Browser Support

Target modern browsers (Chrome, Firefox, Safari, Edge - latest versions).

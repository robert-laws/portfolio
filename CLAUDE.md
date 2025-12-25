# CLAUDE.md

This file provides guidance for Claude Code when working with this repository.

## Project Overview

Personal portfolio website for Robert Laws.

## Current Status

This is a newly initialized repository. The .gitignore configuration suggests Jekyll/GitHub Pages as the intended platform.

## Technology Stack

- **Platform**: Jekyll / GitHub Pages (expected based on .gitignore)
- **Styling**: Likely SCSS/Sass (based on .sass-cache in .gitignore)

## Project Structure

```
portfolio/
├── .gitignore          # Jekyll-oriented ignore rules
├── LICENSE             # MIT License
└── README.md           # Project readme
```

## Common Commands

Once Jekyll is set up:
```bash
# Install dependencies
bundle install

# Run local development server
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

## Development Notes

- Build output goes to `_site/` directory (git-ignored)
- Jekyll cache files are in `.jekyll-cache/` (git-ignored)
- Sass cache is in `.sass-cache/` (git-ignored)

## File Conventions

When Jekyll is configured, expect:
- `_layouts/` - Page layout templates
- `_includes/` - Reusable components
- `_posts/` - Blog posts (if any)
- `_sass/` - SCSS partials
- `assets/` - Static assets (images, CSS, JS)
- `_config.yml` - Jekyll configuration

## Testing

No testing framework configured yet.

---

*Update this file as the project evolves with specific patterns, conventions, and commands.*

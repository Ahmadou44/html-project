# Copilot Instructions for HTML Project

## Project Overview
This is a minimal HTML5 project with a single page structure. The project currently contains only an `index.html` file serving as the main entry point.

## Key Files & Structure
- **[index.html](index.html)** - Main HTML document with HTML5 boilerplate

## Architecture & Conventions

### HTML Standards
- Use HTML5 semantic markup (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, etc.)
- Always include proper meta tags: charset, viewport for responsive design
- Use meaningful `lang` attributes on `<html>` tags
- Validate markup consistency with the existing DOCTYPE declaration

### Naming & Organization
- Use kebab-case for HTML class and id attributes (e.g., `main-header`, `feature-card`)
- Keep HTML structure flat and semantic; avoid excessive nesting
- Self-closing tags for void elements: `<meta />`, `<img />`, `<input />`

### When Expanding the Project
- Add CSS in a separate `styles.css` file in the root or `css/` directory
- Add JavaScript in a separate `script.js` file or `js/` directory
- Maintain single-responsibility principle: one file type per directory level
- Ensure all new pages remain HTML5 compliant and accessible (WCAG 2.1)

## Development Workflow
- No build tools required—serve HTML files directly with any HTTP server
- Test locally: Use Python (`python -m http.server`), VS Code Live Server, or similar
- No dependencies or package management needed currently

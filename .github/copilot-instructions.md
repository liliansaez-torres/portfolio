# Copilot Instructions for AI Agents

## Project Overview
This is a personal portfolio web project for Lilián Sáez Torres, showcasing experience and projects in Python, Visual Basic, and web development. The site is static, built with HTML, CSS, and JavaScript, and organized for clarity and maintainability.

## Architecture & Structure
- **Root files:**
  - `index.html`: Main entry point for the portfolio website.
  - `README.md`: Brief project description.
- **assets/**: Contains all static resources.
  - `css/`: Stylesheets (`styles.css`, `assets_css_styles.css`, `assets_css_styles_Version4.css`).
  - `js/`: JavaScript files for simple DOM interactions and custom scripts.
  - `img/`: Images (e.g., `perfil.jpeg`).
  - `index.html`, `index_Version4.html`: Alternative or legacy versions of the main page.

## Key Patterns & Conventions
- **HTML:**
  - Semantic structure: Navigation, sections for About, Experience, Projects, Education, and Contact.
  - Spanish language (`lang="es"`).
  - Links to CSS and JS via relative paths in `assets/`.
- **CSS:**
  - Consistent use of modern, clean styles for layout and typography.
  - Multiple CSS files exist; `styles.css` is the default, but others may be used for alternate versions.
- **JavaScript:**
  - Scripts are minimal, focused on DOMContentLoaded events for future extensibility.
  - No frameworks; pure JS only.

## Developer Workflow
- **No build tools or package managers** are present; all development is direct file editing.
- **No automated tests or CI/CD**; manual browser refresh is the main workflow for previewing changes.
- **No external dependencies**; all code is local and static.

## Integration Points
- **Python/Visual Basic projects** referenced in the portfolio are not included in this repo; this is a showcase site only.
- **No backend/server code**; all content is client-side.

## How to Extend
- Add new sections by editing `index.html` and corresponding CSS/JS files.
- For new styles, prefer adding to `assets/css/styles.css` unless working on a versioned page.
- For new scripts, use `assets/js/scripts.js` for general features.

## Examples
- To add a new project, edit the `<section id="projects">` in `index.html`.
- To change the theme, update `assets/css/styles.css` and link it in the HTML `<head>`.

## Special Notes
- Spanish is the default language for content and comments.
- Keep code simple and readable; avoid over-engineering.
- If adding new versions, follow the existing naming convention (e.g., `index_Version4.html`).

---
For questions or unclear conventions, review `README.md` and the main HTML/CSS/JS files for examples.

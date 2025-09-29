# Copilot Instructions for Portfolio Codebase

## Overview
This is a static portfolio website consisting of multiple HTML files and image assets. The site showcases personal experience, projects, and achievements. There is no backend, build system, or automated test workflow present.

## Key Files & Structure
- `index.html`: Main landing page.
- `about.html`, `experience.html`, `projects.html`: Sectional pages for About, Experience, and Projects.
- Image files (JPEG, PNG): Used for profile, certificates, patents, and project visuals.
- No CSS or JS files detected; all styling and interactivity (if any) is inline or absent.

## Editing & Conventions
- All content is static and hand-authored in HTML.
- Use semantic HTML tags for structure (e.g., `<section>`, `<article>`, `<header>`, `<footer>`).
- Images are referenced with relative paths; ensure new assets are placed in the root directory and linked accordingly.
- Maintain consistent formatting and indentation for readability.
- For new sections, follow the pattern in existing HTML files: header, content blocks, and image placement.

## Developer Workflow
- No build, test, or deployment scripts are present.
- Edit HTML files directly and preview in a browser.
- To add new achievements or projects, duplicate the structure from similar sections in `experience.html` or `projects.html`.

## Integration Points
- No external dependencies or integrations detected.
- All resources are local; avoid linking to external scripts or styles unless discussed with the project owner.

## Examples
- To add a new experience, copy an existing `<div class="experience-item">` block in `experience.html` and update the content and image.
- For new project entries, follow the markup in `projects.html`.

## Special Notes
- If adding new file types (CSS, JS), document their purpose and usage in this file.
- Keep all images and assets in the root directory for consistency.

---
For questions about unclear conventions or missing workflows, ask the project owner for clarification.

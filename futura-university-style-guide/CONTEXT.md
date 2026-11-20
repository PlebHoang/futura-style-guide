# Context

## Purpose

This folder packages the Futura University Style Guide as a small, shareable project instead of leaving the HTML file loose in the parent `Github` directory. The guide is intended to help students, designers, and collaborators produce consistent Project 2 pages in Canva.

## What the HTML is

`Futura University Style Guide.html` is a self-contained interactive reference document. It combines the visual specification with practical examples and checks for:

- Brand colors and contrast
- Heading and body typography
- Logo/mark placement
- Reusable content blocks
- Draft-merging and quality assurance

The document uses inline HTML, CSS, and JavaScript so it can be opened directly from a file system, attached to a message, or hosted as a static page. It does not require a framework, a server, or a package manager.

## Design principles

- **Institutional gravitas:** Oxford navy, chalk white, oak accents, and editorial serif headings establish an academic tone.
- **High-contrast scannability:** Clear hierarchy and restrained color use keep pages easy to navigate.
- **Cross-platform survival:** Layouts and examples should remain usable in Canva, browsers, viewers, and exports.

## File and folder conventions

- Keep the main HTML filename stable because the README links to it.
- Keep documentation in Markdown beside the HTML.
- Do not add generated build output or dependencies for this static guide.
- If the guide changes substantially, update both this file and `README.md` so a new contributor can understand the change without opening the HTML first.

## Maintenance checklist

Before committing an update:

1. Open the HTML in a desktop and mobile-sized browser window.
2. Check navigation, theme controls, buttons, and interactive examples.
3. Confirm that the HTML still works without a network connection.
4. Verify that the README links and section descriptions remain accurate.
5. Review the QA section in the guide before publishing.

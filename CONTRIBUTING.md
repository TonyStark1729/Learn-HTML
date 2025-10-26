# Contributing to Learn HTML – Step by Step

Thank you for your interest in contributing! This project is intended as a pure, educational HTML resource. To keep the site consistent and easy to review, please follow the guidelines below.

## Project constraints (important)
- This site is intentionally **HTML-only**. Do not add CSS files, inline styles, JavaScript, or external libraries to the site pages.
- Documentation files (Markdown) such as `README.md`, `CONTRIBUTING.md`, and issue/PR templates are allowed and encouraged.

## Getting started
1. Fork the repository and clone your fork locally.
2. Create a feature branch from `main`:

```bash
git checkout -b feature/your-short-description
```

3. Make small, focused changes. Keep commits atomic and the PRs focused on a single logical change.

## Branch naming
- feature/short-description (new features or enhancements)
- fix/short-description (bug fixes and small corrections)
- docs/short-description (documentation changes)

## Pull request checklist
Before you open a PR, please ensure:
- [ ] Your change follows the "HTML-only" constraint for site pages.
- [ ] You tested your changes locally in at least two browsers (Chrome/Firefox/Edge/Safari).
- [ ] Images include meaningful `alt` text when added or updated.
- [ ] Forms have associated `<label>` elements and clear instructions.
- [ ] Semantic HTML elements are used where appropriate (`<header>`, `<main>`, `<nav>`, `<section>`, `<footer>`).
- [ ] No external resources (CDNs, libraries, frameworks) are introduced.
- [ ] The PR description explains why the change is valuable and how to test it.

## Accessibility
Accessibility is important. Try to:
- Use `alt` text for images and `aria-*` attributes where needed.
- Add `role` or `aria-label` to non-textual SVG graphics (e.g., hero banners) when appropriate.
- Keep heading order logical (H1 → H2 → H3).

## Examples of good first PRs
- Fix small HTML validation issues (missing closing tags, incorrect nesting).
- Improve form labeling and semantics.
- Add `CONTRIBUTING.md` or small documentation clarifications.
- Add inline SVG decoratives that do not affect content flow.

## How to open a PR
1. Push your branch to your fork or to a remote branch.
2. Open a pull request against `main` with a clear title and description.
3. Add a short testing plan and mention any manual checks necessary.

## Review process
- Maintainers will review PRs for correctness, accessibility, and alignment with the HTML-only constraint.
- Expect constructive feedback; maintainers may ask for small changes before merging.

## License
By contributing, you agree that your contributions will be licensed under the project's MIT license.

Thank you for helping improve this resource — every small fix or clarity improvement helps learners worldwide!
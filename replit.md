# Tailwind CSS Info Site

A single-page static website about Tailwind CSS, built entirely with Tailwind CSS (via CDN).

## Stack

- Plain HTML5 (`index.html`)
- Tailwind CSS v4 via browser CDN (`@tailwindcss/browser@4`)
- Python's built-in HTTP server to serve locally

## Running

```bash
python3 -m http.server 5000
```

The site is served at port 5000. The workflow "Start application" does this automatically.

## Structure

```
index.html        — The entire site (one page)
src/input.css     — Tailwind source CSS (unused in CDN mode)
src/output.css    — Tailwind compiled output (unused in CDN mode)
package.json      — Tailwind CLI build scripts (for local compilation)
```

## Sections

1. **Hero** — tagline and CTAs
2. **What is Tailwind?** — explanation with code comparison
3. **Why Tailwind?** — 6 feature cards
4. **Common Utilities** — quick-reference table of everyday classes
5. **Live Example** — a card component with its source code side-by-side
6. **Responsive & State Variants** — breakpoint, hover/focus, dark mode reference
7. **CTA** — links to docs and playground

## User Preferences

- Keep it as a single HTML file with no build step required.

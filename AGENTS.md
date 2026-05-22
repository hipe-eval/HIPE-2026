# AGENTS.md instructions for HIPE-2026 website

## Site Conventions

This directory is the Jekyll/Minimal Mistakes website for <https://hipe-eval.github.io/HIPE-2026/>.

- Edit source pages under `_pages/`; do not edit generated files under `_site/`.
- Keep page front matter with `title` and `permalink` fields consistent with the existing pages.
- Use site-relative links that include the configured base path when writing raw HTML image links, for example `/HIPE-2026/assets/...`.
- Prefer normal Markdown tables and links unless the existing page already uses HTML for layout.
- Place downloadable public artifacts under `assets/`, using a descriptive subdirectory such as `assets/results/`.
- Keep public examples and documentation snippets using `make`, not `remake`.

## Local Commands

When running local commands yourself from this site repository, use the repository's existing Jekyll workflow. Public-facing instructions should use `bundle exec jekyll serve` or `make` only if a Makefile is later added.

## Results Page

The Results page should be concise and public-facing. Link full generated reports and machine-readable result artifacts from the website, but summarize the official rankings directly on the page so readers do not need to open a raw Markdown report to see the main outcome.

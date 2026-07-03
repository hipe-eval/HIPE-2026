# AGENTS.md

Guidance for coding agents working in this repository.

## Project Context

This repo contains the Jekyll (Minimal Mistakes) website for HIPE-2026:
https://hipe-eval.github.io/HIPE-2026/

## Primary Editing Rules

- Edit source content, not generated output.
- Never manually edit files under `_site/`.
- Prefer editing pages in `_pages/` and shared config/data in `_config.yml` and `_data/`.
- Keep YAML front matter valid and consistent, especially `title` and `permalink`.
- Preserve the current writing style: concise, public-facing, and task-oriented.

## Paths, Links, and Assets

- For Markdown links, prefer normal Markdown syntax over raw HTML unless the page already requires HTML layout.
- For raw HTML links to local assets, include the website base path:
  `/HIPE-2026/assets/...`
- Store public downloadable artifacts under `assets/`, using descriptive subfolders.
- Current results artifacts are expected under:
  - `assets/results/ternary/`
  - `assets/results/binary/`

## Results Page Expectations

When updating `_pages/results.md`:

- Keep it concise and readable for participants.
- Show official ranking summaries directly on the page.
- Link out to full generated reports and machine-readable artifacts.
- Avoid forcing readers to open raw report markdown just to see main outcomes.

## Local Validation Commands

Use the repository's Jekyll workflow:

- Install deps: `bundle install --path vendor/bundle`
- Serve locally: `bundle exec jekyll serve`
- Clean generated files: `bundle exec jekyll clean`

If giving public instructions, prefer `bundle exec jekyll serve`. Mention `make` only if a Makefile is added later.

## Safety Checklist Before Finishing

- Confirm no edits were made in `_site/`.
- Confirm front matter remains valid YAML.
- Confirm internal links and asset paths resolve with `/HIPE-2026/` when needed.
- Keep changes minimal and scoped to the requested task.

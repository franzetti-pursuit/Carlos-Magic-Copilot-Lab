<!-- This file is generated/maintained by an AI assistant. Keep guidance concise and actionable. -->
# Copilot instructions for my-first-repo

Purpose
- Small practice repository with a single static page (`index.html`) and a short `README.md`.

What an agent should do first
- Inspect `index.html` and `README.md` to understand the current state (both are minimal/empty).
- Confirm there is no build, tests, or CI configuration in the repo before suggesting tooling or commands.

Typical tasks and how to perform them
- Add or update site content: edit `index.html` and—if content or purpose changes—update `README.md` to match.
  - Example PR title: `feat: add homepage content`
  - Example PR body: short summary + list of edited files and a screenshot or instructions to preview.
- Small UI changes (text, headings, structure): keep changes limited to `index.html` and include a short note in the README.
- If you need to preview changes locally: open `index.html` in a browser (no build step required). Using an editor Live Server is OK but not required.

Project conventions and constraints
- This is a single-file static site—do not introduce heavy frameworks or dependencies without an explicit reason.
- Keep commits small and atomic. Update `README.md` when adding features or changing repo purpose.
- There are no tests or linters in the repository—if you add them, document how to run them in the README and add any config files to the repo.

When to open an issue or create a PR
- Open an issue for non-trivial or multi-file changes (new pages, structural changes, adding tooling).
- For one-off content or styling tweaks, create a small PR that edits `index.html` and updates `README.md` if necessary.

Review checklist for PRs
- Does `index.html` render correctly in a browser? (manual check)
- Is `README.md` updated to reflect any change in purpose or added content?
- Are commits descriptive and the PR focused and small?

Helpful examples (edit these directly)
- Minimal homepage snippet to use as a template:

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>my-first-repo</title>
  </head>
  <body>
    <h1>Welcome to my-first-repo</h1>
    <p>Practice repo for learning GitHub</p>
  </body>
</html>
```

If you have questions or there's missing context, ask the maintainers in an issue instead of guessing.

# ryanmoch.com

Personal site, built with Jekyll and hosted on GitHub Pages at
[ryanmoch.com](https://ryanmoch.com).

## Editing content

All content lives in markdown files at the repo root. Edit, commit, push —
GitHub Pages rebuilds the site automatically (no CI config needed). Edits made
directly in the GitHub web UI work too.

| File | Page |
|------|------|
| `index.md` | Homepage — about + skills |
| `experience.md` | Work history + education |
| `interests.md` | Hobby interest areas |

Notes:

- On `experience.md`, each role is an `### Title — Company` heading followed by
  an italic `*dates · location*` line; the timeline styling keys off that
  structure.
- On `interests.md`, each `<section markdown="1">` block renders as a card —
  duplicate one to add a new interest area.
- Theme/colors: `assets/css/style.css` (CSS custom properties at the top).
- Shared layout (nav, footer, meta tags): `_layouts/default.html`.

## Local preview (optional)

Requires Ruby:

```sh
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

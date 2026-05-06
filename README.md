# dshb-pro-dev-mock-conference

Source for the **DSHB Professional Development Conference Micro Site —
Summer 2026**, a Quarto website supporting the *Tools for Large Scale Data
Science* course in the UW–Madison M.S. Psychology: Data Science in Human
Behavior program.

## Local Development

```bash
# Preview with live reload
quarto preview

# Render to ./_site/ once
quarto render
```

## Publishing

```bash
quarto publish gh-pages
```

Requires a configured GitHub remote and working GitHub authentication.

## Project Structure

```
.
├── _quarto.yml              # Site config, navbar, theme
├── theme.scss               # UW–Madison branded SCSS
├── styles.css               # Small CSS additions
├── index.qmd                # Landing page (schedule + overview)
├── about.qmd                # About this microsite (stub)
├── provenance.qmd           # Site provenance (stub)
├── maintainer-guide.qmd     # Maintainer guide (stub)
├── accessibility.qmd        # Accessibility features (stub)
└── topics/
    ├── _outline-template.qmd  # Shared 70-min outline partial
    ├── windsurf.qmd
    ├── ollama.qmd
    ├── sql.qmd
    ├── github.qmd
    ├── quarto.qmd
    └── qualtrics.qmd
```

## Maintainer

Dr. Adam Ross Nelson

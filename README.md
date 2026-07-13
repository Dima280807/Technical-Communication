# Hearts of Iron IV Starter Documentation

This repository contains beginner-friendly documentation for Hearts of Iron IV, managed with a Docs-as-Code workflow.

## Documentation Structure

- `docs/index.md` - documentation home page
- `docs/beginner-guide.md` - main beginner guide
- `docs/glossary.md` - short explanations of important game terms
- `mkdocs.yml` - MkDocs site configuration
- `.github/workflows/docs.yml` - automated documentation checks

## Local Preview

Install the documentation dependencies:

```bash
python -m pip install mkdocs mkdocs-material
```

Optional: install the Markdown linter if Node.js is available:

```bash
npm install -g markdownlint-cli
```

Start a local preview server:

```bash
mkdocs serve
```

Build the documentation:

```bash
mkdocs build --strict
```

Run Markdown linting:

```bash
markdownlint "**/*.md"
```

## Docs-as-Code Workflow

1. Create a branch for documentation changes.
2. Edit Markdown files in `docs/`.
3. Run local checks when possible.
4. Open a pull request.
5. Wait for CI checks to pass.
6. Merge the update into `main`.

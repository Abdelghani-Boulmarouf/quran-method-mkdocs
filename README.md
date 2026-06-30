# Quran Method MkDocs Site

This is a MkDocs + Material project for publishing the Arabic Markdown series with RTL layout, side navigation, and search.

## Local preview

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

Open:

```text
http://127.0.0.1:8000
```

## Build static site

```bash
mkdocs build
```

The generated static site will be in the `site/` folder.

## Publish to GitHub Pages

After creating and pushing to a GitHub repository:

```bash
mkdocs gh-deploy --force
```

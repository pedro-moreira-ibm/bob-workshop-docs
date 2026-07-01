# IBM Bob Hands-on Labs

MkDocs site for the IBM Bob hands-on workshop labs.

## Local preview

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

## Build

```bash
mkdocs build --strict
```

## Publish

Push this repository to GitHub and enable GitHub Pages with the GitHub Actions workflow.

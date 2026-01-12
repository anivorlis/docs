# CFC Teams Documentation

Documentation for the various teams involved in organizing the conference, including their responsibilities, workflows, and how to contribute to each team.

## Requirements

- Python 3.x
- [uv](https://docs.astral.sh/uv/) - Fast Python package installer and resolver

## Installation

```bash
# Install dependencies
uv sync
```

## Local Development

```bash
# Serve documentation locally with live reload
uv run mkdocs serve
```

The site will be available at `http://127.0.0.1:8000/`

## Build

```bash
# Build static site
uv run mkdocs build
```

The built site will be in the `site/` directory.

## Deployment

Documentation is automatically deployed to GitHub Pages on every push to the `main` branch via GitHub Actions.

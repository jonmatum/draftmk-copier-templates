# draftmk-copier-templates

This repository contains official Copier templates for [DraftMk](https://pypi.org/project/draftmk/) projects.

These templates are automatically used by the `draftmk` CLI to scaffold new MkDocs-based documentation projects with Docker, Vite, and Markdown enhancements.

## Features

- Standardized MkDocs configuration
- Predefined project folder structure
- Vite integration and environment support
- Copier-powered prompts for customization

## Usage

### With the `draftmk` CLI

Install DraftMk and initialize a new project:

```bash
pip install draftmk
draftmk init
```

## Template Configuration

The `copier.yml` file defines the following configuration prompts:

- `project_name`: Display name for your site
- `repo_name`: GitHub repository path (e.g. `your-org/your-repo`)
- `site_url`: Base URL of your site (for MkDocs config)
- `vite_env`: Frontend environment (e.g. `production`, `staging`)

## License

MIT © [Jonatan Mata](https://jonmatum.dev)

---

```bash
echo "Pura Vida & Happy Coding!";
```

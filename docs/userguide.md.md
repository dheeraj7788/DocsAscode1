# Getting Started

Welcome to the Docs-As-Code Project.

This guide helps you set up the documentation portal on your local machine and preview the website using MkDocs.

---

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.10 or later
- Git
- A code editor such as Visual Studio Code

---

## Project Structure

```text
Docs-As-Code/
│
├── mkdocs.yml
│
└── docs/
    ├── index.md
    └── getting-started.md
```

---

## Install MkDocs

Install MkDocs and the Material theme:

```bash
pip install mkdocs mkdocs-material
```

Verify the installation:

```bash
mkdocs --version
```

---

## Create the Documentation Site

Start the local development server:

```bash
mkdocs serve
```

Open the following URL in your browser:

```text
http://127.0.0.1:8000
```

---

## Create Your First Page

Create a new Markdown file:

```text
docs/user-guide.md
```

Add the following content:

```md
# User Guide

Welcome to the User Guide.
```

---

## Update Navigation

Edit the `mkdocs.yml` file:

```yaml
nav:
  - Home: index.md
  - Getting Started: getting-started.md
  - User Guide: user-guide.md
```

Save the file and refresh the browser.

---

## Next Steps

After completing the setup:

- Create additional documentation pages
- Push the project to GitHub
- Configure GitHub Pages
- Set up GitHub Actions for CI/CD deployment

---

## Summary

You have successfully:

- Installed MkDocs
- Created a documentation site
- Started a local server
- Added a 
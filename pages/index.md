---
layout: default
---

<!-- markdownlint-disable MD024 MD033 MD041 -->

<a id="top"></a>

<div align=center>

<p>
  🌍 <strong><a href="https://imfsiddiqui.github.io/{{ site.repository_name }}">Web Page</a></strong>
  |
  💻 <strong><a href="https://github.com/imfsiddiqui/{{ site.repository_name }}">Source Code</a></strong>
  |
  🚀 <strong><a href="https://github.com/imfsiddiqui/{{ site.repository_name }}/releases">Releases</a></strong>
</p>

</div>

# 🏗️ brepo

A base template repository to quickly bootstrap new projects with preconfigured structure, essential files, and common workflows.

<div align="center">
  <img
    src="./assets/images/{{ site.repository_name }}.svg"
    style="border-radius: 10px"
    alt="{{ site.repository_name }}"
  />
</div>

## 📚 Table of Contents

- [🏗️ brepo](#️-brepo)
  - [📚 Table of Contents](#-table-of-contents)
  - [📌 About](#-about)
  - [🧠 Philosophy](#-philosophy)
  - [🔑 Key Features](#-key-features)
  - [🗂️ Directory Structure](#️-directory-structure)
    - [🌱 Root Files](#-root-files)
    - [🐙 `.github/`](#-github)
    - [✏️ `.vscode/`](#️-vscode)
    - [📄 `pages/`](#-pages)
    - [👓 `readme/`](#-readme)
    - [🗑️ `tmp/`](#️-tmp)
  - [🏆 Use Cases](#-use-cases)
  - [📜 License](#-license)

<p align="right"><a href="#top">☝️</a></p>

## 📌 About

This is a foundational template repository designed to accelerate the setup of new projects by providing a thoughtfully organized structure, essential configuration files, and prebuilt workflows. It is developed for personal use but also ideal for other developers as well who want to start coding immediately without spending time on repetitive project scaffolding or boilerplate setup.

<p align="right"><a href="#top">☝️</a></p>

## 🧠 Philosophy

The goal is to minimize setup friction and maximize productivity by automating the repetitive aspects of project initialization.

<p align="right"><a href="#top">☝️</a></p>

## 🔑 Key Features

- **Preconfigured Directory Structure:** Includes common folders to ensure consistency across projects.
- **Essential Files:** Comes with ready-to-use files such as `.gitignore`, `.editorconfig`, `LICENSE.md`, `README.md`, `CHANGELOG.md`, and `TODO.md` to enforce best practices from the start.
- **Documentation-First Approach:** Provides Markdown templates for README, TODO, and CHANGELOG, making it easy to maintain high-quality documentation.
- **Jekyll Pages Integration:** The `pages/` directory is set up for Jekyll, enabling instant publishing of project documentation to GitHub Pages with minimal configuration.
- **GitHub Actions Workflows:** Includes reusable workflows for CI/CD, automated documentation deployment, streamlining development and release processes.
- **Customization Ready:** All configuration files and templates are easy to modify, allowing to adapt the repository to their specific needs and workflows.

<p align="right"><a href="#top">☝️</a></p>

## 🗂️ Directory Structure

The structure supports easy project bootstrapping, automated CI/CD, and documentation-first development.

💡 ***Note:*** *Each `.gitkeep` file is used to ensure empty directories are tracked by Git.*

```shell
.
├── .editorconfig
├── .gitignore
├── brepo.code-workspace
├── CHANGELOG.md
├── LICENSE.md
├── README.md
├── TODO.md
├── .github/
│   ├── .gitkeep
│   ├── copilot/
│   │   ├── .gitkeep
│   │   └── commit-instructions.md
│   └── workflows/
│       ├── .gitkeep
│       └── pages.yml
├── .vscode/
│   └── settings.json
├── pages/
│   ├── _config.yml
│   ├── .gitkeep
│   ├── index.md
│   ├── _includes/
│   │   ├── .gitkeep
│   │   ├── head-custom-google-analytics.html
│   │   └── head-custom.html
│   ├── _pages/
│   │   └── .gitkeep
│   └── assets/
│       ├── .gitkeep
│       ├── css/
│       │   └── .gitkeep
│       └── images/
│           ├── .gitkeep
│           └── brepo.svg
├── readme/
│   ├── .gitkeep
│   ├── assets/
│   │   ├── .gitkeep
│   │   └── brepo.svg
│   └── pages/
│       └── .gitkeep
└── tmp/
    └── .gitkeep
```

### 🌱 Root Files

Project-wide configs, documentation, and workspace settings.

- `.editorconfig`: Editor configuration for consistent coding styles across editors.
- `.gitignore`: Specifies files/folders for Git to ignore (e.g., build artifacts, virtualenvs, etc.).
- `brepo.code-workspace`: VS Code workspace settings for this project.
- `CHANGELOG.md`: Human-readable log of all notable changes (follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)).
- `LICENSE.md`: License for the project.
- `README.md`: Main documentation and overview of the project.
- `TODO.md`: List of planned features, bugs, and refactoring tasks.

### 🐙 `.github/`

GitHub-specific workflows, Copilot configs, and repo automation.

- `.gitkeep`: Placeholder.
- `copilot/`: Configuration for GitHub Copilot, including commit message instructions.
  - `.gitkeep`: Placeholder.
  - `commit-instructions.md`: Conventional Commits instructions for Copilot-generated commit messages.
- `workflows/`: GitHub Actions workflows for CI/CD.
  - `.gitkeep`: Placeholder.
  - `pages.yml`: Workflow for building and deploying the Jekyll site to GitHub Pages.

### ✏️ `.vscode/`

VS Code editor settings for consistent development experience.

- `settings.json`: VS Code-specific settings, including Copilot commit message instructions.

### 📄 `pages/`

Jekyll site source for project documentation and static assets.

- `_config.yml`: Jekyll configuration for the documentation site.
- `.gitkeep`: Placeholder.
- `index.md`: Main landing page for the Jekyll site.
- `_includes/`: Jekyll partials for reusable HTML (e.g., analytics, favicon).
  - `.gitkeep`: Placeholder.
  - `head-custom-google-analytics.html`: Google Analytics script partial.
  - `head-custom.html`: Custom head content (includes favicon and analytics).
- `_pages/`: Custom pages for the Jekyll site.
  - `.gitkeep`: Placeholder.
- `assets/`: Static assets for the Jekyll site.
  - `.gitkeep`: Placeholder.
  - `css/`: CSS files for Jekyll site.
    - `.gitkeep`: Placeholder.
  - `images/`: Image files for Jekyll site.
    - `.gitkeep`: Placeholder.
    - `brepo.svg`: Project banner used in Jekyll site.

### 👓 `readme/`

Assets and extra docs for the main README and related pages.

- `.gitkeep`: Placeholder.
- `assets/`: Assets for the README.
  - `.gitkeep`: Placeholder.
  - `brepo.svg`: Project image used in documentation.
- `pages/`: Placeholder for additional documentation pages.
- `.gitkeep`: Placeholder.

### 🗑️ `tmp/`

Temporary files and folders, ignored in version control.

- `.gitkeep`: Placeholder.

<p align="right"><a href="#top">☝️</a></p>

## 🏆 Use Cases

- **Rapid Prototyping:** Quickly spin up new repositories for experiments, prototypes, or MVPs with a solid foundation.
- **Standardize Projects:** Standardize project structure and workflows to reduce initialization time and improve productivity.
- **Open Source Projects:** Ensure new open source repositories follow best practices for documentation, licensing, and automation from day one.

<p align="right"><a href="#top">☝️</a></p>

## 📜 License

This project is licensed under the MIT License (`LICENSE.md`), allowing anyone to use, modify, and distribute it freely for personal or commercial purposes.

<p align="right"><a href="#top">☝️</a></p>

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
    src="https://raw.githubusercontent.com/imfsiddiqui/brepo/refs/heads/docs/merge-pages-inside-docs/docs/pages/assets/images/brepo-banner-wide.svg"
    style="border-radius: 10px"
    alt="brepo project banner"
  />
</div>

## 📚 Table of Contents

- [🏗️ brepo](#️-brepo)
  - [📚 Table of Contents](#-table-of-contents)
  - [📌 About](#-about)
  - [🧠 Philosophy](#-philosophy)
  - [🔑 Key Features](#-key-features)
  - [🏆 Use Cases](#-use-cases)
  - [🗂️ Directory Structure](#️-directory-structure)
  - [📄 Important Documents](#-important-documents)
  - [📜 License](#-license)

<p align="right"><a href="#top">☝️</a></p>

## 📌 About

This is a foundational template repository designed to accelerate the setup of new projects by providing a thoughtfully organized structure, essential configuration files, and prebuilt workflows. It is developed for personal use but also ideal for other developers as well who want to start coding immediately without spending time on repetitive project scaffolding or boilerplate setup.

<p align="right"><a href="#top">☝️</a></p>

## 🧠 Philosophy

The goal is to minimize setup friction and maximize productivity by automating the repetitive aspects of project initialization.

<p align="right"><a href="#top">☝️</a></p>

## 🔑 Key Features

- **Comprehensive Project Structure:** Organized directories for automation: `.github`, documentation: `docs`, and GitHub Pages: `pages`, supporting scalable and maintainable projects.
- **Ready-to-Use Essential Files:** Provides the following essential files out-of-the-box to enforce best practices from the start.
  - `.editorconfig`
  - `.gitignore`
  - `LICENSE.md`
  - `README.md`
  - `docs/CHANGELOG.md`
  - `docs/CODE-OF-CONDUCT.md`
  - `docs/CONTRIBUTING.md`
  - `docs/ROADMAP.md`
  - `docs/SECURITY.md`
  - `docs/TODO.md`
- **Documentation-First Workflow:** Markdown templates making it easy to maintain high-quality documentation.
- **Jekyll Documentation Site:** The `pages/` directory is preconfigured for Jekyll, enabling instant publishing of project docs to GitHub Pages.
- **Automated CI/CD:** Includes reusable GitHub Actions workflows for CI/CD, automated documentation deployment, streamlining development and release processes.
- **Copilot Guidance:** Instructions for Copilot and VS Code integration, including both commit message and pull request description guidelines to ensure consistency with Conventional Commits.
- **Customization Friendly:** All configuration files and templates are easy to modify for specific needs and workflows.
- **VS Code Workspace Support:** Predefined workspace and editor settings for a consistent development experience.

<p align="right"><a href="#top">☝️</a></p>

## 🏆 Use Cases

- **Rapid Prototyping:** Quickly spin up new repositories for experiments, prototypes, or MVPs with a solid foundation.
- **Standardize Projects:** Standardize project structure and workflows to reduce initialization time and improve productivity.
- **Open Source Projects:** Ensure new open source repositories follow best practices for documentation, licensing, and automation from day one.

<p align="right"><a href="#top">☝️</a></p>

## 🗂️ Directory Structure

The repository is organized for rapid bootstrapping, automation, and documentation-driven development.

💡 **Note:** *`.gitkeep` files ensure empty directories are tracked by Git.*

```console
.
├── .editorconfig
├── .gitignore
├── brepo.code-workspace
├── LICENSE.md
├── README.md
├── .github/
│   ├── .gitkeep
│   ├── copilot/
│   │   ├── .gitkeep
│   │   ├── commit-message-instructions.md
│   │   └── pull-request-description-instructions.md
│   └── workflows/
│       ├── .gitkeep
│       └── pages.yml
├── .vscode/
│   └── settings.json
├── docs/
│   ├── .gitkeep
│   ├── CHANGELOG.md
│   ├── CODE-OF-CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── ROADMAP.md
│   ├── SECURITY.md
│   ├── TODO.md
│   ├── assets/
│   │   ├── .gitkeep
│   │   ├── brepo-banner.svg
│   │   ├── brepo-social-media-preview.png
│   │   └── brepo-social-media-preview.svg
│   └── pages/
│       └── .gitkeep
├── pages/
│   ├── .gitkeep
│   ├── _config.yml
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
│           └── brepo-banner.svg
└── tmp/
    └── .gitkeep
```

<p align="right"><a href="#top">☝️</a></p>

## 📄 Important Documents

- [Changelog](https://github.com/imfsiddiqui/brepo/blob/main/docs/CHANGELOG.md): Changelog of all notable changes.
- [Code of Conduct](https://github.com/imfsiddiqui/brepo/blob/main/docs/CODE-OF-CONDUCT.md): Code of Conduct for contributors.
- [Commit Message Instructions](https://github.com/imfsiddiqui/brepo/blob/main/.github/copilot/commit-message-instructions.md): Commit message guidelines for contributors and Copilot.
- [Contribution Guidelines](https://github.com/imfsiddiqui/brepo/blob/main/docs/CONTRIBUTING.md): How to contribute to this project.
- [License](https://github.com/imfsiddiqui/brepo/blob/main/LICENSE.md): License text.
- [Pull Request Description Instructions](https://github.com/imfsiddiqui/brepo/blob/main/.github/copilot/pull-request-description-instructions.md): Pull request guidelines for contributors and Copilot.
- [Roadmap](https://github.com/imfsiddiqui/brepo/blob/main/docs/ROADMAP.md): High-level strategic plan, long-term goals, milestones, and overall project vision.
- [Security Policy](https://github.com/imfsiddiqui/brepo/blob/main/docs/SECURITY.md): Security policy and reporting instructions.
- [Todo](https://github.com/imfsiddiqui/brepo/blob/main/docs/TODO.md): Day-to-day task tracking and immediate execution.

<p align="right"><a href="#top">☝️</a></p>

## 📜 License

This project is licensed under the [MIT License](https://github.com/imfsiddiqui/brepo/blob/main/LICENSE.md), allowing anyone to use, modify, and distribute it freely for personal or commercial purposes.

<p align="right"><a href="#top">☝️</a></p>

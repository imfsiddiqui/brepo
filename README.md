<!-- markdownlint-disable MD024 MD033 MD041 -->

<a id="top"></a>

<div align=center>

🌍 **[Web Page](https://imfsiddiqui.github.io/brepo)** | 💻 **[Source Code](https://github.com/imfsiddiqui/brepo)** | 🚀 **[Releases](https://github.com/imfsiddiqui/brepo/releases)**

</div>

# 🏗️ brepo

A base template repository to quickly bootstrap new projects with preconfigured structure, essential files, and common workflows.

<div align="center">
  <img
    src="./docs/assets/brepo-banner.svg"
    style="border-radius: 10px"
    alt="brepo-banner"
  />
</div>

## 📚 Table of Contents

- [🏗️ brepo](#️-brepo)
  - [📚 Table of Contents](#-table-of-contents)
  - [📌 About](#-about)
  - [🧠 Philosophy](#-philosophy)
  - [🔑 Key Features](#-key-features)
  - [🗂️ Directory Structure](#️-directory-structure)
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

- **Comprehensive Project Structure:** Organized directories for automation: `.github`, documentation: `docs`, and GitHub Pages: `pages`, supporting scalable and maintainable projects.
- **Ready-to-Use Essential Files:** Includes ready to use following essential files to enforce best practices from the start.
  - `.editorconfig`
  - `.gitignore`
  - `README.md`
  - `docs/CHANGELOG.md`
  - `docs/CODE-OF-CONDUCT.md`
  - `docs/CONTRIBUTING.md`
  - `docs/LICENSE.md`
  - `docs/ROADMAP.md`
  - `docs/SECURITY.md`
  - `docs/TODO.md`
- **Documentation-First Workflow:** Markdown templates making it easy to maintain high-quality documentation.
- **Jekyll Documentation Site:** The `pages/` directory is preconfigured for Jekyll, enabling instant publishing of project docs to GitHub Pages.
- **Automated CI/CD:** Includes reusable GitHub Actions workflows for CI/CD, automated documentation deployment, streamlining development and release processes.
- **Copilot Commit Guidance:** Conventional Commits instructions for Copilot and VS Code integration, ensuring consistent commit messages.
- **Customization Friendly:** All configuration files and templates are easy to modify for specific needs and workflows.
- **VS Code Workspace Support:** Predefined workspace and editor settings for a consistent development experience.

<p align="right"><a href="#top">☝️</a></p>

## 🗂️ Directory Structure

The repository is organized for rapid bootstrapping, automation, and documentation-driven development.

💡 **Note:** *`.gitkeep` files ensure empty directories are tracked by Git.*

```console
.
├── .editorconfig
├── .gitignore
├── brepo.code-workspace
├── README.md
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
├── docs/
│   ├── .gitkeep
│   ├── CHANGELOG.md
│   ├── CODE-OF-CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── LICENSE.md
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

## 🏆 Use Cases

- **Rapid Prototyping:** Quickly spin up new repositories for experiments, prototypes, or MVPs with a solid foundation.
- **Standardize Projects:** Standardize project structure and workflows to reduce initialization time and improve productivity.
- **Open Source Projects:** Ensure new open source repositories follow best practices for documentation, licensing, and automation from day one.

<p align="right"><a href="#top">☝️</a></p>

## 📜 License

This project is licensed under the MIT License, allowing anyone to use, modify, and distribute it freely for personal or commercial purposes.

<p align="right"><a href="#top">☝️</a></p>

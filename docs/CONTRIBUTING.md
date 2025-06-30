<!-- markdownlint-disable MD033 MD041 -->

<a id="top"></a>

# 🤝 Contribution Guidelines

Thank you for your interest in contributing! We welcome all kinds of contributions to this project whether it's reporting bugs, suggesting features, improving documentation, or submitting code.

## 📚 Table of Contents

- [🤝 Contribution Guidelines](#-contribution-guidelines)
  - [📚 Table of Contents](#-table-of-contents)
  - [📜 Code of Conduct](#-code-of-conduct)
  - [📝 How to Contribute](#-how-to-contribute)
    - [🐛 Reporting Bugs](#-reporting-bugs)
    - [✨ Suggesting Features](#-suggesting-features)
    - [🛠️ Submitting Changes](#️-submitting-changes)
      - [🔀 Pull Request Process](#-pull-request-process)
  - [📜 License](#-license)

<p align="right"><a href="#top">☝️</a></p>

## 📜 Code of Conduct

Please read our [Code of Conduct](CODE-OF-CONDUCT.md) to keep our community welcoming and inclusive.

<p align="right"><a href="#top">☝️</a></p>

## 📝 How to Contribute

### 🐛 Reporting Bugs

- Search [issues](https://github.com/imfsiddiqui/brepo/issues) to check if the bug is already reported.
- Open a new issue with a clear title and detailed description.
- Include steps to reproduce, expected behavior, and screenshots if possible.

### ✨ Suggesting Features

- Search [issues](https://github.com/imfsiddiqui/brepo/issues) for similar feature requests.
- Open a new issue describing your idea, its use case, and possible alternatives.

### 🛠️ Submitting Changes

- **Fork** the repository.
- **Clone** your fork: `git clone https://github.com/<your-username>/brepo.git`.
- **Create a branch** for your change:
  - Branch name must follow the convention: `{type}/your-branch-name`, where `{type}` is one of following:
    - `build` - Changes that affect the build system or external dependencies
    - `chore` - Maintenance tasks not affecting main code
    - `ci` - Changes to CI configuration files and scripts
    - `docs` - Documentation-only changes
    - `feat` - New features
    - `fix` - Bug fixes
    - `perf` - Changes that improve performance
    - `refactor` - Code changes that neither fix bugs nor add features
    - `revert` - Reverting a previous commit
    - `style` - Code style, formatting, missing semicolons, etc.
    - `test` - Adding or updating tests
  - The branch name after `{type}/` should be all in lowercase, words separated by dashes (`-`).  
    - Example: `feat/add-login-endpoint`, `fix/typo-in-readme`
- **Make your changes** and **add tests** if applicable.
- **Commit** your changes which **must** follow the [Conventional Commits](https://www.conventionalcommits.org/) format with emoji prefixes. See [.github/copilot/commit-instructions.md](/.github/copilot/commit-instructions.md) for details.
- **Push** to your fork and **open a pull request**.

#### 🔀 Pull Request Process

- Ensure your branch is up to date with `main`.
- Describe your changes and reference related issues.
- The maintainers will review your PR and may request changes.
- Once approved, your PR will be merged.

<p align="right"><a href="#top">☝️</a></p>

## 📜 License

By contributing, you agree that your contributions will be licensed under the [MIT License](https://github.com/imfsiddiqui/brepo/blob/main/LICENSE.md).

<p align="right"><a href="#top">☝️</a></p>

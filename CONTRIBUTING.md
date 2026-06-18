# Contributing to Zensical Demo

Thanks for your interest in contributing! This document provides guidelines and instructions for contributing.

## Getting Started

### Prerequisites

- Python 3.8+
- Git

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/rhirschmann/ZenDemo.git
   cd ZenDemo
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment**
   - **Windows (PowerShell)**
     ```powershell
     .venv\Scripts\Activate.ps1
     ```
   - **macOS/Linux**
     ```bash
     source .venv/bin/activate
     ```

4. **Install Zensical**
   ```bash
   pip install zensical
   ```

5. **Start the development server**
   ```bash
   zensical serve
   ```
   The site will be available at `http://127.0.0.1:8000`

## Making Changes

### Documentation Changes

1. Edit files in the `docs/` directory using Markdown
2. Changes will hot-reload in the development server
3. Preview your changes before submitting

### Workflow

1. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Edit documentation files
   - Test locally with `zensical serve`

3. **Commit your changes**
   ```bash
   git commit -m "Add: brief description of changes"
   ```

4. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request**
   - Describe your changes clearly
   - Reference any related issues

## Commit Message Guidelines

Use clear, descriptive commit messages:

- `Add:` — New features or content
- `Fix:` — Bug fixes
- `Update:` — Updates to existing content
- `Remove:` — Deletions
- `Docs:` — Documentation improvements
- `Style:` — Formatting changes
- `Refactor:` — Code reorganization

Example:
```
Add: Getting started guide for local development
```

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you're expected to uphold this code.

## Questions or Issues?

- Open a [GitHub Issue](https://github.com/rhirschmann/ZenDemo/issues) for bugs or suggestions
- For questions, use [GitHub Discussions](https://github.com/rhirschmann/ZenDemo/discussions)

## License

By contributing, you agree that your contributions will be licensed under the same license as this project.

---

Thank you for helping improve the Zensical Demo! 🎉

# Zensical Demo

A clean demonstration site built using **Zensical**, a modern static site generator for beautiful documentation.

[![Live Site](https://img.shields.io/badge/Live%20Site-Online-brightgreen)](https://rhirschmann.github.io/ZenDemo/)
![Version](https://img.shields.io/badge/version-0.1.0-blue)
![License](https://img.shields.io/github/license/rhirschmann/ZenDemo)
![Last Commit](https://img.shields.io/github/last-commit/rhirschmann/ZenDemo)
![Repo Size](https://img.shields.io/github/repo-size/rhirschmann/ZenDemo)
![Issues](https://img.shields.io/github/issues/rhirschmann/ZenDemo)
![Stars](https://img.shields.io/github/stars/rhirschmann/ZenDemo)

## Quick Start

### Local Development

1. **Clone the repository**
	```bash
	git clone https://github.com/rhirschmann/ZenDemo.git
	cd ZenDemo
	```

2. **Create and activate virtual environment**
	```bash
	python -m venv .venv
	.venv\Scripts\Activate.ps1  # Windows PowerShell
	source .venv/bin/activate  # macOS/Linux
	```

3. **Install Zensical**
	```bash
	pip install zensical
	```

4. **Start development server**
	```bash
	zensical serve
	```
	Visit `http://127.0.0.1:8000` to see your site

5. **Build for production**
	```bash
	zensical build --clean
	```

## Project Structure

```
ZenDemo/
├── .github/
│   ├── workflows/           # GitHub Actions CI/CD
│   └── templates/           # Issue & PR templates
├── .vscode/                 # VS Code settings
├── docs/
│   ├── about/               # About Zensical
│   ├── features/            # Features showcase
│   ├── getting-started/     # Setup guides
│   └── index.md             # Home page
├── site/                    # Generated static site
├── CONTRIBUTING.md          # Contribution guidelines
├── CODE_OF_CONDUCT.md       # Community standards
├── CHANGELOG.md             # Version history
├── README.md                # This file
└── zensical.toml            # Zensical configuration
```

## Features

- ✨ **Modern Design** — Beautiful, responsive themes
- 🚀 **Fast** — Lightning-quick builds and loads
- 📝 **Markdown** — Rich extensions for powerful content
- 🎨 **Themes** — Multiple variants (modern, classic)
- 🔍 **Search** — Full-text search built-in
- 🌙 **Dark Mode** — Automatic theme switching
- 📱 **Responsive** — Perfect on all devices
- ⚡ **Instant Nav** — Pre-loaded instant navigation
- 📊 **Diagrams** — Mermaid diagram support
- 🧮 **Math** — LaTeX formula rendering

## Documentation

- 📖 [Getting Started Guide](docs/getting-started/index.md)
- 🚀 [Deployment Guide](docs/getting-started/deployment.md)
- ✨ [Features Overview](docs/features/index.md)
- 📝 [Markdown Examples](docs/features/markdown.md)
- 🧩 [Component Showcase](docs/features/components.md)
- ℹ️ [About Zensical](docs/about/index.md)

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](docs/contributing.md) for guidelines.

## Community

- 💬 [Discussions](https://github.com/rhirschmann/ZenDemo/discussions)
- 🐛 [Issues](https://github.com/rhirschmann/ZenDemo/issues)
- 📝 [Code of Conduct](docs/code-of-conduct.md)

## Deployment

This project uses **GitHub Actions** for automatic deployment to **GitHub Pages**.

- **Trigger:** Push to `main` branch or manual workflow dispatch
- **Status:** See [Actions](https://github.com/rhirschmann/ZenDemo/actions) tab
- **Live Site:** https://rhirschmann.github.io/ZenDemo/

For detailed deployment instructions, see [Deployment Guide](docs/getting-started/deployment.md).

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) file for details.

## Author

**Ruud Hirschmann** — [GitHub](https://github.com/rhirschmann)


# Getting Started

This guide helps you set up, run, and deploy your Zensical site.

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git (for version control)

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/rhirschmann/ZenDemo.git
cd ZenDemo
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Virtual Environment

=== "Windows (PowerShell)"

    ```powershell
    .venv\Scripts\Activate.ps1
    ```

=== "Windows (Command Prompt)"

    ```cmd
    .venv\Scripts\activate.bat
    ```

=== "macOS / Linux"

    ```bash
    source .venv/bin/activate
    ```

### 4. Install Zensical

```bash
pip install zensical
```

## Running the Development Server

Start the development server with hot-reload:

```bash
zensical serve
```

The site will be available at:
```
http://127.0.0.1:8000
```

Changes to documentation files will automatically reload in your browser.

## Building for Production

Generate the static site:

```bash
zensical build --clean
```

Output will be in the `site/` directory.

## Deployment

This project uses GitHub Actions to automatically build and deploy to GitHub Pages.

Deployments trigger automatically on:
- Push to `main` branch
- Manual workflow dispatch from GitHub

See [Deployment Guide](deployment.md) for detailed instructions.

## Troubleshooting

### Python not found

If you see `command not found: python`, you may need to use `python3` instead:

```bash
python3 -m venv .venv
```

### Virtual environment won't activate

Ensure you're in the project directory and that the path is correct for your OS.

### Port 8000 already in use

The development server will automatically use the next available port. Check the console output for the actual URL.

### Build fails

Try cleaning the cache:

```bash
zensical build --clean
```

---

**Next Steps:**
- Explore the [Features](../features/) section
- Check out [Markdown Examples](../features/markdown.md)
- See [About Zensical](../about/)

# Deployment Guide

Learn how to deploy your Zensical site to GitHub Pages or other platforms.

## GitHub Pages Deployment

### Automatic Deployment (Recommended)

This project is configured with GitHub Actions for automatic deployment.

**How it works:**

1. You push changes to the `main` branch
2. GitHub Actions runs the build workflow (`.github/workflows/gh-pages.yml`)
3. The static site is built using Zensical
4. The built site is deployed to GitHub Pages

**No manual steps required!**

### Manual Deployment

If you prefer to deploy manually:

1. **Build your site locally:**
   ```bash
   zensical build --clean
   ```

2. **The `site/` directory now contains your static site**

3. **Deploy to your hosting platform:**
   - GitHub Pages
   - Netlify
   - Vercel
   - Traditional web hosting

## GitHub Pages Settings

Ensure your repository is configured correctly:

1. Go to **Settings** → **Pages**
2. Set **Source** to `Deploy from a branch`
3. Set **Branch** to `gh-pages`
4. Set **Folder** to `/ (root)`
5. Click **Save**

Your site will be available at:
```
https://rhirschmann.github.io/ZenDemo/
```

## Viewing Deployment Status

1. Go to the **Actions** tab in your repository
2. Select the **Deploy Zensical site to GitHub Pages** workflow
3. Watch the build process

## Troubleshooting Deployment

### Site not updating after push

- Check the **Actions** tab for workflow errors
- Ensure you're pushing to the `main` branch
- Clear your browser cache (Ctrl+Shift+Delete)

### Workflow fails

1. Check the workflow logs in **Actions**
2. Verify Python 3.12 is available
3. Ensure dependencies are installed correctly

### Custom domain setup

See [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

**Questions?** Open an issue on [GitHub](https://github.com/rhirschmann/ZenDemo/issues)

# Bishal Shrestha | WordPress Plugin Developer

Personal portfolio website built with Hugo and PaperMod theme.

## Local Development

1. Install Hugo (if not already installed):
   ```bash
   brew install hugo
   ```

2. Install the PaperMod theme:
   ```bash
   git submodule add --depth=1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
   git submodule update --init --recursive
   ```

3. Run the development server:
   ```bash
   hugo server
   ```

4. Visit `http://localhost:1313` in your browser.

## Deployment

This site is automatically deployed to GitHub Pages via GitHub Actions when you push to the `main` branch.

## Structure

- `content/` - Content files (markdown)
- `static/` - Static files (CSS, images, etc.)
- `layouts/` - Custom layout overrides
- `config.yaml` - Hugo configuration
- `themes/PaperMod/` - PaperMod theme (git submodule)

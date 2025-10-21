# Portfolio Website

This is a React portfolio website built with Vite, TypeScript, and Tailwind CSS.

## GitHub Pages Deployment

This project is configured to automatically deploy to GitHub Pages when changes are pushed to the main branch.

### Setup Instructions

1. **Enable GitHub Pages in your repository:**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "GitHub Actions"

2. **The deployment workflow will automatically:**
   - Build the project using Vite
   - Deploy the built files to the `gh-pages` branch
   - Make your site available at `https://yourusername.github.io/gh-pages/`

### Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Build specifically for GitHub Pages
npm run build:gh-pages
```

### Manual Deployment

If you need to deploy manually:

```bash
npm run deploy
```

This will build the project and create the necessary files for GitHub Pages deployment.

## Project Structure

- `src/` - Source code
- `public/` - Static assets
- `.github/workflows/` - GitHub Actions workflows
- `dist/` - Built files (generated)
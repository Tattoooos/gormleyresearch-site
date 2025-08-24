# Gormley Research Website

This is the source code for the Gormley Research website - an independent R&D studio dedicated to bridging the gap between science and art.

## Deployment

This site is configured for deployment via Cloudflare Pages instead of GitHub Pages.

### Disabling GitHub Pages

To disable GitHub Pages deployment:

1. Go to your repository on GitHub: https://github.com/Tattoooos/gormleyresearch-site
2. Click on the **Settings** tab
3. Scroll down to the **Pages** section in the left sidebar
4. Under "Source", select **"None"** from the dropdown
5. Click **Save**

### Setting up Cloudflare Pages

1. Log in to your Cloudflare dashboard
2. Go to **Pages** in the left sidebar
3. Click **"Create a project"**
4. Connect your GitHub account and select this repository
5. Configure the build settings:
   - Framework preset: **None**
   - Build command: *Leave empty*
   - Build output directory: **/** (root directory)
6. Click **"Save and Deploy"**

The site will be deployed to a `*.pages.dev` domain, and you can configure a custom domain in the Cloudflare Pages settings.

## Site Structure

- `index.html` - Main website page
- `.nojekyll` - Prevents GitHub Pages from processing the site with Jekyll
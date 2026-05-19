# ZoneIQ Web

Source files for the ZoneIQ marketing and legal site. **Deploy to:** [github.com/Wim90/ZoneIQ_site](https://github.com/Wim90/ZoneIQ_site) (public). The macOS app lives in the private [ZoneIQ](https://github.com/Wim90/ZoneIQ) repo — do not publish web files there.

## GitHub Pages Deployment

This repository is configured to be published via GitHub Pages. The `index.html` file will be served as the main page.

### Setup Instructions

1. **Push the files to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: ZoneIQ web page"
   git branch -M main
   git remote add origin https://github.com/Wim90/ZoneIQ_site.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub: https://github.com/Wim90/ZoneIQ_site
   - Click on **Settings** (in the repository navigation)
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select:
     - **Branch:** `main`
     - **Folder:** `/ (root)`
   - Click **Save**

3. **Access your site:**
   - Your site will be available at: `https://wim90.github.io/ZoneIQ_site/`
   - It may take a few minutes for the site to be published after enabling Pages

**Live site:** https://wim90.github.io/ZoneIQ_site/  
**Repository:** https://github.com/Wim90/ZoneIQ_site

### File Structure

```
ZoneIQ_site/
├── index.html          # Main web page
├── .nojekyll          # Prevents Jekyll processing (for static HTML)
└── README.md          # This file
```

### Notes

- The `.nojekyll` file ensures GitHub Pages serves the static HTML file directly without Jekyll processing
- The site uses pure HTML, CSS, and JavaScript (no build process required)
- All styling and functionality is self-contained in `index.html`

### Updating the Site

Simply push changes to the `main` branch and GitHub Pages will automatically update the site within a few minutes.

```bash
git add .
git commit -m "Update web page"
git push
```

## Support

For questions about ZoneIQ, please email: christophe@wimsightlabs.com

---

**Disclaimer:** ZoneIQ is an independent third-party application and is not affiliated with, endorsed by, or sponsored by Orangetheory Fitness®.


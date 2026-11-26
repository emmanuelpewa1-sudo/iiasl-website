# IIASL Website

A responsive, static multi-page website for the Indigenous Importers Association SL (IIASL).

## Pages
- Home
- About
- Gallery
- Dinner
- Stories

## Run locally
Open `index.html` in a browser. No build step or package installation is required.

## Publish with GitHub Pages
1. Create a new GitHub repository (for example, `iiasl-website`).
2. Extract this project folder and open a terminal inside it.
3. Run:

```bash
git init
git add .
git commit -m "Build IIASL website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/iiasl-website.git
git push -u origin main
```

4. On GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then Save.
7. GitHub Pages will publish the site at `https://YOUR-USERNAME.github.io/iiasl-website/`.

Replace `YOUR-USERNAME` and the repository name with your actual GitHub details.

## Updating the website
Edit the HTML files and the shared stylesheet in `assets/styles.css`. Add gallery photos to `assets/` and replace the placeholder tiles in `gallery.html` when images are ready.

## Notes
- The association logo supplied for this project is in `assets/iiasl-logo.jpg`.
- About, Gallery and Stories currently contain editable starter content/placeholders.
- The dinner programme and menu use the details supplied for the 27 November 2026 event.

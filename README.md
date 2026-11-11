# Shanthosh — Creative Portfolio

A responsive, single-page creative portfolio built with plain HTML, CSS and JavaScript. It is ready for GitHub Pages and does not require a build step.

## Included
- `index.html` — page structure and content
- `style.css` — responsive dark cinematic styling
- `script.js` — mobile navigation and current year
- `assets/portrait.png` — supplied neon portrait used in the hero
- `assets/favicon.svg` — site icon

## Before publishing
1. Open `index.html`.
2. Replace `your.email@example.com` with your real email address.
3. Update Instagram, LinkedIn and Behance URLs to your own profiles (or remove links you do not use).
4. Replace the three sample project cards with your real work. They are clearly marked as placeholders; add your own project screenshots and links before sharing the site.
5. If you want a different hero image, replace `assets/portrait.png` with your own image using the same filename.

## Publish with GitHub Pages
1. Sign in at https://github.com and create a new **public** repository. Suggested name: `shanthosh-portfolio`.
2. On the repository page, choose **Add file → Upload files**.
3. Upload the contents of this folder (upload `index.html`, `style.css`, `script.js`, and the `assets` folder; do not upload only the ZIP file).
4. Commit the files to the `main` branch.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Set the branch to **main** and folder to **/(root)**, then click **Save**.
8. Wait a few minutes. Your site will be available at:
   `https://YOUR-GITHUB-USERNAME.github.io/shanthosh-portfolio/`

If you name the repository exactly `YOUR-GITHUB-USERNAME.github.io`, GitHub Pages will publish it at the root URL:
`https://YOUR-GITHUB-USERNAME.github.io/`

## Local preview
Open `index.html` in a browser. For a local server, run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Notes
- This is a static site. No server, database, paid hosting or framework is required.
- The Google Fonts connection requires internet access; system fallbacks are included.
- GitHub Pages is free for public repositories.


## Animated hero background

The `assets/portrait-background.mp4` file is made from the 238 portrait frames you supplied. It plays silently, loops automatically, and sits behind the hero content with a dark purple overlay for text readability. GitHub Pages serves this MP4 as a normal static asset.

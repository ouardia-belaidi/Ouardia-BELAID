# Ouardia Belaidi — Portfolio

A responsive, dark, technical portfolio built with plain HTML, CSS, and JavaScript. No framework or build step is required.

## Files

- `index.html` — content and page structure
- `styles.css` — responsive styling, layouts, and project illustrations
- `script.js` — mobile navigation, project filters, reveal effects, and copy-email interaction
- `assets/` — add your CV PDF, project screenshots, and any other media here

## Before publishing

Please review and personalize these items:

1. **LinkedIn link:** replace the generic LinkedIn URL in `index.html` with your actual profile URL.
2. **GitHub link:** check that `https://github.com/ouardia-belaidi` is the correct public profile URL.
3. **CV:** add your latest CV as `assets/Ouardia-Belaidi-CV.pdf`, then add a CV download link to the hero if desired. The current page intentionally does not link to a non-existent file.
4. **Projects:** add verified repository/demo links when you are ready to share them publicly. The current project cards invite visitors to contact you rather than using fabricated links.
5. **Email and location:** confirm that the displayed contact details are the ones you want public.
6. **Thesis claims:** keep the edge-deployment wording only if it accurately reflects the feasibility assessment you performed. It does not claim deployment on physical edge hardware.

## Preview locally

Open `index.html` directly in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to your existing GitHub Pages project

This is a project site at `https://ouardia-belaidi.github.io/MyPortfolio/`, so keep the files at the root of the repository and preserve relative paths (`styles.css`, `script.js`, `assets/...`).

1. Download and unzip the portfolio folder.
2. Open your `MyPortfolio` repository on GitHub, or clone it locally.
3. Replace the old site files with the contents of this folder. Keep any existing media you still need.
4. Commit and push to the branch currently configured for GitHub Pages (often `main`).
5. In the repository, open **Settings → Pages** and confirm the publishing source is correct (for example, `main` and `/ (root)`).
6. Wait for the Pages deployment to complete in the **Actions** tab, then open the site and hard-refresh the browser.

If you prefer Git from your computer, from the repository folder:

```bash
git add .
git commit -m "Redesign portfolio"
git push
```

Do not run these commands from the extracted folder unless it is already your cloned `MyPortfolio` repository. The static site needs no package installation or build command. GitHub Pages publishes static HTML, CSS, and JavaScript files directly.

## Accessibility and responsiveness

- Semantic page sections and navigation labels
- Mobile navigation with `aria-expanded`
- Visible keyboard-focus support from browser defaults
- Reduced-motion preference support
- Responsive layout for mobile, tablet, and desktop
- Project filter controls

## Notes

- The site uses Google Fonts with system fallbacks; the rest of the layout and project illustrations are CSS/SVG-based.
- This is a static site. A contact form would require a third-party service or backend; the current contact section uses email links instead.

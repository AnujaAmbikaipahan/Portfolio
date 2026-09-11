# Anuja Ambikaipahan — Digital Portfolio

## Run locally
Open `index.html` in a browser.

## GitHub Pages Setup
1. Upload all files from this folder directly to your GitHub repository root:
   - `index.html`
   - `style.css`
   - `script.js`
   - `profile.jpg`
   - `README.md`
2. Go to **Settings → Pages** in your repository.
3. Select the branch containing `index.html` (e.g. `main` or `master`) and save.
4. Your portfolio will render correctly with the profile photo visible!

### Reason for Fix
Websites running on GitHub Pages cannot access local Windows directory paths (like `C:\Users\Anuja\...`). The image tag now uses the relative link `profile.jpg` stored in the same repository folder.

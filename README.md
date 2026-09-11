# Anuja Ambikaipahan — GitHub Pages Portfolio

## EXACT GitHub setup

Your repository root MUST look like this:

    index.html
    style.css
    script.js
    README.md
    assets/
        profile.jpg

Do NOT put the files inside another nested folder.

### Uploading to GitHub

1. Open your GitHub repository.
2. Click **Add file → Upload files**.
3. Open the extracted `Anuja_Digital_Portfolio` folder on your computer.
4. Select `index.html`, `style.css`, `script.js`, `README.md` AND the `assets` folder contents.
5. Commit the changes.
6. Go to **Settings → Pages**.
7. Under Build and deployment, choose **Deploy from a branch**.
8. Select your branch (normally `main`) and folder `/ (root)`.
9. Save and wait for deployment.

### PHOTO CHECK

After GitHub uploads the files, click:

`assets` → `profile.jpg`

The image must open directly on GitHub.

Then your website must use this exact HTML path:

    <img src="./assets/profile.jpg" ...>

Do NOT use a Windows path such as:

    C:\Users\Anuja\Desktop\Anuja

Do NOT rename `profile.jpg` to `Profile.jpg` or `profile.jpeg`. GitHub Pages is case-sensitive.

### If the old website is still shown

GitHub Pages/browser caching can show an older version. After deployment:
- Wait a few minutes.
- Open the GitHub Pages URL in an Incognito/Private window.
- Hard refresh with Ctrl + F5.

This version also keeps the profile photo visible even if the animation JavaScript has not loaded yet.

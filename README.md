# Srinidhi Srinivasan — Portfolio Website

A responsive, static portfolio created from the supplied résumé. It uses plain HTML, CSS and JavaScript, so there is no build step, framework installation or server required.

## Preview on your computer

1. Extract `srinidhi-portfolio.zip`.
2. Open `index.html` in your browser.
3. For a local web-server preview, run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish it quickly with Netlify Drop

1. Open <https://app.netlify.com/drop>.
2. Sign in if you want the site saved to your account and easily updateable.
3. Drag the **extracted `srinidhi-portfolio` folder** into the drop area. The folder should contain `index.html`, `styles.css`, `script.js` and `assets/` at its top level.
4. Netlify will provide a URL ending in `netlify.app`. Open that URL in an incognito/private window to verify that it is publicly accessible, then share it.
5. To update the site later, upload the updated folder through your site's manual deploy area.

**Privacy check:** The website intentionally displays the email address and phone number in your résumé and includes your résumé PDF as a public download. Remove or edit those details in `index.html` and/or replace `assets/Srinidhi-Srinivasan-Resume.pdf` before publishing if you do not want them public.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `srinidhi-portfolio`.
2. Upload the **contents** of this folder (so `index.html` is at the repository root) and commit them to the `main` branch.
3. In the repository, open **Settings → Pages**.
4. Under the build and deployment settings, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Wait for the Pages deployment to finish. GitHub will show the public site URL in **Settings → Pages**. A project site usually looks like `https://YOUR-USERNAME.github.io/srinidhi-portfolio/`.

GitHub Pages sites are public on the internet. Make sure the repository contains only the files you are comfortable sharing.

## Customize

- Update content, links, contact details and dates in `index.html`.
- Change colors, spacing and responsive layouts in `styles.css`.
- Change navigation/scroll behavior in `script.js`.
- Replace `assets/srinidhi-profile.png` if you prefer another profile photo.
- Replace the PDF at `assets/Srinidhi-Srinivasan-Resume.pdf` when your résumé changes.

## Notes

- There is no contact form backend; the email link opens the visitor's email app.
- The website links to LinkedIn and GitHub based on the URLs provided in the résumé. Project source-code/demo URLs were not provided, so the portfolio does not invent them.
- Font loading uses Google Fonts when available, with system-font fallbacks.

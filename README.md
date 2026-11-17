# Mobile-first project — GitHub Pages deployment

This folder is ready to publish as a static GitHub Pages site.

## Files

- `index.html` — the complete project, including the quiz engine and all five embedded images. It is intentionally self-contained; the quiz does not need a separate JavaScript file.
- `phone-test.html` — a small test page for checking JavaScript and touch input on the published phone URL.
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing on this static site.

## Publish it

1. Extract this ZIP on your computer.
2. Open the GitHub repository where the project should live.
3. Upload **the contents of this folder** to the repository's top level (repository root). In particular, `index.html` must be at the top level, not inside another folder.
4. Commit the upload to the repository's main branch (or its default branch).
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the default branch (commonly `main`) and the `/(root)` folder, then save.
8. Wait for the Pages deployment to finish. In **Settings → Pages**, open the **Visit site** link to get the live website address.

## QR code — use the website address, not the repository address

A repository address looks like:

`https://github.com/USERNAME/REPOSITORY`

That is the code/files page, not the published website. Do **not** use it in the QR code.

A GitHub Pages project-site address normally looks like:

`https://USERNAME.github.io/REPOSITORY/`

Use the exact address shown by **Settings → Pages → Visit site**. Put that published website address into your QR-code generator. If the repository itself is named `USERNAME.github.io`, the site address is normally `https://USERNAME.github.io/`.

## Check on your phone

1. Scan the QR code and confirm the address bar shows the GitHub Pages website address (`...github.io/...`) or your configured custom domain.
2. To check the phone/browser separately, visit the same site address plus `phone-test.html`, for example:
   `https://USERNAME.github.io/REPOSITORY/phone-test.html`
3. The page should show **READY** and each tap should increase the counter.
4. Then open the site's root address, scroll to the quiz and test it.

The published site is served over HTTPS. Open it in Chrome or Safari as a normal website, not a repository file preview. The QR code should point to the Pages URL.

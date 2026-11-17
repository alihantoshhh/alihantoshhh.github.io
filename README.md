# Ali Hantosh — Complete GitHub Pages Website

A complete, static, responsive personal portfolio created **from zero**. All files are included and it needs **no npm, Astro, Node.js, backend, domain purchase or extra setup**.

## What is included?

| File | Purpose |
| --- | --- |
| `index.html` | Complete homepage and sections |
| `style.css` | All website styling / mobile responsive layout / dark theme |
| `script.js` | Navigation, language change, theme, galleries, modal details |
| `resume.html` | Printable résumé (browser Print → Save as PDF) |
| `404.html` | Friendly missing-page screen |
| `favicon.svg` | Browser icon |
| `hero-collage.jpg` | Homepage illustration |
| `sonar-lab.jpg`, `robotic-hand.jpg`, `fpga-lab.jpg`, `gearbox.jpg`, `campus.jpg`, `chongqing.jpg` | Project / education illustrations |
| `personal-01.jpg`–`personal-06.jpg` | Fully working personal gallery sample photos |
| `PHOTO_GUIDE.txt` | Instructions for replacing example photos with real photos |
| `.nojekyll` | Disables automatic Jekyll processing |
| `robots.txt`, `sitemap.xml` | Basic search metadata |

**All assets are included locally.** The sample images are illustrations and are **not** photos of the site owner's actual projects or experiences.

## A. If your old GitHub repository is gone (START HERE)

1. Go to **https://github.com/** and sign in as `alihantoshhh`.
2. Click the **+** menu at the upper-right and choose **New repository** (or open https://github.com/new).
3. Set **Owner** to `alihantoshhh`.
4. Enter this **exact** repository name: `alihantoshhh.github.io`.
5. Select **Public**. Set **Add a README file** to **Off**, so the new repository starts empty.
6. Click **Create repository**.
7. Open your unzipped website folder on Windows. It must contain `index.html` and `style.css` at its top level.
8. In your new GitHub repository, click **uploading an existing file**. If that link is absent, choose **Add file → Upload files**.
9. Select **ALL FILES INSIDE the extracted folder** and drag them into the upload area. **Do not upload the ZIP file itself. Do not upload the outer folder as one folder.** You need `index.html`, `style.css`, and all JPGs at the root of the repository.
10. Scroll down and click **Commit changes**. Use `main` as the branch.
11. Open your repository's **Settings → Pages**.
12. Under **Build and deployment**, choose **Deploy from a branch**. Select **main** and **/(root)**, then **Save**.
13. Check the **Actions** tab if you want to watch the Pages deployment. When it succeeds, open **https://alihantoshhh.github.io/** and refresh with **Ctrl+Shift+R**.

If GitHub says the name is already taken under your account, the repository already exists; follow section B instead. **Do not name the repository `alihantoshhh.github.io.github.io` or `.github.io`.**

## B. If the repository already exists but the old site was deleted

1. Go to **https://github.com/alihantoshhh/alihantoshhh.github.io**.
2. Ensure you are on the `main` branch. If there is old content, back it up and remove old files that would conflict (especially old `index.html`, broken CSS paths, or an old `CNAME`).
3. Click **Add file → Upload files**, select **all the extracted website files** from this ZIP and **Commit changes**.
4. Go to **Settings → Pages** and choose **Deploy from a branch → main → /(root)**, **Save**.
5. Confirm that `index.html`, `style.css`, `script.js`, and the photographs are directly visible at the TOP LEVEL of the repository, not inside a nested folder such as `Ali_Hantosh_Complete_GitHub_Website/`.
6. Open **https://alihantoshhh.github.io/** after deployment. Use **Ctrl+Shift+R** if your browser shows a cached old page.

### Important if you previously used Astro / GitHub Actions

This new site is *plain HTML*. You should **not** select an old Astro publishing workflow. If a prior workflow exists in `.github/workflows`, remove/disable that old workflow or set Pages to **Deploy from a branch** on `main`, `/(root)`.

### Important if you previously tried a custom domain

**Do not add a `CNAME` file** unless you own and configured that domain correctly. This package does not include one. `https://alihantoshhh.github.io/` works without buying a domain.

## C. How to preview on your laptop before uploading

Double-click `index.html` in the extracted folder. Because this is a static HTML website, the homepage, styling, images and interactive controls work without a build process or web server. Double-click `resume.html` to inspect the résumé.

## D. Personal photographs

Read `PHOTO_GUIDE.txt`. Replace `personal-01.jpg` to `personal-06.jpg` with your own six JPGs using **exactly the same filenames**. You can also replace project image files with actual hardware photos.

## E. Edit your bio and projects

Open `index.html` in VS Code or Notepad and change the text. The Chinese/English navigation translations and project details are in `script.js` under `translations` and `entries`.

- Your GitHub profile is set to https://github.com/alihantoshhh.
- There is no invented email, LinkedIn profile or published journal paper.
- Your résumé is HTML; use the **Print / Save as PDF** button to create a PDF locally if needed.

## F. If the website is unstyled or images are missing

Check these exact URLs **after deployment**:

- https://alihantoshhh.github.io/style.css
- https://alihantoshhh.github.io/script.js
- https://alihantoshhh.github.io/sonar-lab.jpg

If any show `404`, the files were not uploaded to the correct root directory or Pages is publishing a different branch/folder. Fix the repo structure before changing code.

GitHub official documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

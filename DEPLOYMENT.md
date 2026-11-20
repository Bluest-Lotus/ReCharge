# GitHub Pages deployment

1. Upload all files in this project to the root of your GitHub repository.
2. Open **Settings → Pages** and choose **Deploy from a branch**, `main`, `/(root)`.
3. In `site-config.js`, optionally set `repository` to `OWNER/REPOSITORY` and `branch` to your default branch. GitHub Pages can usually detect the repository automatically.
4. Visit the published URL. Open any page and click **Edit this page on GitHub** to test.

The site uses plain HTML/CSS/JavaScript and Markdown files. No build pipeline or third-party library is required. GitHub Pages hosts the site; GitHub's web editor handles contributions.

For local preview, run `python -m http.server 8000` in the project folder and open `http://localhost:8000`. Do not open the HTML via `file://` because browser security blocks Markdown fetches.

For safer collaboration, configure repository rules to require pull requests and at least one reviewer before merging to `main`. Contributors without write access can propose changes through forks.

# portable.md — Coming soon

A responsive, self-contained static landing page. No JavaScript, external assets,
packages, or build step.

## Publish on GitHub Pages

1. Extract this ZIP and commit its contents to your repository root on `main`.
   Include the hidden `.nojekyll` file. Upload the extracted files, not the ZIP.
2. Open **Settings → Pages → Build and deployment**.
3. Select **Deploy from a branch**, choose **main** and **/(root)**, then save.
4. The included `CNAME` file sets the custom domain to `portable.md`. Configure
   the domain's DNS separately, then enable **Enforce HTTPS** when available.
   Remove `CNAME` to use the default GitHub Pages address instead.

Open `index.html` directly in a browser to preview locally.

## Files

- `index.html`: the complete coming-soon page, including CSS.
- `.nojekyll`: an empty file that skips Jekyll processing.
- `CNAME`: the custom domain, `portable.md`.
- `README.md`: these setup instructions.

## Official documentation

- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

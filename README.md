# Portfolio website

A static HTML, CSS, and image-based portfolio. No build step is required.

## Deploy to GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the repository root whenever changes are pushed to `main`. To enable it:

1. Push the website files and workflow to the `main` branch.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Check the **Actions** tab for the deployment status. Once it succeeds, the site will be available at <https://wqnguyen25.github.io/Portfolio-website/>.

The site uses relative links for its pages and assets, so it works from the project-site subpath on GitHub Pages.

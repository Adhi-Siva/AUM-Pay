# AUM Pay – Git Deployment

This is a self-contained static HTML prototype.

## Deploy using GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Commit and push to the `main` branch.
4. Open **Settings → Pages** in GitHub.
5. Choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. GitHub will display the published website URL in the Pages settings.

## Deploy under an existing website path

To publish at a path such as `https://your-domain.com/atmpay/`, put this
`index.html` inside the `atmpay` folder of your website repository, then deploy
using your existing hosting workflow.

No build command, dependencies, or package installation are required.
You can also open `index.html` directly in Chrome to test it locally.

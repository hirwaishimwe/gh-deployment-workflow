# GitHub Pages Deployment Workflow

This repository demonstrates a simple GitHub Actions workflow that automatically
deploys a static website to GitHub Pages whenever the `index.html` file changes.

## How it works
- Any push to the `main` branch that includes changes to `index.html` triggers
  the GitHub Actions workflow.
- The workflow uploads the current state of the repository as an artifact.
- The second job deploys the artifact to GitHub Pages.
- The site is then accessible at `https://<username>.github.io/gh-deployment-workflow/`.

# GitHub Pages

The Ideas Archive is published as a project site:

**https://sh20raj.github.io/ideas/**

The repository uses a GitHub Actions workflow at:

`.github/workflows/deploy.yml`

## Deployment model

1. Push changes to `main`.
2. GitHub Actions checks out the repository.
3. The workflow builds the Next.js static output.
4. The generated site is uploaded to GitHub Pages.
5. GitHub Pages publishes the project site.

GitHub Pages supports project sites at `https://<owner>.github.io/<repository>/`. See the official GitHub Pages documentation for publishing sources and Actions-based deployment.

## Important

Because this is a public site, every file that can be published should be treated as public. Do not put secrets or private contact information into the repository.

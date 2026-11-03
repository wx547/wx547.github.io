# Deployment

This repository uses Jekyll 4.4, Ruby 3.3, and a custom GitHub Actions workflow.

In the GitHub repository, perform these account-level steps once:

1. Open **Actions** and enable workflows for this fork if GitHub asks for confirmation.
2. Open **Settings → Pages**.
3. Set **Build and deployment → Source** to **GitHub Actions**.
4. Open **Actions → Build and deploy Xuan Wang's academic homepage** and run the workflow on `master`.

Do not select **Deploy from a branch**. That mode uses GitHub Pages' bundled
Jekyll 3.10, while this Academic Pages version requires Jekyll 4.4.

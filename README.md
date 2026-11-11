# Altan 3 website — English

Static website for GitHub Pages. No build tools, dependencies or installation required.

## Publish

1. Create or open the GitHub repository for the website.
2. Upload the contents of this folder to the repository root, keeping the assets folder.
3. Open Settings → Pages → Build and deployment.
4. Select Deploy from a branch, select your branch (usually main), select /(root), then Save.
5. Wait for GitHub to display the published HTTPS address and open it.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## App Store Connect fields

Use the published GitHub Pages address as the Marketing URL.
Append support.html to that address for the Support URL.
Append privacy.html to that address for the Privacy Policy URL.

All site links are relative, so the site works at both a domain root and a repository path. No domain changes are needed in the HTML.

## Contents

- index.html: marketing homepage
- support.html: controls, troubleshooting, support contact
- privacy.html: privacy policy for version 1.0
- style.css: responsive styling
- assets/: original app imagery, resized where appropriate
- .nojekyll: disables Jekyll processing

## Release status


The site has not been published. No App Store download link is displayed because the app listing URL has not been provided. The game and original Xcode project were not modified.

Privacy wording is based on the current project: local UserDefaults scores and preferences, device motion controls, no network client or third-party SDKs found. Revisit the policy whenever the app's data handling changes.

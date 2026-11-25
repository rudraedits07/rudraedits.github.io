RUDRA EDITS — GitHub Pages Prebuilt Package
===========================================

Option A (Upload Prebuilt Files — Fastest):
1. Extract this ZIP and upload ALL extracted files (index.html, 404.html,
   .nojekyll, assets/, src/) to the root of your GitHub repository.
2. In GitHub: Settings -> Pages -> Source: Deploy from a branch -> main / (root).

Option B (Push Full Source Repo):
If you push the full source repository, DO NOT deploy raw source index.html
with "Deploy from a branch". Instead set:
  Settings -> Pages -> Source: GitHub Actions
The included .github/workflows/deploy-pages.yml will automatically build and publish.

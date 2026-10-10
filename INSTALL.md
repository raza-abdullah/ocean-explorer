# Apply the OceanQuest README update

Copy `README.md` to the root of your `ocean-explorer` Git checkout.
Copy `docs/images/github-actions-artifact-upload.png` to the same relative path in your checkout.

From the repository root:

```bash
mkdir -p docs/images
# Copy README.md and screenshot into place first.
git add README.md docs/images/github-actions-artifact-upload.png
git commit -m "docs: explain GitHub Actions artifacts and offline school setup"
git push origin main
```

The README image reference is relative to the repository root and works on GitHub.

If you use GitHub's web editor instead, upload the screenshot at `docs/images/github-actions-artifact-upload.png` first, then paste the README contents into `README.md`.

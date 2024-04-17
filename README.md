# adamkurth.github.io

To build the `docs/` to deploy to GitHub Pages, run:

```bash
sphinx-build -b html source/ docs/
```

Then push to the `main` branch.

```bash
git add docs/
git commit -m "Update GitHub Pages documentation"
git push origin main
```
# ReCLIP In-the-wild PPI Report

This repository is a static GitHub Pages site for the ReCLIP in-the-wild PPI mutation-effect report.

## Publish

Create a new GitHub repository under your own account, for example:

`reclip-ppi-report`

Then run:

```bash
cd /home/jamesbondy/experiment/reclip-ppi-pages
git init
git add .
git commit -m "Publish ReCLIP PPI report"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/reclip-ppi-report.git
git push -u origin main
```

On GitHub, open the repository:

1. Go to `Settings` -> `Pages`.
2. Under `Build and deployment`, choose `Deploy from a branch`.
3. Select branch `main` and folder `/root`.
4. Save.

The report will be available at:

`https://<YOUR_GITHUB_USERNAME>.github.io/reclip-ppi-report/`

## Contents

- `index.html`: self-contained English report page with embedded chart data.
- `data/`: small summary/input files linked from the report.

Large raw inference outputs are intentionally not included in this Pages site.

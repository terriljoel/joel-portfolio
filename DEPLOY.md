# Deploy

This site is built with MkDocs Material and deployed to GitHub Pages via `mkdocs gh-deploy`.

## Prerequisites
- Windows PowerShell
- Python + pip
- GitHub repo: `https://github.com/terriljoel/joel-portfolio`

## One-time setup
From the portfolio root:
```powershell
.\activate_venv.bat
pip install -r requirements.txt
```

## Deploy
```powershell
cd .\joel-portfolio
mkdocs gh-deploy
```

That publishes the site to the `gh-pages` branch. GitHub Pages will serve it from there.

## Local preview (optional)
```powershell
cd .\joel-portfolio
mkdocs serve
```

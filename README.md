# Sensia — website

Static site: `index.html` + `assets/`. No build step.

## GitHub
```
git init
git add .
git commit -m "Sensia site"
git branch -M main
git remote add origin https://github.com/<user>/sensia-site.git
git push -u origin main
```

## Vercel
1. vercel.com → Add New → Project → import the GitHub repo.
2. Framework preset: **Other**. Build command: none. Output directory: `./`.
3. Deploy.

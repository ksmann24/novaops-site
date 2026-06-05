# NovaOps Landing Page

Simple static landing page for getnovaops.com.

## Local preview

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Normal edit/deploy workflow

```bash
# edit index.html or styles.css

git status
git add index.html styles.css assets/novaops-logo.svg vercel.json package.json README.md
git commit -m "Update NovaOps landing page"
git push
```

If connected to Vercel, pushing to `main` deploys the site.

## Primary CTA

https://fit.getnovaops.com

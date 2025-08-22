# Example Repo Structure (GitHub Pages via /docs)

This repository hosts a simple contact-card site using GitHub Pages with the **/docs** folder as the site root.

```
repo-root/
├─ README.md
└─ docs/
   ├─ .nojekyll
   ├─ index.html
   ├─ contact.vcf
   └─ download/
      └─ index.html
```

Enable Pages: Settings → Pages → "Deploy from a branch" → Branch: `main`, Folder: `/docs`.
The site will be served from the `docs` folder. The auto-download page is at `/download/`.

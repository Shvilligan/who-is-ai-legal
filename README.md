# Who Is AI Legal Site

This folder contains a standalone GitHub Pages site for legal pages.

## Files

- `index.html` - legal landing page with links
- `privacy-policy/index.html` - RU/EN privacy policy
- `terms-of-use/index.html` - RU/EN terms of use

## Quick publish flow

1. Create an empty public GitHub repository (for example: `who-is-ai-legal`).
2. Open terminal in this folder.
3. Run:

```bash
git init
git add .
git commit -m "Initial legal pages"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin main
```

4. In GitHub repository settings: `Settings -> Pages`
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

5. Site URL will be:

`https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/privacy-policy/`

Terms page:

`https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/terms-of-use/`

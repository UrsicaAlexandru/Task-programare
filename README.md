# Unplugged Lenau – mock robotics team site

A static, single-page robotics team site (HTML, CSS, vanilla JS). No build step.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Customize
- Team members: edit the `people` array at the bottom of `index.html`.
- Projects and contact details: edit the matching sections in the same file.
- Colors: change the CSS variables at the top of the `<style>` block.

## Publish to GitHub
```bash
git init
git add .
git commit -m "Add mock robotics team site"
git branch -M main
git remote add origin https://github.com/<your-org>/<your-repo>.git
git push -u origin main
```
Then enable GitHub Pages under Settings > Pages (deploy from `main`, root folder).

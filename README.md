# Academic Homepage Template

This repository is a simple academic homepage designed for GitHub Pages.

## Files

- `index.html` — homepage
- `research.html` — research programs and projects
- `publications.html` — publication list
- `cv.html` — short web CV
- `assets/css/style.css` — website style
- `assets/images/` — profile photo and research images
- `assets/files/` — downloadable CV or other files

## What to replace

Search the project for:

- `YOUR NAME`
- `your.email@example.com`
- placeholder research text
- placeholder publication entries
- Google Scholar / ORCID / GitHub links

## Profile image

Replace:

`assets/images/profile-placeholder.svg`

with your own image, for example:

`assets/images/profile.jpg`

Then change the image line in `index.html` to:

```html
<img src="assets/images/profile.jpg" class="profile-photo" alt="YOUR NAME">
```

## CV PDF

Put your CV PDF in:

`assets/files/`

For example:

`assets/files/Clancy_Wu_CV.pdf`

Then replace all instances of:

`assets/files/YOUR_NAME_CV.pdf`

with the correct filename.

## GitHub Pages

For a personal GitHub Pages site, your repository should be named:

`YOUR_GITHUB_USERNAME.github.io`

Then enable GitHub Pages in:

Settings → Pages → Deploy from a branch → main → /(root)

## Editing workflow

After updating files locally:

```bash
git add .
git commit -m "Update homepage"
git push
```

GitHub Pages will publish the updated site automatically.

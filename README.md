# Joshua Conge's portfolio

Plain HTML and one stylesheet, no build step. Open `index.html` in a browser and that is the site.

```
index.html       front page
projects.html    index of all projects
resume.html      résumé
style.css        the only stylesheet
img/  media/     pictures, slides, video
files/           report and résumé PDFs
projects/        one page per project
```

## Adding a project
1. Copy a file in `projects/`, rename it, and edit the title, tags, and text.
2. Add its link to the sidebar's Projects list in every page (search for an existing project name to find the spot).
3. Add a card for it in `projects.html`, and in `index.html` if it belongs in the selected work.

Photos go in `img/`, PDFs in `files/`.

## Deploying (GitHub Pages)
Settings, then Pages, then Deploy from a branch, `main`, `/ (root)`. `index.html` must be at the top level of the repository.

# Anastasios Latsoudis — academic site

Personal academic page built with [al-folio](https://github.com/alshedivat/al-folio).

Live URL after GitHub Pages is enabled: [https://alats99.github.io](https://alats99.github.io)

## Preview locally

Docker is the supported way to run al-folio:

```bash
cd ~/Projects/alats99.github.io
docker compose pull
docker compose up
```

Then open [http://localhost:8080](http://localhost:8080).

## Put it online

1. Create a GitHub repo named **`alats99.github.io`** (use this folder as the source; do not fork al-folio).
2. In the repo: **Settings → Actions → General → Workflow permissions → Read and write**.
3. Push the `master` (or `main`) branch.
4. After the **Deploy site** action finishes, set **Settings → Pages** to deploy from the **`gh-pages`** branch.

```bash
git remote add origin git@github.com:alats99/alats99.github.io.git
git push -u origin master
```

## Where to edit

| What | File |
| --- | --- |
| Name, URL, site description | `_config.yml` |
| Bio and photo caption | `_pages/about.md` |
| Photo | `assets/img/prof_pic.jpg` |
| Email, GitHub, LinkedIn | `_data/socials.yml` |
| Papers | `_bibliography/papers.bib` |
| Projects | `_projects/` |
| News | `_news/` |
| CV | `assets/json/resume.json` |

Add a PDF CV later by putting it in `assets/pdf/` and setting `cv_pdf` in `_pages/cv.md`.

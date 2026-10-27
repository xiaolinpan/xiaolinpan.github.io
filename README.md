# xiaolinpan.github.io

Personal academic website of **Xiaolin Pan** — <https://xiaolinpan.github.io>

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, deployed automatically by GitHub Actions on every push to `master`.

## Where to edit

| Content | File |
|---|---|
| About / bio / photo | `_pages/about.md`, `assets/img/prof_pic_xp.jpg` |
| News | one Markdown file per item in `_news/` (`display_date` controls the date shown) |
| Publications | `_bibliography/papers.bib` (`selected={true}` → shown on the home page; `abbr` must match `_data/venues.yml`) |
| Software cards | `_projects/*.md`, covers in `assets/img/software/` |
| CV page | `_data/cv.yml`; PDF in `assets/pdf/XiaolinPan_CV.pdf` |
| Presentations | `_data/talks.yml` |
| Mentoring | `_data/teaching.yml` |
| Name, links, social icons | `_config.yml` |
| Theme colors | `_sass/_themes.scss`, `_sass/_variables.scss` |

## One-time setup

Repository **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve
```

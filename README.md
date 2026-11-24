# hungph11.github.io

Personal academic homepage, built on [acad-homepage](https://github.com/RayeRen/acad-homepage.github.io) (Jekyll, auto-built by GitHub Pages).

## How to edit
| What | Where |
|---|---|
| Name, bio, avatar, social links | `_config.yml` → `author:` |
| About / News / Publications / Experience / Awards / Education | `_pages/about.md` (Markdown) |
| Top navigation bar | `_data/navigation.yml` |
| Images (paper figures, photo) | `images/` → reference as `images/xxx.png` |
| CV, slides, posters (PDF) | `files/` → link as `files/cv.pdf` |

Edit directly on github.com (pencil icon) or locally, then commit & push — the site rebuilds in ~1 minute.

## Citation badges (optional)
Add repo secret `GOOGLE_SCHOLAR_ID` = `bFzFJMgAAAAJ` (Settings → Secrets → Actions); the daily workflow then writes citation data to the `google-scholar-stats` branch.

## Local preview (optional)
`bundle install && bundle exec jekyll serve` → http://localhost:4000

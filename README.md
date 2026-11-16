# milinpatel07.github.io

Personal academic homepage of Milin Patel, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template.

## Where to edit

| What | File |
|---|---|
| Bio, subtitle, photo | `_pages/about.md` (photo: `assets/img/prof_pic.jpg`) |
| Publications | `_bibliography/papers.bib` (`selected = {true}` shows a paper on the About page; `code`, `arxiv`, `doi` add buttons) |
| News | one file per item in `_news/` |
| CV page | `_data/cv.yml`; PDF in `assets/pdf/Milin-Patel-CV.pdf` |
| Profile links | `_data/socials.yml` |

Every push to `main` builds the site with GitHub Actions and publishes it to the `gh-pages` branch.

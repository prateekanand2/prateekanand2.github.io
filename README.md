# prateekanand2.github.io

This is the source for my personal website, [prateekanand2.github.io](https://prateekanand2.github.io/). I'm a Ph.D. student in Computer Science at UCLA working on machine learning for genomics, and the site has my publications, presentations, teaching, and CV.

The site is built with [Jekyll](https://jekyllrb.com/) using the [al-folio](https://github.com/alshedivat/al-folio) theme. Every push to `master` rebuilds it and deploys to GitHub Pages.

## Running it locally

With Docker installed:

```bash
docker compose up
```

Then open http://localhost:8080. The page reloads when you save a file.

## Where things live

- `_pages/`: the main pages (about, publications, presentations, repositories, CV, teaching)
- `_news/`: announcements shown on the home page
- `_bibliography/`: publications (`papers.bib`, `preprints.bib`) and presentations (`presentations.bib`)
- `assets/json/resume.json`: content for the CV page
- `assets/pdf/resume.pdf`: the downloadable resume

## License

The al-folio theme is released under the MIT license. See [LICENSE](LICENSE).

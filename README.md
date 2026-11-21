# roozbehnahavandi.github.io

Personal academic website, built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (MIT license; see `LICENSE`).
Pushing to `main` rebuilds the site through `.github/workflows/jekyll.yml`.

## Editing

- Sidebar (name, photo, links): `author:` block in `_config.yml`
- Home page: `_pages/about.md`
- Header links: `_data/navigation.yml`
- CV: replace `files/cv.pdf`
- Photo: replace `images/photo.jpg`

## Adding a publication

Copy one file in `_publications/`, rename it `YYYY-MM-DD-short-name.md`, and edit the front matter
(`title`, `category`, `permalink`, `excerpt`, `date`, `venue`, `link`, `paperurl`, `citation`).
`category` is one of the keys under `publication_category` in `_config.yml` (`conferences` or `preprints`).
Bold your name in `citation` with `<b>...</b>`. The list is sorted newest first by `date`.

## Local preview

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve -l -H localhost
```

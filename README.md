# pieter414.github.io

Personal site of Pieter Christy Yan Yudhistira, built on the [Academic Pages](https://academicpages.github.io/) Jekyll template.

## Updating

- Bio, interests, news: `_pages/about.md`
- Projects: add an entry to `_data/projects.yml` (`selected: true` also shows it on the home page)
- CV: `_pages/cv.md`; the PDF download is the Google Drive link at the top
- Sidebar (bio line, links): `author:` in `_config.yml`

## Running locally

```bash
bundle config set --local path 'vendor/bundle'
bundle install
bundle exec jekyll serve -l -H localhost   # http://localhost:4000
```

Or `docker compose up`.

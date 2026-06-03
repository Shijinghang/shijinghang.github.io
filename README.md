# Shijinghang's Personal Website

This repository hosts the source for [https://shijinghang.github.io](https://shijinghang.github.io).

The site is based on the Academic Pages Jekyll template and is published with GitHub Pages.

## Main Files To Edit

- `_config.yml`: site title, sidebar profile, avatar, academic links, social links
- `_pages/about.md`: homepage content
- `_pages/cv.md`: Markdown CV page
- `_data/cv.json`: optional JSON CV data
- `_data/navigation.yml`: top navigation menu
- `_publications/`: publication entries
- `images/profile.jpg`: sidebar profile photo

## Local Preview

Install dependencies once:

```bash
bundle install
```

Run the local site:

```bash
bundle exec jekyll serve -l -H localhost
```

Then open [http://localhost:4000](http://localhost:4000).

## Publish

Commit and push changes to `master`:

```bash
git add .
git commit -m "Update website"
git push origin master
```

GitHub Pages will rebuild the public site after the push.

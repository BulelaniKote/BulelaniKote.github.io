# bulelani-kote.github.io

Personal portfolio and blog. Data Engineer, Analytics Engineer, and poet. Built with Jekyll and GitHub Pages.

## Local development

```bash
gem install bundler jekyll
git clone https://github.com/BulelaniKote/bulelani-kote.github.io.git
cd bulelani-kote.github.io
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`

## Adding a new poem

Create a new file in `_poetry/` with the format `YYYY-MM-DD-title-slug.md`:

```markdown
---
title: "Your poem title"
date: 2026-04-02
dedication: "optional dedication line"
---
Your poem content here.

Blank lines create stanza breaks.
```

Push to main and GitHub Pages will rebuild automatically.

## Structure

```
_config.yml          # Jekyll configuration
_layouts/            # Page templates
_poetry/             # Poem collection (add new poems here)
assets/css/          # Stylesheet
index.html           # Homepage
projects.html        # Projects page
poetry.html          # Poetry index
contact.html         # Contact page
```

# GEMINI.md

## Directory Overview

This directory contains a Jekyll-based blog hosted on GitHub Pages. The blog is titled "Dostępnik" and described as "Prosty blog Jekyll na GitHub Pages". It uses the "minima" theme.

## Key Files

*   `_config.yml`: The main configuration file for the Jekyll site. It contains the site's title, description, and theme.
*   `index.md`: The main landing page for the blog.
*   `2025-05-24_14-39-39_Jak_powinny_być_umie.md`: A blog post.
*   `.github/workflows/jekyll-gh-pages.yml`: A GitHub Actions workflow for building and deploying the Jekyll site to GitHub Pages.
*   `gemfile` and `Gemfile.lock`: These files manage the Ruby gems required for the project, including Jekyll and its plugins.

## Usage

This directory is used to manage and generate a personal blog. The content is written in Markdown, and Jekyll transforms it into a static website. The site is automatically deployed to GitHub Pages whenever changes are pushed to the repository.

### Local Development

To run the site locally, you would typically use the following command:

```bash
bundle exec jekyll serve
```

This will build the site and start a local web server. You can then view the site in your browser at `http://localhost:4000`.

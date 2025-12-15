# Still Willows

Mental wellness coaching website for small teams. Built with Jekyll and deployed to GitHub Pages.

**Live site:** https://www.stillwillows.com

## Development

### Prerequisites

- Ruby 3.4.4
- Bundler

### Setup

```bash
bundle install
```

### Run locally

```bash
bundle exec jekyll serve --livereload
```

Site will be available at http://localhost:4000

### Build

```bash
bundle exec jekyll build
```

Output goes to `_site/`.

## Deployment

Push to `master` branch to trigger automatic GitHub Pages deployment.

## Project Structure

```
_config.yml          # Site configuration
_layouts/            # Page templates
_includes/           # Reusable components (header, footer)
assets/css/main.css  # Styles
index.md             # Homepage
about.md             # About page
services.md          # Services page
contact.md           # Contact page
faq.md               # FAQ page
```

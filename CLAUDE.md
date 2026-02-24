# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based personal academic blog and project portfolio hosted on GitHub Pages. It uses the Minimal Mistakes theme (`mmistakes/minimal-mistakes`) via `remote_theme`. The site includes:

- **Blog posts** in `_posts/` (Markdown with YAML frontmatter)
- **Static pages** in `_pages/` (About, Blog, Categories, etc.)
- **Standalone web tools** in `project/` (pure HTML/JS applications)
- **Custom layouts and includes** in `_layouts/` and `_includes/`
- **Site configuration** in `_config.yml`

## Development Environment

### Prerequisites
- Ruby (with Bundler)
- Node.js (for JavaScript asset processing)

### Local Development
```bash
# Install Ruby dependencies
bundle install

# Serve the site locally (default: http://localhost:4000)
bundle exec jekyll serve

# Optional: Enable live reload
bundle exec jekyll serve --livereload
```

### JavaScript Asset Processing
The theme includes JavaScript minification via npm scripts:
```bash
# Install Node dependencies
npm install

# Build minified JavaScript (run after modifying assets/js/_main.js or vendor files)
npm run build:js

# Watch for JavaScript changes
npm run watch:js
```

## Key Directories

- `_posts/` – Blog posts with filenames following `YYYY-MM-DD-title.md` format
- `_pages/` – Static pages (About, Blog, Categories, Donate, Gallery, Research)
- `_includes/` – Reusable HTML components (theme overrides possible)
- `_layouts/` – Page templates (`default.html`, `single.html`, `home.html`, etc.)
- `_data/` – YAML data files for navigation and UI text
- `_sass/` – SCSS stylesheets (theme-provided)
- `assets/` – Images, JavaScript, and CSS (theme assets plus customizations)
- `project/` – Standalone HTML/JS tools referenced from blog posts
- `_site/` – Generated static site (do not edit directly)

## Adding Content

### New Blog Post
1. Create a Markdown file in `_posts/` with filename `YYYY-MM-DD-slug.md`
2. Include YAML frontmatter (see existing posts for examples):
   ```yaml
   ---
   title: "Post Title"
   ---
   ```
3. Write content in Markdown; images should be placed in `assets/images/`

### New Page
1. Add a Markdown file to `_pages/`
2. Set layout and other frontmatter (see existing pages)
3. Update navigation in `_data/navigation.yml` if needed

### New Project Tool
1. Create a standalone HTML/JS file in `project/`
2. Ensure it works independently (no server-side dependencies)
3. Create a blog post in `_posts/` describing the tool and linking to `/project/filename.html`

## Configuration Highlights

- **Theme**: `remote_theme: "mmistakes/minimal-mistakes"` (no local theme files)
- **Site URL**: `https://asgeologeekfan.github.io`
- **Author**: Haotian Fan with extensive social links in `_config.yml:author.links`
- **Analytics**: Google Analytics via `google-gtag` with measurement ID `G-T17ZLKL8KQ`
- **Comments**: Custom comment provider configured (no Disqus)
- **Search**: Enabled with full-content search using Lunr (default)

## Deployment

The site is deployed automatically via GitHub Pages:
- Source: `master` branch root
- Build: GitHub Pages runs Jekyll with the `github-pages` gem
- No manual build needed; push changes to `master` and they will be live within minutes

## Important Notes

1. **JavaScript modifications**: Edit `assets/js/_main.js` and vendor files in `assets/js/vendor/`, then run `npm run build:js` to regenerate `assets/js/main.min.js`
2. **Theme customizations**: Override theme files by placing similarly named files in `_includes/`, `_layouts/`, or `_sass/` (the `remote_theme` is fetched remotely)
3. **Project tools**: Standalone HTML files in `project/` are served directly as static files (not processed by Jekyll) and referenced from blog posts
4. **Data privacy**: Project tools emphasize client-side processing with no data upload
5. **Image hosting**: Some author images are hosted externally on Aliyun OSS
6. **Windows development**: The Gemfile includes `wdm` gem for Windows filesystem monitoring
7. **Search indexing**: A `.travis.yml` exists for Algolia search indexing but appears unused; site uses Lunr for client-side search

## Common Commands Reference

```bash
# Local development
bundle exec jekyll serve
bundle exec jekyll build

# JavaScript assets
npm run build:js
npm run watch:js
npm run uglify

# Dependency management
bundle update
npm install
```
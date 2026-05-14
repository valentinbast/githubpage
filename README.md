# GitHub Pages Personal Site

A simple GitHub Pages site for personal projects and a blog.

## What’s included

- `index.md` — home landing page
- `projects.md` — project showcase page
- `blog/index.md` — blog index page
- `_posts/` — Jekyll blog posts
- `_config.yml` — site configuration

## Customize

1. Edit `_config.yml`:
   - `title`
   - `description`
   - `author.name`
   - `author.email`
   - `url` when your site is live
2. Update `index.md`, `projects.md`, and `blog/index.md`.
3. Add blog posts in `_posts/` using the filename format `YYYY-MM-DD-title.md`.

## Publish on GitHub Pages

1. Create a repository on GitHub.
2. Push this folder to `main` / `master`.
3. In GitHub, go to Settings > Pages and set the source to `main` branch.
4. Your site will be available at `https://your-github-username.github.io/repo-name/`.

## Local preview

If you want a local preview, install Jekyll and run:

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

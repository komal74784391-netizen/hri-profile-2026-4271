# Lab profile site scaffold

Starting point for member profile pages on the group website.

## Layout

- `_pages/` — the site's pages. This scaffold ships `about.md` and `cv.md`; the
  profile page is the *about* page and no extra pages should be added.
- `_publications/` — one Markdown file per publication (the file name is the slug).
  The files shipped here are demo entries and must be replaced.
- `_config.yml` — site configuration, including the site-level `author` block
  (`name`, `email`, `github`).
- `_data/navigation.yml` — top navigation.
- `_includes/author-profile.html` — sidebar author card, rendered from `_config.yml`.

## Publishing a profile

Create a repository from this scaffold, fill `_pages/about.md`, the `author`
block in `_config.yml` and the `_publications/` collection, then push everything
to the repository's default branch.

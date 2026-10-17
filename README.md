# Stoic Monkie

Our GitHub Pages site. A calm monkey, a few friends, and projects we build together.

## Structure

```
index.html      landing page + project cards
index.css       styles
assets/         shared files (logo, images, common styles)
projects/       one folder per project
docs/           notes
```

## Adding a project

1. Create a folder: `projects/my-project/` with its own `index.html` (and anything else it needs).
2. In the root `index.html`, copy the block between `PROJECT CARD` and `END PROJECT CARD`.
3. Change the title, one-line summary, link (`projects/my-project/`) and badge.
4. Push. Done.

Badges: `badge--progress` (in progress), `badge--live` (deployed), plain `badge` (idea).

Shared files go in `assets/` and are reached from a project with `../../assets/...`.
Every project page should link back home with `<a href="../../">Back to Stoic Monkie</a>`.

# Yongjie Han

A minimal personal homepage built with Jekyll and hosted on GitHub Pages.

The site contains contact details, education, and skills. Former About and CV
URLs redirect to the homepage.

## Editing

- `_config.yml`: name, email, GitHub account, site URL, and metadata.
- `_pages/about.md`: education and skills shown on the homepage.
- `_layouts/home.html`: profile header.
- `assets/css/main.css`: layout and responsive styles; no JavaScript is required.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --livereload --host localhost
```

Open `http://localhost:4000`. Restart Jekyll after changing `_config.yml`.

Alternatively, with Docker running:

```sh
docker compose up --build
```

Deployment continues to use the repository's GitHub Pages configuration.

## Credits

Originally based on [Academic Pages](https://github.com/academicpages/academicpages.github.io)
and [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes).
The original MIT license is retained in `LICENSE`.

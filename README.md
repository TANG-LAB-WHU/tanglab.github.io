# TANG LAB @ WHU Website

This is a Jekyll-based research group website designed for deployment through:

```text
https://github.com/TANG-LAB-WHU
```

Recommended public URL:

```text
https://TANG-LAB-WHU.github.io
```

To use this URL, create a repository under the organization named exactly:

```text
TANG-LAB-WHU.github.io
```

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Open:

```text
http://localhost:4000
```

## Deploy on GitHub Pages

1. Create a public repository under `TANG-LAB-WHU` named `TANG-LAB-WHU.github.io`.
2. Upload all files in this folder to the repository.
3. Go to repository `Settings` → `Pages`.
4. Under `Build and deployment`, choose `GitHub Actions`.
5. Push to the `main` branch.
6. The workflow in `.github/workflows/pages.yml` will build and deploy the website.

## Editing content

Most updates are in `_data/`:

- `_data/site.yml` — lab name, professor name, department, intro text
- `_data/people.yml` — PI, students, alumni
- `_data/projects.yml` — research cards
- `_data/publications.yml` — papers
- `_data/teaching.yml` — courses
- `_data/opportunities.yml` — recruiting text

News posts go in `_posts/`.

Images go in:

```text
assets/img/people/
assets/img/projects/
assets/img/logos/
```

## Custom domain option

If WHU can provide a real domain such as:

```text
tanglab.whu.edu.cn
```

then add it in GitHub repository `Settings` → `Pages` → `Custom domain`, and configure DNS with WHU's domain administrator.

Do not use `tanglab.whu.github.io` unless that is actually controlled by a GitHub account/domain owner. The normal organization GitHub Pages default is `ORGANIZATION.github.io`.

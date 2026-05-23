# TANG LAB @ WHU Website

## Overview

This repository contains the public Jekyll website for TANG LAB @ WHU. It is designed for the GitHub organization `TANG-LAB-WHU`, the repository `tanglab.github.io`, and the intended public URL:

```text
https://tanglab.github.io
```

The website presents research themes, public software projects, placeholder publication data, placeholder people profiles, teaching placeholders, news posts, joining information, and contact details for the lab.

## Local Preview

Use Ruby 3.2 or newer. The deployment workflow uses Ruby 3.2.

```bash
bundle install
bundle exec jekyll serve
```

Open:

```text
http://localhost:4000
```

## Editing Content

Most site content is editable without touching layouts:

- Edit `_data/site.yml` for lab identity, contact details, homepage summary, and keywords.
- Edit `_data/people.yml` for members, roles, bios, links, and profile images.
- Edit `_data/projects.yml` for repositories, project descriptions, categories, tags, languages, and images.
- Edit `_data/publications.yml` for papers, DOIs, code links, project links, and abstracts.
- Edit `_data/teaching.yml` for courses.
- Edit `_data/opportunities.yml` for recruitment and collaboration information.
- Add Markdown posts to `_posts/` for news.
- Add images under `assets/img/`, especially `assets/img/people/`, `assets/img/projects/`, and `assets/img/logos/`.

## Deployment

1. Push changes to the `main` branch.
2. Go to the GitHub repository `TANG-LAB-WHU/tanglab.github.io`.
3. Open `Settings` -> `Pages`.
4. Under `Build and deployment`, select `GitHub Actions`.
5. Wait for the `Deploy Jekyll site to GitHub Pages` workflow to complete.
6. Visit `https://tanglab.github.io`.

If GitHub Pages does not automatically serve the repository at this domain, configure `tanglab.github.io` as the repository's custom domain in the same Pages settings panel.

## Information to Replace

- Official professor full name.
- Official department or school at Wuhan University.
- Official lab logo.
- Official office address and contact information.
- Member photos and verified member biographies.
- Real publications and DOI links.
- Real courses and course links.
- Real openings and application instructions.
- Official custom domain if needed.

## Notes

Placeholder content is clearly marked in the website data and page copy. Replace placeholders before using the website as the lab's official public profile.

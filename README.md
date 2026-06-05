# TANG LAB @ WHU Website

## Overview

This repository contains the source code for the public Jekyll website of **TANG LAB @ Wuhan University**. It is designed for the GitHub organization `TANG-LAB-WHU`, the repository `tanglab.github.io`, and is served at:

```text
https://tang-lab-whu.github.io/tanglab.github.io
```

### Research Vision
TANG LAB leverages **Physics-Intrinsic Artificial Intelligence (PI-AI)** to advance circular resource and sustainable engineering science. Our research thrives on deep vertical and horizontal cross-disciplinary integration to address pressing environmental, technological, and governance-cost challenges. We seamlessly connect atomistic simulation, machine intelligence, and dynamic stochastic LCA/TEA to quantify and mitigate uncertainties in sustainable engineering, accelerating real-world solutions for:
- AI-Accelerated CO₂ Mineralization
- Phosphogypsum Upcycling
- MLIPs and Atomistic Simulation
- Dynamic Stochastic LCA/TEA
- Interpretable AI for Bioenergy
- Molecular Network Topology

## Local Preview

Use Ruby 3.2 or newer. 

```bash
bundle install
bundle exec jekyll serve
```

Open: `http://localhost:4000`

## Editing Content

The website is entirely data-driven. Content can be easily modified without touching the underlying HTML/CSS layouts:

- **`_data/site.yml`**: Lab identity, research vision, keywords, and homepage research cards.
- **`_data/opportunities.yml`**: Recruitment information (PhD, Master's, Postdocs, Undergrads, Visiting Scholars) and application instructions.
- **`_data/people.yml`**: Lab members, roles, bios, links, and profile images.
- **`_data/projects.yml`**: Featured research projects, GitHub repositories, and language tags.
- **`_data/publications.yml`**: Academic papers, DOIs, abstracts, and code links.
- **`_data/teaching.yml`**: Course information and materials.
- **`_posts/`**: Markdown files for lab news and updates.
- **`assets/img/`**: Images for people, projects, and logos.

## Deployment

This repository is configured with a GitHub Actions workflow (`.github/workflows/pages.yml`) for continuous deployment.

To deploy your updates:
1. Simply push your changes to the `main` branch.
2. GitHub Actions will automatically build and deploy the site.
3. Wait a few minutes and visit: `https://tang-lab-whu.github.io/tanglab.github.io`

*Note: If this is the very first time you are deploying, ensure that under your repository's `Settings` -> `Pages`, the `Build and deployment` source is set to `GitHub Actions`.*

## Launch Checklist

Before the official public launch, please ensure the following data files are populated with your lab's real information:
- Replace placeholder member profiles in `people.yml`.
- Add actual publication records to `publications.yml`.
- Update course information in `teaching.yml`.
- Replace placeholder news in `_posts/`.
- Upload official lab logo and member headshots to `assets/img/`.

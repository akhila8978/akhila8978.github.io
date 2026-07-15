# akhila8978.github.io

Personal portfolio site for Akhila Kurre — Data Engineer.

**Live site:** https://akhila8978.github.io

## About

Single-page portfolio covering experience, technical stack, featured projects, and certifications. Content is kept in sync with my resume so both tell the same, defensible story — no claims here that I can't back up in an interview.

## Stack

- Static HTML/CSS, no build step or framework
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (display), [Space Mono](https://fonts.google.com/specimen/Space+Mono) (mono/labels), served via Google Fonts
- Deployed via GitHub Pages directly from this repo

## Structure

```
.
├── index.html   # entire site — markup, styles, and content in one file
└── README.md
```

## Running locally

No build tools needed — just open the file:

```bash
git clone https://github.com/akhila8978/akhila8978.github.io.git
cd akhila8978.github.io
open index.html   # or double-click it / use a local server like `python3 -m http.server`
```

## Updating content

Everything lives in `index.html`:

| Section | What to edit |
|---|---|
| Hero | `.hero-desc`, `.hero-stats` — summary and headline numbers |
| Skills | `#skills` — grouped skill cards; "Currently Building" and "Databricks (Certified)" cards are intentionally marked as not-yet-production to stay honest about depth |
| Experience | `#experience` — bullets should match the resume's wording and numbers exactly |
| Projects | `#projects` — one `.proj-card` per project, linked to its actual GitHub repo |
| Certifications | `#certifications` |

**Rule of thumb before pushing changes:** if a claim appears here, it should also appear on the resume (or be clearly marked as in-progress/learning). Keeping the two in sync is what makes both credible to a recruiter who checks.

## Deployment

GitHub Pages serves this repo's `main` branch directly — pushing to `main` updates the live site within a minute or two, no CI step required.

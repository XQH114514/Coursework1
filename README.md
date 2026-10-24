# Qihao Xing - Personal Portfolio

A personal portfolio developed as Coursework Part I for the Applications of AI
in EEE course.

## Submission links for assessment

> **Published websites**
>
> - **Version 1 - AI-generated:** https://xqh114514.github.io/Coursework1/
> - **Version 2 - Human-designed:** https://xqh114514.github.io/Coursework1/me-designed.html
> - **Fuzzy decision project profile:** https://xqh114514.github.io/Coursework1/fuzzy-project.html
>
> **Supporting document:** https://github.com/XQH114514/Coursework1/blob/main/report.md

Both public website links were verified on 24 October 2026.

## Versions

### Version 1: AI-generated

`index.html` is the expressive AI-generated version. It presents a professional
profile, detailed project evidence, education, capabilities, awards, contact
details, and links to the supporting report.

### Version 2: Human-designed

`me-designed.html` is the white, photo-led version designed from the student's
own requirements. It uses a clean editorial structure, a personal portrait, and
a different information hierarchy from Version 1.

## Project files

- `index.html` - AI-generated portfolio page
- `me-designed.html` - human-designed portfolio page
- `fuzzy-project.html` - detailed research project profile
- `fuzzy-project-paper.pdf` - public project report with contact details removed
- `freight-forecasting.html` - freight forecasting and workforce scheduling profile
- `credit-risk.html` - credit risk modeling profile
- `project-case.css` - shared styling for applied project pages
- `profile-photo.jpg` - optimized portrait with metadata removed
- `report.md` - coursework report draft
- `README.md` - repository and maintenance documentation

Each portfolio version is a self-contained HTML file with embedded CSS, keeping
deployment simple and making both versions easy to review independently.

## Local preview

From the repository directory, start a static file server:

```text
python -m http.server 8000
```

Then open `http://localhost:8000/` for Version 1 or
`http://localhost:8000/me-designed.html` for Version 2.

## Deployment

GitHub Pages publishes the root of the `main` branch. A push or web-based commit
triggers a new deployment automatically.

## Maintenance workflow

1. Edit the relevant HTML or documentation file.
2. Preview both versions at desktop and mobile widths.
3. Check links, images, text overflow, and privacy-sensitive content.
4. Commit with a short, descriptive message.
5. Confirm the GitHub Pages deployment completed successfully.

Only the university email address is intentionally published. Private personal
details from the source resume are excluded from the website.

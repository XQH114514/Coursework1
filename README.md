# Qihao Xing - Personal Portfolio

A two-version personal portfolio developed as Coursework Part I for the
Applications of AI in EEE course.

## Live pages

- [AI-generated version](https://xqh114514.github.io/Coursework1/)
- [Human-designed version](https://xqh114514.github.io/Coursework1/guided.html)
- [Coursework report](https://github.com/XQH114514/Coursework1/blob/main/report.md)

## Versions

### Version 1: AI-generated

`index.html` is the expressive AI-generated version. It uses a dark editorial
layout with a large visual, project methods, education, capabilities, and contact
details.

### Version 2: Human-designed

`guided.html` is the human-designed version. The content order and design
requirements were defined before implementation. It prioritizes readability,
structured project evidence, and professional presentation on desktop, mobile,
and in print.

## Project files

- `index.html` - AI-generated portfolio page
- `guided.html` - human-designed portfolio page
- `report.md` - coursework report draft
- `README.md` - repository and maintenance documentation

Both web pages are self-contained HTML files with embedded CSS. This keeps the
deployment simple and allows either version to be reviewed independently.

## Local preview

From the repository directory, start a static file server:

```text
python -m http.server 8000
```

Then open `http://localhost:8000/` for Version 1 or
`http://localhost:8000/guided.html` for Version 2.

## Deployment

GitHub Pages publishes the root of the `main` branch. A push or web-based commit
triggers a new deployment automatically.

## Maintenance workflow

1. Edit the relevant HTML or documentation file.
2. Preview both pages at desktop and mobile widths.
3. Check links, images, text overflow, and privacy-sensitive content.
4. Commit with a short, descriptive message.
5. Confirm the GitHub Pages deployment completed successfully.

Only the university email address is intentionally published. Private personal
details from the source resume are excluded from the website.

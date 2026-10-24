# Coursework Part I: Personal Web Development

**Course:** Artificial Intelligence  
**Student:** Qihao Xing  
**Student ID:** [Your student ID]  
**Submission date:** [Date]

## Published websites

- AI-generated version: https://xqh114514.github.io/Coursework1/
- Human-designed version: https://xqh114514.github.io/Coursework1/guided.html
- Source repository: https://github.com/XQH114514/Coursework1
- Report source: https://github.com/XQH114514/Coursework1/blob/main/report.md

## Development process

### Version 1: AI-generated page

Version 1 was developed through Codex using a high-level brief. The brief identified
the intended audience and general purpose of the portfolio, while leaving the visual
language, content structure, typography, color system, responsive behavior, and
interaction details to the AI agent.

The resulting page uses a dark editorial presentation, an expressive serif display
face, a lime accent, a full-width image treatment, and a compact navigation system.
The layout includes a profile introduction, selected projects, capabilities, and a
contact section. CSS Grid and Flexbox provide desktop and mobile layouts, while
reduced-motion preferences and semantic HTML improve accessibility.

Key workflow:

1. Describe the purpose and the intended audience at a high level.
2. Let the agent choose the information architecture and visual direction.
3. Review the generated HTML and CSS at desktop and mobile widths.
4. Test image loading, navigation, text wrapping, and horizontal overflow.
5. Publish the page from the root of the `main` branch using GitHub Pages.

### Version 2: Human-designed page

Version 2 followed a design specification written before implementation. The
specification prioritized professional content over decorative effects: a direct
name-led introduction, scannable profile facts, evidence-oriented project records,
education, technical methods, qualifications, and contact details. A persistent
section index supports navigation on larger screens.

The visual direction combined an off-white gridded surface with dark ink, cobalt,
vermillion, and warm yellow accents. A sticky side panel supports navigation on
larger screens, while a compact mobile header replaces it on narrow screens.
Content is presented in explicit sections rather than the more fluid composition
used in Version 1. A print stylesheet also provides a clean, resume-like output.

Key workflow:

1. Decide what information a recruiter or academic reviewer needs first.
2. Define the page sections, navigation behavior, typography, color, and spacing.
3. Use Codex for implementation assistance rather than delegating the design
   decisions to it.
4. Test responsive behavior at desktop and mobile widths.
5. Check navigation, image loading, privacy-sensitive content, and deployment.

## Git and GitHub workflow

The project is maintained in a GitHub repository on the `main` branch. Changes
are committed with descriptive messages such as "Add two personal portfolio
versions", "Update portfolio with resume details", and "Replace personal email
with university email". GitHub Pages automatically publishes the repository root
after each update.

This workflow provides a remote backup, makes the change history inspectable, and
keeps the deployed site synchronized with the versioned source files. README.md
documents the live links, file structure, local preview command, deployment
method, and maintenance process.

## Comparison and evaluation

| Dimension | Version 1: AI-generated | Version 2: Human-designed |
| --- | --- | --- |
| Design direction | Expressive, editorial, high contrast | Structured, systematic, information-led |
| Navigation | Compact top navigation | Persistent side index on desktop |
| Information density | Lower, with more visual emphasis | Higher, with clearly separated records |
| Main strength | Strong first impression and distinctive personality | Clear scanning, comparison, and predictable structure |
| Main limitation | Less explicit structure for detailed professional information | More formal and visually conservative |
| Human involvement | High-level goal and review | Detailed layout, content, and behavior requirements |
| Development experience | Fast exploration with more decisions delegated to AI | More control, but more specification and iteration |

Both versions meet the basic publishing requirement through independent GitHub
Pages URLs. They are intentionally different in hierarchy and visual rhythm so
that the comparison focuses on their development approaches rather than small
cosmetic changes.

## Personal reflection

[Complete this section yourself without AI assistance.]

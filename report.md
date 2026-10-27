# Coursework Part I

## Personal Web Development

### A Two-Version Portfolio Built with GitHub Pages

**Student:** Qihao Xing  
**Course:** EEEE3134 Applications of AI in EEE  
**Student ID:** ____________________  
**Submission date:** 27 October 2026

## Published websites

| Version | Website |
| --- | --- |
| Version 1: AI-generated | https://xqh114514.github.io/Coursework1/ |
| Version 2: AI-guided | https://xqh114514.github.io/Coursework1/me-designed.html |

Source repository: https://github.com/XQH114514/Coursework1

## 1. Project scope and approach

This coursework involved developing and publishing two personal portfolio websites
through GitHub Pages. Both versions present the same professional information:
my academic background, technical skills, applied projects, awards, and contact
details. The purpose of this common foundation was to make the comparison focus
on how each page was created and designed, rather than on unrelated differences
in content.

The two versions used different levels of human direction. Version 1 gave Codex a
high-level objective and delegated most visual and structural decisions to the AI
agent. Version 2 began with a detailed student-written specification covering the
visual style, use of a personal photograph, layout, content order, and functional
requirements. Codex was used as an implementation tool, but the principal design
decisions were made before implementation.

Both websites are public and can be reviewed independently:

- Version 1: https://xqh114514.github.io/Coursework1/
- Version 2: https://xqh114514.github.io/Coursework1/me-designed.html

## 2. Version 1: AI-generated website

### 2.1 Brief and design direction

Version 1 was created using a broad brief that identified the audience, purpose,
and general need to present a professional personal profile. The AI agent was
responsible for deciding the information architecture, typography, colour system,
page rhythm, image treatment, navigation, and responsive behaviour.

The resulting design uses a dark editorial style with an off-white and lime-green
accent palette. A large serif headline, an abstract neural-network image, a moving
subject strip, and structured project rows create a visually expressive page. The
visual decision deliberately differs from a conventional résumé and demonstrates
the exploratory style that an AI agent may choose when given more freedom.

### 2.2 Content and implementation

The page was implemented as a self-contained `index.html` file with embedded CSS.
It includes:

- a name-led hero section and a short professional summary;
- a profile-at-a-glance section;
- three detailed project entries;
- an education, award, language, and certification section;
- technical and professional capabilities;
- university email, GitHub, and report links.

Each project is presented with its analytical problem, methods, and outputs rather
than only a title. All three projects link to separate detail pages: freight
forecasting and workforce scheduling, credit-card risk modelling, and fuzzy
multi-attribute decision making.

### 2.3 Development workflow

1. A high-level brief was supplied to Codex.
2. The agent selected the visual concept and page structure.
3. Content from the résumé and project materials replaced the initial placeholders.
4. Project detail pages and a public, contact-redacted research-paper PDF were added.
5. The page was tested at desktop and mobile widths.
6. The files were committed to the `main` branch and published through GitHub Pages.

### 2.4 Evaluation

The main strength of Version 1 is speed and visual distinctiveness. It is easy to
navigate, has a clear hierarchy, and presents a strong first impression. The
project links make the page more useful than a static summary. However, the dark
editorial styling is less conventional for a professional portfolio and gives
more attention to atmosphere than to a clean, document-like presentation.

## 3. Version 2: AI-guided website

### 3.1 Student-defined requirements

Version 2 was developed from a more explicit brief. The student required:

- the same basic professional information as Version 1;
- a white visual background;
- a clearly different layout from Version 1;
- use of the student's personal photograph;
- a clean and professional presentation.

These requirements were treated as design constraints. Codex assisted with coding,
responsive implementation, metadata, and testing, while the student determined
the intended appearance and level of personal representation.

### 3.2 Design and image workflow

The local portrait was resized to a web-appropriate resolution and stripped of
EXIF metadata before publication. It is displayed in a vertical portrait frame
within a white, editorial layout. The page uses a muted green accent, orange
details, a large name treatment, compact profile facts, and generous spacing.

The information architecture is more direct than Version 1:

1. Name and portrait
2. Profile at a glance
3. About and areas of focus
4. Selected projects
5. Education
6. Technical and professional capabilities
7. Contact information

The skills area introduces Python, C/C++, MATLAB, data modelling and AI, Git and
GitHub, and research communication with project-linked descriptions. The award
area also explains the National College Student Mathematics Competition, including
its host, history, two-stage format, and the fact that the provincial second prize
belongs to the preliminary stage rather than the national final.

### 3.3 Implementation and accessibility

Version 2 is implemented as a self-contained `me-designed.html` file with embedded
CSS. It includes semantic sections, keyboard focus states, descriptive link text,
responsive layouts, a reduced-motion preference, and a print stylesheet. A reusable
`project-case.css` file provides consistent styling for the separate project
profiles.

### 3.4 Development workflow

1. The student defined the white, photo-led design direction.
2. The portrait was prepared and cleaned of metadata.
3. Codex implemented the layout, content hierarchy, and responsive styles.
4. The project detail pages were linked from the portfolio.
5. Desktop and mobile layouts were checked for overflow, clipping, and broken links.
6. GitHub Pages published the result from the `main` branch.

### 3.5 Evaluation

Version 2 provides a clearer personal identity because the name and photograph are
visible in the first viewport. The light design is easier to adapt to conventional
professional contexts and presents factual information in a more predictable
order. Its limitations are a longer page and a more conservative visual character
than Version 1. It also required more detailed human input before implementation.

## 4. Git and GitHub workflow

The project is stored in a public GitHub repository and deployed from the root of
the `main` branch. Git was used to track changes, preserve a remote backup, and
provide an inspectable history. Commit messages describe the purpose of each
change, including adding the two portfolio versions, replacing personal contact
information, enriching the first version, adding project case studies, and adding
context for the mathematics competition award.

GitHub Pages automatically rebuilds the public site after repository updates.
`README.md` records the two principal website links, the project-detail links,
the file structure, the local preview command, and the maintenance workflow.

## 5. Comparison and evaluation

| Dimension | Version 1: AI-generated | Version 2: AI-guided |
| --- | --- | --- |
| Primary design input | High-level brief; AI selected most design details | Student specified the visual direction and content priorities |
| Visual style | Dark, expressive, editorial | White, photographic, structured |
| First impression | Strong atmosphere and visual contrast | Personal identity and professional clarity |
| Main image | Abstract neural-network visual | Personal photograph |
| Information hierarchy | About, projects, capabilities, background | Identity, projects, education, capabilities |
| Navigation | Compact top navigation with version switch | Minimal top navigation and direct section order |
| Content presentation | Large project rows with method and output labels | Structured project entries with method tags |
| Responsiveness | Desktop and mobile layouts verified | Desktop and mobile layouts verified |
| Development experience | Fast exploration with decisions delegated to AI | More specification and iteration, with greater control |
| Human involvement | Briefing, content provision, review, and correction | Detailed requirements, image selection, and systematic review |
| Main strength | Distinctive visual identity and concise project overview | Clear personal identity and consistent professional structure |
| Main limitation | Less conventional for conservative audiences | Longer page and a more restrained visual identity |

Version 1 demonstrates how quickly an AI coding agent can produce a coherent,
visually distinctive site from a general goal. Version 2 demonstrates the value
of detailed design intent: the output is more predictable, easier to scan, and
more clearly connected to the student's own choices. The comparison therefore
supports the view that AI agents are most effective when given clear requirements,
but that human judgement remains important for prioritising content and evaluating
the final result.

## 6. Functional verification

Both principal pages were tested at a desktop viewport of 1280 by 720 pixels and a
mobile viewport of 390 by 844 pixels. The checks covered horizontal overflow,
text clipping, internal anchors, image loading, project links, and page layout.
No blocking layout issues were found. The public pages and the project-detail
pages returned HTTP 200 responses after deployment. The project PDF loads in the
browser and remains 22 pages.

The portfolio also includes three independently accessible project profiles:

- https://xqh114514.github.io/Coursework1/freight-forecasting.html
- https://xqh114514.github.io/Coursework1/credit-risk.html
- https://xqh114514.github.io/Coursework1/fuzzy-project.html

## 7. Privacy and responsible presentation

Only information relevant to a professional portfolio is published. The personal
mobile number, date of birth, ethnicity, political affiliation, and household
registration were excluded. The public email address is the university account.
The portrait was stripped of metadata before publication. The fuzzy-decision
research PDF was derived from a temporary copy of the Word report and had all
team-member phone numbers and email addresses removed before publication.

These decisions distinguish useful professional information from unnecessary
personal exposure. They also demonstrate that AI-assisted development includes
non-code responsibilities such as reviewing what will become public.

## 8. Personal reflection

[To be completed by the student without AI assistance.]

The section should address:

- how the two development approaches affected your design decisions and workflow;
- which version better represents your professional identity and why;
- what you observed when giving AI broad versus detailed instructions;
- what you learned about evaluating, revising, and publishing your own work.

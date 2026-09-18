# atomosky.github.io

Personal website for **AnneMarie Tomosky, MPH** - senior research project manager in the Intelligent Health Research Lab at Temple University's College of Public Health.

**Live site:** https://atomosky.github.io

## About this site

A single-page site covering my research, teaching, publications, and the plain-language explainers I use in community-engaged health research. It includes a glossary of terms that come up often in AI and health work, and answers to questions I get asked regularly.

## What's in this repository

| File | Purpose |
|---|---|
| `index.html` | The entire site: HTML, CSS, and JavaScript in one file |
| `cv.pdf` | Curriculum vitae, linked from the Contact section |

## How it's built

No frameworks, no build step, no dependencies. One self-contained HTML file with:

- Inline CSS using custom properties for the color palette
- Two Google Fonts (Literata for headings, Public Sans for body text)
- Inline SVG icons and illustrations
- A small amount of vanilla JavaScript for the mobile menu, the scroll state on the nav, and the count-up statistics
- The headshot embedded as a base64 data URI, so there are no external image requests

The page is responsive, respects `prefers-reduced-motion`, and uses semantic HTML with `<details>` elements for the expandable glossary and FAQ so they work without JavaScript.

## Updating the site

1. Edit `index.html` directly, on GitHub or locally.
2. Commit the change. GitHub Pages redeploys in about a minute.
3. Update the "Last updated" line in the footer.

To replace the CV or resume, upload a new `cv.pdf` or `resume.pdf` with the same filename so the links keep working.

## Contact

- Email: atomosky@temple.edu
- LinkedIn: https://www.linkedin.com/in/a-tomosky
- ORCID: https://orcid.org/0009-0000-1712-9386
- Google Scholar: https://scholar.google.com/citations?user=groPWy0AAAAJ

---

Feel free to borrow the structure; of course, please don't copy the biography or written content directly.

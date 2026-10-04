# Portfolio Site Plan

## Site
- A light-only, responsive, single-column Jekyll portfolio for Jason Jia at `jasonjia97.github.io`, published from the repository root.
- Home, About, Work Experience, and Contact pages, with shared navigation and footer.
- Warm, human typography; semantic HTML, accessible contrast, and layouts that work at phone and desktop widths.
- Content sourced only from the supplied résumé: UC Berkeley education, L.E.K. Consulting, Prolink Elite Financial & Insurance Services, Wellmax Insurance Services, skills, leadership, and interests. No unsupported claims or invented details.
- Contact page links to the supplied LinkedIn profile. It will not publish an email address or phone number.

## Technical approach
- Markdown pages with YAML front matter; reusable Jekyll layout and includes; plain HTML and CSS with minimal or no JavaScript.
- Root-level `_config.yml`, `index.md`, `_layouts/`, `_includes/`, `assets/`, and `README.md`.
- GitHub Pages-compatible SEO tags, sitemap, and favicon; no server, database, framework, blog, form backend, or third-party trackers.
- README instructions for editing content, local preview, and Lighthouse checks.

## Assumptions
- The GitHub user-site address should be `https://jasonjia97.github.io`.
- “No” to a public mailto link means the résumé email stays private; the résumé phone number also stays private.
- The résumé itself is source material and will not be published as a downloadable file.
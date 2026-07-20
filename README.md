MATHEUS SIQUEIRA — DEVELOPER PORTFOLIO
========================================

Personal portfolio site for Matheus Siqueira, Backend / Full-Stack Developer
(Python, Django, REST APIs). Built as a static site, styled around an
"API documentation" visual concept — sections are framed as routes
(GET /experience, GET /projects, etc.), matching the backend-developer
focus of the content itself.

Live site: https://matheuspsiqueira.github.io/Portfolio/


FEATURES
--------
- Bilingual content (English / Português), toggled instantly via a button
  in the nav — no page reload, no duplicate files.
- Résumé download menu offering both language versions as PDF.
- Featured project cards with an expandable case-study modal (problem,
  features, architecture, tech stack) for the strongest projects.
- Image gallery inside each case study, with a click-to-enlarge lightbox.
- A secondary "Other Projects & Labs" grid for smaller builds, study
  projects, and security CTF write-ups.
- Fully responsive layout (mobile, tablet, desktop).
- No frameworks, no build step — plain HTML, CSS and vanilla JavaScript.


TECH STACK
----------
- HTML5
- CSS3 (custom properties / CSS variables, no framework)
- Vanilla JavaScript (language toggle, dropdown menu, modals, lightbox)
- Fonts: Space Grotesk, Inter, IBM Plex Mono (Google Fonts)


NOTES
-----
- The language toggle relies on CSS rules using !important. This is
  intentional — it guarantees the language switch always wins over
  other component styles, even ones that also set `display`. Keep
  this in mind if you add new components with their own display rules.
- Code snippets (e.g. the JSON block in the hero) are intentionally
  left in English in both language modes, as a stylistic choice.

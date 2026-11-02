# Changelog

## Part 2 — CSS styling and responsive design

- Added `Websites/styles.css` as a shared external stylesheet for all five pages.
- Added a CSS reset, design tokens, readable typography, accessible colour contrast, cards, buttons, form controls and focus/hover states.
- Reworked page structure with semantic header, navigation, main, sections, articles and footer elements.
- Added CSS Grid and Flexbox layouts for desktop content and cards.
- Added tablet and mobile media queries that collapse columns and reflow navigation, actions and footer content.
- Corrected broken navigation references caused by capital letters and spaces in the original links.
- Corrected the home page image markup and added `srcset`, `sizes`, `loading` and descriptive `alt` text.
- Added responsive screenshot evidence for desktop, tablet and mobile testing.
- Added `README.md` and `References.md` to document implementation decisions and sources.

## Feedback addressed from Part 1

The Part 1 prototype was structurally complete but visually unstyled and not yet robust on case-sensitive hosting. Part 2 addresses those limitations by centralising presentation in an external stylesheet, improving readability and hierarchy, adding visible interaction states, correcting navigation/file-name mismatches, and testing the pages at three viewport widths.

## Part 3 – Enhancing Functionality and SEO

- Added shared `Websites/script.js` with dynamic services rendering, keyword search, category filtering, image lightbox gallery, query-string enquiry presets, client-side validation, accessible error/status messaging and asynchronous form processing.
- Added service search and filter controls to `services.html`.
- Added enquiry and contact form fields, HTML5 constraints, JavaScript validation and submission handling. Contact messages are compiled into a `mailto:` link for `hello@pawscommunity.example`.
- Added an accessible lightbox gallery to `index.html`.
- Improved page titles, descriptions, keywords, canonical links, theme colour and image alt text across all pages.
- Added root-level `robots.txt` and `sitemap.xml` for search-engine crawling.
- Added responsive styles for the new controls, gallery, modal and form feedback states.

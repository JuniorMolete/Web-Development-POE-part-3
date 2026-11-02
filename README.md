# Paws Community Animal Shelter — WEDE5020W Part 2

This package extends the Part 1 HTML into a styled, responsive website for Paws Community Animal Shelter. The site keeps the five required pages and uses one shared external stylesheet so that typography, colour, spacing, layout and interaction states remain consistent.

## Website

Open `Websites/index.html` in a browser. The pages are:

- `index.html` — home and primary calls to action
- `about.html` — organisation, community and research-informed approach
- `services.html` — adoption, rehabilitation, foster, community and education services
- `enquiry.html` — accessible enquiry form
- `contactus.html` — contact details and opening hours

All navigation links use lowercase filenames so that the site works on case-sensitive hosting. The home image uses `srcset`, `sizes`, descriptive alternative text and a responsive aspect ratio.

## Part 2 implementation

The shared `Websites/styles.css` contains a reset, CSS custom properties, a consistent colour palette, relative spacing, typography, CSS Grid and Flexbox layouts, card styles, form controls, focus states and hover states. The layout is responsive at tablet (`52rem`) and mobile (`38rem`) breakpoints: the desktop multi-column layout collapses to a single column, navigation wraps into a mobile grid, and buttons and footer content reflow for narrow screens.



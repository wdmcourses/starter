# RULES:

* assets/ holds technical interface elements: fonts, icons, and other non-public assets.
* public/ holds all user-facing files: images, videos, and other media.
* scripts/ holds the project's own JS only. Libraries go into vendor/, not here.
* styles/ holds the project's own CSS, organized by purpose:
  - _fonts.css: font declarations (@font-face) only. New fonts go into assets/fonts/ in woff2 format.
  - _main.css: custom project styles only.
  - _media.css: media queries only, using the breakpoint templates defined there. Intermediate breakpoints may only be added by the user.
  - _vars.css: all project variables and basic html and body styling. Do not add new ones: if the design uses a new color or size, use the closest existing variable.
  - index.css: imports and gathers all project styles.
  - Other custom styles for specific scopes (components, sections, admin overrides, etc.) may also be placed here.
* vendor/ holds all external libraries and plugins. Download each required plugin from a public CDN (e.g., cdnjs) or its official source into a separate folder inside vendor/, keeping only production files (dist).
* Use existing tools in vendor/ (grid, helper classes, etc.) whenever possible instead of writing new ones.
* Where a container is used, use the --container variable for its width.
* Use relative paths whenever possible.
* Use 2 spaces for indentation.

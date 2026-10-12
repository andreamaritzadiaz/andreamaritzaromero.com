# andreamaritzaromero.com

My design portfolio, exported from Webflow and set up to be hosted for free on GitHub Pages.

## Editing
Every page is a plain `.html` file in this folder. Styles are in `css/`, images and GIFs in `images/`, fonts in `fonts/`, and my resume in `documents/`.
To preview locally, run `npx serve` in this folder and open the address it prints. The pages link to each other with clean addresses (`/about-me` rather than `about-me.html`), which `serve` and GitHub Pages both handle. Opening the files directly by double-clicking won't follow those links.

## Files GitHub Pages needs
- `CNAME` tells GitHub Pages to serve the site at andreamaritzaromero.com.
- `.nojekyll` makes GitHub publish the files exactly as they are.

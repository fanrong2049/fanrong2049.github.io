# Rong Fan, Ph.D. — Personal website

**Live website:** https://fanrong2049.github.io/

A responsive professional website focused on clinical pharmacology, DMPK, and oncology development. The content was adapted from Rong Fan's September 29, 2026 CV.

## Content

- Professional introduction and location
- Three selected areas of contribution in drug development
- Karyopharm and Frontage experience
- Education, certifications, selected training, and awards
- Publications, presentations, and a patent application
- Email, LinkedIn, and GitHub contact links
- Downloadable three-page CV

The public CV retains the original professional content and removes the phone number from the contact line. Email and LinkedIn remain available. The monogram and project panels are decorative graphics, not a photograph or study data.

## Edit the website

Open `index.html` in GitHub, click the pencil button, make your edits, and commit to `main`. GitHub Pages automatically publishes the changes. All page content and styles are in that file; there is no framework, installation, or build step.

- Colors: edit the variables at the beginning of the `<style>` block.
- Portrait: replace the initials panel with your photograph and descriptive alt text.
- CV: replace `resume.pdf` with an updated public copy using the same filename.
- Contributions: edit the `<article class="project">` blocks.
- Research: edit the `<article class="publication">` blocks.

## Hosting

GitHub Pages uses **Deploy from a branch → main → / (root)**. `.nojekyll` ensures the static files are served directly. HTTPS is enforced on the default domain.

## Files

- `index.html`: public website
- `resume.pdf`: downloadable public CV
- `favicon.svg`: initials icon
- `.nojekyll`: static hosting configuration
- `README.md`: maintenance instructions

The site uses system fonts, with no tracking scripts or external dependencies. Check mobile layout and contact, CV, and publication links after updates.

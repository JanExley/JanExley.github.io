# Jan Exley — Personal Portfolio

A responsive personal portfolio built with plain HTML, CSS and JavaScript for GitHub Pages. The site has a landing page and separate pages for robotics and quantum computing.

## Files

- `index.html` — landing page, education and selected work
- `robotics.html` — robotics, tomography and gas-leak localisation interests
- `quantum.html` — quantum algorithms, tomography and hardware interests
- `style.css` — shared layout, colours and responsive styles
- `script.js` — mobile navigation, reveal animations and current year
- `documents/Jan_Exley_CV.pdf` — CV linked from the landing page

## Preview locally

Open `index.html` in a browser, or use the Live Server extension in Visual Studio Code. The Robotics and Quantum links on the landing page open the other sections.

## Publish with GitHub Pages

1. Create a repository named **`jan-exley.github.io`** under the GitHub account `jan-exley`.
2. Upload the contents of this folder to the repository root (the `index.html` file should be at the root).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for deployment and visit `https://jan-exley.github.io/`.

## Before submitting — personalisation checklist

- [ ] Check that the LinkedIn profile URL and contact email are the ones you want to publish.
- [ ] Keep the CV at `documents/Jan_Exley_CV.pdf`, or update the landing-page link if you replace it.
- [ ] Add links to public repositories, reports or videos when you are ready to share them.
- [ ] Check the robotics and quantum pages regularly so project status and descriptions stay accurate.
- [ ] Test the live page on both mobile and desktop.
- [ ] Do not publish private coursework, confidential client information or code you do not have permission to share.

## Editing the design

The colour palette is at the top of `style.css` in the `:root` variables. The main accent is `--accent`. Landing-page copy is in `index.html`; the two research pages have their own HTML files.

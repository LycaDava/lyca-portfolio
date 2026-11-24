# Lyca C. Dava — Personal Portfolio

A responsive static portfolio using HTML, CSS, JavaScript, and local image assets. No build step, external libraries, database, or hosting credentials are needed.

## Preview locally
Open `index.html` in a browser. For a local web server, run `python -m http.server 8000` in this folder, then visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a GitHub repository (for example, `lyca-portfolio`).
2. Extract the ZIP and upload **the contents** of this folder to the repository root, including the complete `assets` folder. `index.html` must be at the root, not inside an additional folder.
3. Commit the files to the `main` branch.
4. Open the repository's Settings → Pages. Under Build and deployment, select Deploy from a branch, then `main` and `/ (root)`. Save.
5. Use the website URL displayed by GitHub Pages once deployment is complete.

All assets use relative paths, so the website can be hosted at a GitHub project path or a custom domain.

## Print or save as PDF
- On the homepage, click **Print / Save portfolio as PDF** to print the full portfolio, including project images.
- Click **View / Print résumé** to open the separate résumé, then click **Print / Save as PDF**.
- In your browser print dialog, select a physical printer or **Save as PDF**. The print layouts use A4 paper and hide navigation and interactive controls. Browser header/footer options can be turned off for a cleaner result.

## Before publishing
- Confirm that Lyca approves the public use of her portrait, project images, name, school and email address.
- The supplied application letter and original résumé are not included because they contain a personal phone number and detailed address. The site instead includes a public résumé page with a print/save PDF control.
- Graduation is shown as expected 2027. Update it after graduation.
- The DSP project is credited as group academic work. The carwash/charging project is described as an academic concept, and the copra study as a proposal; no unprovided media or demo links are fabricated. Add confirmed project media and individual contributions when available.
- Education honors and work immersion were retained from Lyca's own résumé.

## Files
- `index.html`: portfolio
- `style.css`: visual styling and responsive layouts
- `script.js`: mobile navigation, current section, gallery, email copying
- `resume.html`: public résumé, printable or savable as PDF
- `assets/`: portrait, actual DSP outputs, favicon

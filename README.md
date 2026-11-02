# IMPATalkShort2026

Dispersive PDE with combined nonlinearities — Alex D. Rodriguez, FIU.

## GitHub Pages

This is a static slide deck; no build step is needed. Publish the `main` branch
from `/(root)` in the repository's **Settings → Pages**. The `.nojekyll` file
lets GitHub Pages serve the files directly.

The project URL after deployment is
[alex-d-rod.github.io/IMPATalkShort2026](https://alex-d-rod.github.io/IMPATalkShort2026/).
All slide assets use relative paths so they work under the project URL.

See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Local viewing

Open `index.html` in a browser after unzipping the folder.

The deck vendors reveal.js and MathJax locally, so the mathematical slides should work without an internet connection.

Numerical and blow-up figures are intentionally not generated. They are referenced by the same filenames used in the Beamer/source talk. To show them, place the files at the referenced relative paths:

- `Oscillations/*.png`
- `Exp/*.png`
- root folder for `Corrected_PosE_Gaussain_Criteria_2.png`, `Corrected_PosE_Weighted_Criteria.png`, and `example_positiveE_weighted.png`

If the images are not present, the deck displays labeled placeholders.

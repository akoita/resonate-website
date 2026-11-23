# resonate-website

Source of https://resonate.pydes.xyz (GitHub Pages, custom domain + TLS; DNS at OVH: `resonate` CNAME -> `akoita.github.io`).

Static landing page rebuilt from the Google Labs Pomelli design
(https://labs.google.com/pomelli/website/anXVLcAU0AF5YPgRYwRkzF): the HTML is the
Pomelli export, with its images self-hosted under `assets/`. No build step; edit
`index.html` and push to `main` to deploy.

## Brand

Logo, favicon and social card follow the Resonate brand guide (`docs/brand/` in
`akoita/resonate`). The files in `assets/brand/` are copies of the generated
assets in that repo's `web/public/brand/`; when the logo changes there, copy
them over again.

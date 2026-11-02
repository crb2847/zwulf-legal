# zwulf.com — studio site & legal pages

Public studio homepage (`https://zwulf.com/`) and privacy policies for zwulf.com
apps (`https://zwulf.com/<slug>/privacy.html`), served by GitHub Pages with custom
domain `zwulf.com` (legacy `https://crb2847.github.io/zwulf-legal/...` URLs
redirect automatically).

Pages are generated from the `play-pipeline` repo:
`python scripts/legal.py --app-id com.zwulf.<slug> --name "<App Name>"` writes
`<slug>/privacy.html` here and updates `index.html`. Commit + push to publish.

Nothing here is secret. Do not put anything secret here.

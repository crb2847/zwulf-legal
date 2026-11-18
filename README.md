# zwulf.com — studio site & legal pages

Public studio homepage (`https://zwulf.com/`) and privacy policies for zwulf.com
apps (`https://zwulf.com/<slug>/privacy.html`), served by GitHub Pages with custom
domain `zwulf.com` (legacy `https://crb2847.github.io/zwulf-legal/...` URLs
redirect automatically).

`index.html` (the homepage) is written by hand: one self-contained file with no
external requests. It presents the company and its departments and does not list
individual apps.

The legal pages are generated from the `play-pipeline` repo:
`python scripts/legal.py --app-id com.zwulf.<slug> --name "<App Name>"` writes
`<slug>/privacy.html` here and rebuilds `privacy/index.html`, the list of policies
that the homepage footer links to. Commit + push to publish.

Nothing here is secret. Do not put anything secret here.

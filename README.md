# kcus-editorial

Files uploaded through the KCUS editorial dashboard (cms.kcus.ba), committed
by the editorial backend and published by GitHub Pages under
https://cdn.kcus.ba/kcus-editorial/<path> (until the domain is live:
https://kcus-ba.github.io/kcus-editorial/<path>).

- `editorial/YYYY/MM/` uploads: images as WebP in several widths, documents as uploaded
- `og/citostatici/` generated link-preview cards for the cytostatics report

The paths mirror the site path after /media/. Do not edit by hand: the
database records every file here.

Published from the main branch ("deploy from a branch"). GitHub soft-limits
that to about 10 builds an hour; a burst of uploads queues, nothing fails.

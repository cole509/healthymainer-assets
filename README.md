# healthymainer-assets

Public CDN host for the @healthymainer Instagram carousel slide PNGs.

These PNGs are pushed here from the daily publish workflow in the
private [healthymainer](https://github.com/cole509/healthymainer)
pipeline repo, then fetched by Meta's Container API from the jsDelivr
CDN mirror at `https://cdn.jsdelivr.net/gh/cole509/healthymainer-assets@main/...`.

Slides are 1080×1080 PNGs (2× retina = 2160×2160 actual). Each
publication's slides live under `slides/{run_id}/slide_NN.png`.

This repo is intentionally public — the slides are already public the
moment they post to Instagram. The pipeline + prompts stay private in
the source repo.

# benji-app-legal (legacy redirects)

This repo exists **only** to keep old in-app links working for users on older
builds of the Benji iOS app that were submitted with `nijitaden.github.io`
URLs. Once the new app build is approved and live, those builds still ship
with the old URLs hard-coded — and users who don't update will keep hitting
them for months (some forever).

The current sources of truth live elsewhere:

| Page    | Current canonical URL                                                |
| ------- | -------------------------------------------------------------------- |
| Privacy | https://benji-app.org/privacy                                        |
| Terms   | https://benji-app.org/terms                                          |
| Support | https://benji-finance-app.github.io/benji-app-legal/support.html     |

Each page in this repo is a tiny HTML stub that meta-refreshes to its new
home. **Do not edit the legal text here** — update it at the canonical
location instead.

## Setup

GitHub Pages must be enabled on this repo (Settings → Pages → Deploy from
branch `main`, root `/`) so that `https://nijitaden.github.io/benji-app-legal/...`
resolves.

## Do not delete

Leave this repo up indefinitely. The cost is zero and removing it will
break the App Store listing and any user still on an old build.

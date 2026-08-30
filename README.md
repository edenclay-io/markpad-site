# markpad-site

GitHub Pages host for Markpad's Sparkle update feed.

- `appcast.xml` — the live feed (baked into builds ≥ 0.1.140)
- `releases/` — signed + notarized DMGs and Sparkle deltas

Published by `./build.sh publish-appcast` in the markpad repo. The real
product site lands here once the name is decided (M5 slice 6).

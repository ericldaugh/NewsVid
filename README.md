# NewsVid update feeds

Public in-app update feed for the NewsVid Windows app. This repository is NewsVid-only and is not used for StreamRec.

The installed app fetches, with no login:

- `{base}/update-newsvid-live.json` (or `update-newsvid-staging.json` on the staging channel)
- `{base}/NewsVid-bN.zip` (live) or `{base}/NewsVid-staging-bN.zip` (staging)

Feed base:

https://github.com/ericldaugh/NewsVid/releases/download/feeds

The live feed currently advertises NewsVid 1.2.0 (build 10200). A newer live build is published only when that version is ready to ship.

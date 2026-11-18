# The 45% Club guide

## Updating the guide PDF

1. Replace the PDF in this repo. If the filename stays the same, nothing else needs to change.
2. If the filename changed, update the `/pdf` redirect destination in `vercel.json` to the new file.
3. Push to `main`. This site deploys from `main`.

Guide pages must link to `/pdf` (or `https://45-percent-club.trustevo.co.uk/pdf`). Never link to the PDF filename, and never add a `?v=` query.

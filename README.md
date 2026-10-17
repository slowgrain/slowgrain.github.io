# Slowgrain public website

Published at https://slowgrain.app/ using GitHub Pages from the main branch root.

- Root: product directory.
- `/gantt-for-sheets/`: served separately by the existing `slowgrain/gantt-for-sheets` project repository.
- `/drive-cleaner/`: English Drive Cleaner product, privacy, terms and support pages.
- `/drive-cleaner/ko/`: Korean equivalents.

Drive Cleaner content sources are maintained in the sibling `drive-cleaner` repository, `store/*.md`. Rebuild with:

```sh
node ../drive-cleaner/scripts/build-public-site.mjs --out ./drive-cleaner
```

Commit the generated static pages and push to main to publish. Do not remove CNAME, the Google verification file, or `.nojekyll`. Do not change the Gantt project repository as part of Drive Cleaner changes. Public installation and paid checkout remain unavailable; this website does not deploy the Apps Script app or certify OAuth/CASA compliance.

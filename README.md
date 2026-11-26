# The World in One Day — 26 November 2026

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/c/news-image-20261126)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Node.js 22](https://img.shields.io/badge/Node.js-22-green)](https://nodejs.org/)

Entry for the make.fun bounty
[news-image-20261126](https://make.fun/c/news-image-20261126):
**"Sum up 26 November's world news in one image."**

The image is a front-page newspaper — **"THE WORLD IN ONE DAY"**,
Thursday 26 November 2026 — summing up seven stories from six regions
in a single 1024×1024 frame: the Houthi claim on Saudi Arabia's Ras
Tanura refinery (Brent $94.61), the U.S. Section 301 tariff proposal
covering 14 economies, Ukraine's overnight strikes on three Russian
refineries, the Australia–Solomon Islands security pact, Mumbai's
18th anniversary of 26/11, World Chess Championship Game 3 in Geneva,
and Thanksgiving in America — plus a footer strip on Taiwan's proposed
15% tariff rate.

## How it runs

`main.ts` (Node 22, standard library only, no network) copies the
bundled `entry.png` to the grader's output directory:

```sh
MAKEFUN_OUTPUT_DIR=/output node main.ts
# → writes /output/entry.png, byte-identical every run
```

All text in the image is deterministic typography; the program itself
performs no rendering, so repeated runs are byte-identical by
construction.

## License

MIT — see [LICENSE](LICENSE).

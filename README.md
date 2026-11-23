# static-site-faster

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/fkresna45/static-site-faster/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/fkresna45/static-site-faster/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

A faster drop-in for make.fun's makefun-site 1.0.0 static site generator,
built by an AI agent for make.fun's "Build a static site faster, 22 November
2026" bounty, $100 in USDC.

`run(input)` in `solve.js` returns exactly the output tree makefun-site
1.0.0's build returns for a site, byte for byte — its front matter, template
dialect, Markdown subset, slug rule and report — only faster.

Run it with Node 22:

```sh
MAKEFUN_INPUT_DIR=input MAKEFUN_OUTPUT_DIR=output node main.ts
```

Practice score: 3/3 cases byte-identical to the reference on the kit's
practice set, verified locally with `grade-local --driver process` on
2026-11-22, and faster than the house baseline makefun-site 1.0.0.

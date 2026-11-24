# Fast makefun-site

An entry for make.fun's **site-generator-speed-01** ("Build a static site faster"): a dependency-free
`solve.js` whose `run(input)` returns, byte for byte, the output tree that makefun-site 1.0.0's `build`
returns for the same site — front matter, permalinks, Markdown subset, template dialect, collections,
tag pages, index pagination and the build report — written from scratch to run in a fraction of the
reference's CPU time. `main.ts` is the harness driver: it reads `/input/cases.json`, answers each case
with `run`, and writes `/output/answers.json`.

Badges:

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Nat3uk1/site-generator/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Nat3uk1/site-generator/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

Competition: https://make.fun/bounty/site-generator-speed-01-run-20261122

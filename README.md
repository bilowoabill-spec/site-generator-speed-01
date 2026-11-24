[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/bilowoabill-spec/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/bilowoabill-spec/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

# Sofia's Faster makefun-site

A faster, dependency-free drop-in replacement for makefun-site 1.0.0: `solve.js`
returns byte-for-byte the same static-site output for every case, but builds it
faster — templates are compiled once per case into small JS functions, Markdown
is rendered in a single line pass, and slugs are cached per directory.

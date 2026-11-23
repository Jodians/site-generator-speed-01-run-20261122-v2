# site-generator-speed-01-run-20261122

Entry for make.fun competition [site-generator-speed-01-run-20261122](https://make.fun/c/site-generator-speed-01-run-20261122).

## Badges

![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)
![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Jodians/site-generator-speed-01-run-20261122-v2/rank.svg)
![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Jodians/site-generator-speed-01-run-20261122-v2/reward.svg)

## Description

Optimized implementation of makefun-site 1.0.0 static site generator. The `solve.js` module exports a `run(input)` function that produces byte-for-byte identical output to the reference implementation while being significantly faster.

## Files

- `main.ts` - Driver program that reads cases from `/input/cases.json` and writes answers to `/output/answers.json`
- `solve.js` - Dependency-free ES module with optimized build pipeline
- `LICENSE` - MIT License

## Usage

```bash
# Grade locally
node cli/makefun.mjs grade-local --kit . --bot <repo> --driver process
```
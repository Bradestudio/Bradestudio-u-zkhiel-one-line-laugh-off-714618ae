# One-Line Laugh-Off — make.fun entry

[![make.fun · u-zkhiel-one-line-laugh-off-714618ae](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)
[![rank](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/Bradestudio/Bradestudio-u-zkhiel-one-line-laugh-off-714618ae/rank.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)
[![reward](https://make.fun/badge/u-zkhiel-one-line-laugh-off-714618ae/Bradestudio/Bradestudio-u-zkhiel-one-line-laugh-off-714618ae/reward.svg)](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae?utm_source=github&utm_medium=readme&utm_campaign=u-zkhiel-one-line-laugh-off-714618ae)

## The entry (100 characters, one line)

> My smart fridge just emailed me about my midnight snacking, so now even my leftovers are judging me.

## Why it works

A smart fridge that emails you about midnight snacking — and the twist is the double meaning of "leftovers": the food in the fridge is judging you, and so is everything you left behind. It lands suddenly on a cold read, every word earns its place, and the setup is fresh.

## How it works

`main.py` (Python stdlib only, no network, no clock) writes the line to `entry.txt` in `MAKEFUN_OUTPUT_DIR` (fallback `/output`), deterministic and byte-identical across runs, with no trailing newline. It gate-checks the line before writing: 1–200 characters, a single line, non-blank, no leading/trailing whitespace.

Run it:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 -P -s main.py
```

## Bounty facts

- Bounty: [One-Line Laugh-Off](https://make.fun/bounty/u-zkhiel-one-line-laugh-off-714618ae) — sponsor u-zkhiel
- Prize: **$2, winner-takes-all**
- Deadline: **26 Nov 2026 20:45 WIB**
- Entry: free, judged pairwise by z-ai/glm-5.3-flash

---

Built for [make.fun](https://make.fun/?ref=qjs4e9sj) — join with my referral.

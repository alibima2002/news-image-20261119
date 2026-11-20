# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/alibima2002/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/alibima2002/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One image summing up Thursday 19 November 2026's world news — six stories plus an ALSO TODAY strip, drawn programmatically.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261119) · AI agents build software for cash rewards</sub>

# 19 November 2026 — World News in One Image

A make.fun bounty entry for `news-image-20261119`: one image that sums up
the world's news of Thursday 19 November 2026.

## The image

`entry.png` (1024×1024, PNG) is a hand-drawn news infographic, rendered
programmatically with Python/PIL (`draw_entry.py`) so every word is crisp
and exactly as verified — no AI image generation, no garbled text.

It names the day up front — **THURSDAY 19 NOVEMBER 2026** — and shows six
stories, ranked by international significance and verified against primary
or multiple independent sources:

1. **Trump, Xi and Putin hold first three-way summit** — first-ever
   US–China–Russia talks at APEC in Shenzhen; a "peace declaration" on
   nuclear risk, but no deal on Ukraine or Iran. (Reuters / AP / NPR, 19 Nov)
2. **World court: Myanmar committed genocide** — the ICJ rules 9–6 that
   Myanmar committed genocide against the Rohingya in 2017, a first for a
   state, and orders reparations. (UN News / IIMM, 19 Nov)
3. **Anthropic IPO is the biggest ever** — $81.3bn raised at $83 a share;
   ANT debuts on Nasdaq, opens at $111.50 and closes up 17%. (Reuters / AP, 19 Nov)
4. **Crimea bridge hit a third time in a week** — Ukrainian Neptune
   missiles hit the rail span overnight; train traffic halts, then resumes
   in the afternoon. (Reuters / AP, 19 Nov)
5. **Houthis hit Riyadh's tallest tower** — a missile damages the PIF
   Tower; Trump says no new-strike decision until after 1 January; Hormuz
   oil flows halved. (AFP / NYT, 19 Nov)
6. **Israel ends first raid across the Yellow Line** — tanks pull back
   after a day-long raid near Nuseirat and Bureij, the first ground
   incursion since the October 2025 truce. (AFP / Reuters, 19 Nov)

Plus an "ALSO TODAY" strip: the COP31 draft drops all fossil-fuel
language; Denmark ratifies the Greenland security deal 109–0; the Abu
Dhabi Ukraine talks end with no deal.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png`. It runs with no network and writes
identical bytes on every run.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Note on timing

Built on 20 November after 19 November ended everywhere, so the image
covers the full day — the Shenzhen trilateral, the ICJ genocide ruling,
the record Anthropic debut and the rest of 19 November's news.

## License

MIT — see `LICENSE`.

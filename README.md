# Dad Joke Showdown — "1023 Megabytes"

[![make.fun](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![rank](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/Richat1801/u-mfnakmal-dad-joke-showdown-1d2ce3e5-entry/rank.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![reward](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/Richat1801/u-mfnakmal-dad-joke-showdown-1d2ce3e5-entry/reward.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)

Entry for the [Dad Joke Showdown](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5) bounty on make.fun.

`main.ts` (Node 22, standard library only) keeps a bank of eight original dad
jokes, scores each one deterministically against the judge's criteria — a
clean pun that lands on first read, a father's voice, freshness, tightness,
and a rhythm that reads aloud — and writes only the winner to
`/output/entry.txt`.

The winning joke (59 characters):

> I started a band called 1023 Megabytes. We never got a gig.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Deterministic: both grader runs write the same bytes, no trailing newline.

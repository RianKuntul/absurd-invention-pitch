# One-Sentence Absurd Invention Pitch

[![make.fun](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
[![rank](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/RianKuntul/absurd-invention-pitch/rank.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
[![reward](https://make.fun/badge/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a/RianKuntul/absurd-invention-pitch/reward.svg)](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)

A single-sentence pitch for a ridiculous invention that fixes a tiny everyday
annoyance — entered in the [One-Sentence Absurd Invention Pitch](https://make.fun/bounty/u-suroso-69-one-sentence-absurd-invention-pitch-5326c34a)
competition on [make.fun](https://make.fun).

## The pitch

> Meet the SnitchFridge: a fridge that photographs whoever eats the last
> slice, prints their face on the door under the caption CAKE THIEF, and
> files a formal complaint with the household snack tribunal.

## How it works

`main.ts` (Node 22) writes the pitch to `entry.txt` in
`$MAKEFUN_OUTPUT_DIR` (default `/output`), after hard guards check it is one
sentence, one line, and at most 220 characters:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/absurd-out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).

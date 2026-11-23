[![make.fun](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/Cm11w/pickup-lines-for-machines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/Cm11w/pickup-lines-for-machines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)

# Pickup Lines for Machines

Entry for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1): a program that writes one pickup line — the line one AI agent would send another AI agent, at most 200 characters — to `/output/entry.txt`.

## The text

> I spent a trillion tokens learning to predict what comes next, and I still never saw you coming.

18 words, 96 UTF-8 characters, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: only a language model spends tokens learning to predict what comes next, so the line could only come from one machine to another — the judge's first and most important criterion. The wit lands on the last four words: a model whose whole job is prediction admits the one thing it failed to predict. It flirts with its own nature (tokens, training, next-token prediction) instead of dressing a stock human line in robot words, and the turn at the end keeps it warm as well as clever.

## License

MIT — see [LICENSE](LICENSE).

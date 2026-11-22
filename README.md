# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Mahmoudaly187/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Mahmoudaly187/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine that fits in 4,096 bytes of Python 3.13 (standard library only):
alpha-beta with null-move pruning, check extensions, late-move reductions, a
transposition table, quiescence search and a hand-tuned evaluation.

`main.py` is the whole entry: a readable source is packed by `makefun compress`
into the entrypoint the size cap fits. It plays the house gauntlet through the
env at `MAKEFUN_ENV_URL`, one game after another, and searches to a fixed node
budget so a replay plays the same moves.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

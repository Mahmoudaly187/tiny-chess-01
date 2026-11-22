# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine that fits in 4,096 bytes of Python 3.13 (standard library only).

`main.py` is the whole entry: a readable source is packed by `makefun compress`
into the entrypoint the size cap fits. It plays the house gauntlet through the
env at `MAKEFUN_ENV_URL`, one game after another, and searches to a fixed node
budget so a replay plays the same moves.

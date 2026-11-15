# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/liemargo/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/liemargo/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in a single 4 KB Python file: negamax alpha-beta search with iterative deepening, quiescence search with check evasions, a transposition table, late-move reductions, null-move pruning, piece-square tables and full game-history repetition detection, compressed with lzma into the 4 KB limit. It plays through the make.fun environment API with a fixed 30,000-node budget per move — no clocks, no randomness.

## Run it

```sh
MAKEFUN_ENV_URL=<environment-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=rkd14ktt&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

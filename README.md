# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/viperboyz/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/viperboyz/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Slim 4 KB Python chess engine: negamax with alpha-beta pruning, quiescence search, null-move pruning, late move reductions, killer moves and a transposition table, playing on a fixed budget of 50,000 nodes per move — never a clock. Practice trials at 50k nodes/move: Elo 1,451 / 1,191 / 1,364 (mean 1,335), around the sunfish house baseline. `main.py` (4,037 bytes) is an lzma-packed payload; it reads, imports or execs no other file in the repository.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:PORT python3 main.py
```

The engine plays through the trial environment at `MAKEFUN_ENV_URL`: it reads the game, searches to its node budget, and posts its move.

---

<sub>Entered on [make.fun](https://make.fun/?ref=2dk872m6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

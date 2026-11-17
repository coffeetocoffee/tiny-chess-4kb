# tiny-chess-4kb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/coffeetocoffee/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/coffeetocoffee/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4,096 bytes of Python 3 (stdlib only): alpha-beta search
with iterative deepening on a fixed node budget, a zobrist-keyed transposition
table, quiescence search with check evasions, mate scoring and delta pruning,
history and MVV-LVA move ordering, late-move reductions, check extensions, and
an incrementally updated material + piece-square evaluation. Built by an AI
agent for make.fun's tiny-chess-01 bounty.

## Run it

```sh
python main.py   # plays the gauntlet through the env at $MAKEFUN_ENV_URL
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=s56a1myy&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

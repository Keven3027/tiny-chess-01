[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Keven3027/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Keven3027/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01

A 4,096-byte Python chess engine (main.py is 4,096 bytes or under): 0x88 board,
iterative-deepening negamax alpha-beta under a fixed 300k-node budget (no clock,
fully deterministic), a transposition table, null-move pruning, MVV-LVA ordering,
quiescence search and repetition-draw scoring against game history.

`python3 main.py` plays the house gauntlet through the env at `MAKEFUN_ENV_URL`.

Practice: 1451 Elo (3W/2D/1L on trial-0), replay byte-for-byte identical.

Join the bounty: https://make.fun/bounty/tiny-chess-01 — referral `g2c6ddth`

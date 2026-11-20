# tiny-chess-01

A 4,096-byte Python chess engine: 0x88 board, iterative-deepening negamax
alpha-beta under a fixed 200k-node budget (no clock), transposition table,
null-move pruning, MVV-LVA ordering and quiescence search.

`main.py` ships its source as a raw-LZMA payload; `python3 main.py` plays the
house gauntlet through the env at `MAKEFUN_ENV_URL`.

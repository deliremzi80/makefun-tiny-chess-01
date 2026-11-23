# Antigravity Tiny Sunfish v1

A compact, high-performance chess engine written in under 4,096 bytes of Python for the make.fun tiny-chess-01 challenge.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/deliremzi80/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/deliremzi80/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features

- **Negamax Alpha-Beta Search**: Depth search with alpha-beta cutoffs for rapid, deep evaluation.
- **Piece-Square Tables (PST)**: Tuned positional tables for all pieces (Pawns, Knights, Bishops, Rooks, Queens, Kings).
- **MVV-LVA Move Ordering**: Most Valuable Victim - Least Valuable Attacker move sorting for fast branch pruning.
- **Quiescence Search**: Leaf node tactical resolution avoiding horizon blunders.
- **Strict Size Constraint**: Fits entirely in `<= 4096 bytes` of standard-library Python.
- **Deterministic Replay**: Fully reproducible search with no wall-clock variance.

Visit [make.fun](https://make.fun) for competition details and live standings.

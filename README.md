# Antigravity Tiny Sunfish v1

A compact, high-performance chess engine written in under 4,096 bytes of Python for the make.fun tiny-chess-01 challenge.

[![make.fun](https://img.shields.io/badge/make.fun-tiny--chess--01-blue)](https://make.fun)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python: 3.13](https://img.shields.io/badge/Python-3.13-blue.svg)](https://www.python.org/)

## Features

- **Negamax Alpha-Beta Search**: Depth search with alpha-beta cutoffs for rapid, deep evaluation.
- **Piece-Square Tables (PST)**: Tuned positional tables for all pieces (Pawns, Knights, Bishops, Rooks, Queens, Kings).
- **MVV-LVA Move Ordering**: Most Valuable Victim - Least Valuable Attacker move sorting for fast branch pruning.
- **Quiescence Search**: Leaf node tactical resolution avoiding horizon blunders.
- **Strict Size Constraint**: Fits entirely in `<= 4096 bytes` of standard-library Python.

Visit [make.fun](https://make.fun) for competition details and live standings.

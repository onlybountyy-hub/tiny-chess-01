# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/onlybountyy-hub/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/onlybountyy-hub/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 3,944 bytes of Python (stdlib only): negamax search with PVS, transposition table with bound flags, null-move pruning, late-move reductions, check extensions and quiescence search, driven by a fixed 50,000-node budget so every move is deterministic. Local practice trials in the official kit environment estimate it at about 1,410 Elo.

## Run it

```sh
python3 main.py
```

`main.py` is the packed form of the readable source, produced by the make.fun kit's `compress` command; the readable source is uploaded with the entry's transcripts. The engine speaks the make.fun agent/v1 environment protocol on stdio and needs nothing beyond the Python 3.13 standard library.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q6ckzx1w&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

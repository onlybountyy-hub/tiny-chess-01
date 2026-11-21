# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/onlybountyy-hub/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/onlybountyy-hub/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in 4,012 bytes of Python (stdlib only): negamax search with PVS, transposition table with bound flags, null-move pruning, late-move reductions, check extensions, quiescence search and a butterfly history heuristic for quiet-move ordering, driven by a fixed 100,000-node budget so every move is deterministic. Developed from the fix3 entry (official practice Elo 1809); in 160 local gauntlet games against fix3 and the house baseline it measured a small, not statistically resolved improvement of roughly +35–40 Elo.

## Run it

```sh
python3 main.py
```

`main.py` is the packed form of the readable source, produced by the make.fun kit's `compress` command; the readable source is uploaded with the entry's transcripts. The engine speaks the make.fun agent/v1 environment protocol on stdio and needs nothing beyond the Python 3.13 standard library.

## License

MIT — see [LICENSE](LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q6ckzx1w&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

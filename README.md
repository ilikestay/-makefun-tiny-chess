# -makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ilikestay/-makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ilikestay/-makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Deterministic Python chess engine for the make.fun tiny-chess-01 bounty. `main.py` is the whole program: a fixed 200,000-node alpha-beta search with iterative deepening, principal variation search, quiescence, late-move reductions and a transposition table. It reads `MAKEFUN_ENV_URL` and plays each game over HTTP. The same position always gets the same move.

Local practice trial-0 through the kit env: 5 wins, 1 draw (draw with nodes-500k), about 1809 Elo on the kit's scale. That is this machine's run, not an official grade, and the entry is not submitted.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref={referral_code}&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

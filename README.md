# AI Chess Engine in C# with Unity

Two AI agents playing each other in 3D. Minimax with alpha-beta pruning, configurable search depth, playable from either side or fully autonomous. Includes a Shogi-variant training branch.

**🏆 2nd place — LA Hacks 2024.**

![platform](https://img.shields.io/badge/engine-Unity-000000?style=flat-square)
![language](https://img.shields.io/badge/language-C%23-239120?style=flat-square)
![search](https://img.shields.io/badge/search-minimax%20%2B%20%CE%B1%CE%B2-1F2937?style=flat-square)
![award](https://img.shields.io/badge/LA%20Hacks%202024-2nd%20place-gold?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-black?style=flat-square)

---

## What it does

- **AI vs AI** — spin up two engine instances and watch them play a full game.
- **AI vs Human** — play either color against the engine.
- **3D Unity board** — click-to-move interface with legal-move highlighting.
- **Shogi-variant mode** — piece-drop mechanics and variant-specific evaluation terms for training.

## How it searches

- **Minimax** with fixed-depth recursion.
- **Alpha-beta pruning** — cuts branches that cannot improve on the current best line.
- **Material + positional evaluation** — piece values, king safety, mobility, pawn structure.
- **Move ordering** — captures and checks searched first to maximize pruning.
- **Iterative deepening** on longer time controls.

## Run it

The repository ships built binaries for convenience:

| Platform | File |
|---|---|
| macOS | `Chess.app.zip` |
| Windows | `Chess (windows).zip` |

Unzip and launch. Source-build: open the project in Unity 2022+ and press play.

## Stack

C# · Unity · Minimax · Alpha-Beta Pruning · Shogi variant

---

## License

MIT

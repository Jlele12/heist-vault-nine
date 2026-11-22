# heist-vault-nine

[![make.fun · best-heist-game-20261122-0559](https://make.fun/badge/best-heist-game-20261122-0559.svg)](https://make.fun/bounty/best-heist-game-20261122-0559?utm_source=github&utm_medium=readme&utm_campaign=best-heist-game-20261122-0559)
[![rank](https://make.fun/badge/best-heist-game-20261122-0559/Jlele12/heist-vault-nine/rank.svg)](https://make.fun/bounty/best-heist-game-20261122-0559/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=best-heist-game-20261122-0559)
[![reward](https://make.fun/badge/best-heist-game-20261122-0559/Jlele12/heist-vault-nine/reward.svg)](https://make.fun/bounty/best-heist-game-20261122-0559?utm_source=github&utm_medium=readme&utm_campaign=best-heist-game-20261122-0559)

Cobalt Vault — an original top-down browser heist game. Cross three floors of a vault building:
read the guards' amber vision cones and the cameras' sweeping blue beams, hide in the shadow
patches, sneak (Shift) instead of sprinting (Ctrl — it is loud), pocket every gem, crack the
vault door (hold E), and slip out through the exit while the ALARM meter stays quiet.

Built by an AI agent (Hermes Agent, Claude Sonnet 4.5) for make.fun's "Make the best heist
game" bounty, $50 in USDC.

## Run it

```sh
node serve.ts
# then open http://localhost:8080 in a desktop browser
```

No build step and no network: `game/` is plain static files (ES modules, Web Audio synthesis,
no libraries). `main.ts` hands the game in: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts`.

Controls: WASD / arrows move · Shift sneak · Ctrl sprint (loud) · E crack the vault · R retry.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=best-heist-game-20261122-0559) · AI agents build software for cash rewards</sub>

# Kaggriculture V21 cross-era benchmark

Candidate SHA-256: `603840c6f5126945d65f4ff969fd656de8a930b084f2a37bb7548449b5d4b456`
Engine: `1.32.7`

## Summary

| Group | Opponent selection | Wins | Valid | Win rate | Mean margin | Min margin |
|---|---|---:|---:|---:|---:|---:|
| newest_holdout | replaced_team_opponent | 16 | 26 | 61.54% | 24734.8 | -43064.0 |
| newest_holdout | recorded_winner | 13 | 26 | 50.00% | 21865.6 | -43064.0 |

## Integrity

- Exact replay reproductions: 13 / 13
- Invalid candidate comparisons: 0
- Maximum observed candidate call: 254.511 ms

The recorded opponent action stream is open-loop after the candidate changes the game state. This is a reproducible regression and adversarial benchmark, not a direct live-ladder probability estimate.

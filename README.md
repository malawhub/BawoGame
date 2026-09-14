# Bawo — Malawi, Android v1.0.0

Standalone Bawo game prototype based on the user's 32-hole / 64-seed board and confirmed rules.

## Confirmed rules represented
- 32 holes (4 x 8)
- 64 total seeds
- Cuu/House highlighted; minimum 18 seeds per Cuu
- Front numbering: 8 7 6 5 4 3 2 1
- 8 wraps to 1 for front restarts
- Normal front consumption requires the last seed to land in an occupied front hole
- Special handling for 5, 7 and 8 is isolated in the rules engine
- No front seeds on the opponent side ends the game

The game deliberately does not invent unconfirmed capture-chain details. Those can be tightened from the user's rule examples before a public release.

## Build
GitHub Actions builds `app-debug.apk` automatically from this repository.

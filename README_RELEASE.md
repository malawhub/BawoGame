# Bawo Game v1.0.0 — Android Release Project

This is the standalone Android project for the Bawo game.

## Build
Open the `BawoGame` folder in Android Studio and build the debug APK, or run:

`./gradlew assembleDebug`

APK output:
`app/build/outputs/apk/debug/`

## Game foundation
- 32 holes (4 x 8)
- 64 seeds
- Cuu/House support
- Front numbering: 8 7 6 5 4 3 2 1
- Local two-player structure
- Bawo-specific sowing/capture logic hooks

Traditional-rule-specific code is kept isolated so further rule corrections can be applied without changing the board UI.

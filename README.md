# Chess Overlay

Android overlay prototype built with Kotlin, Android Gradle Plugin 8.0.2 and JDK 17.

## Build

Run `gradle --no-daemon assembleDebug`. The APK is written to `app/build/outputs/apk/debug/app-debug.apk`.
GitHub Actions builds the debug APK on pushes to `main` and uploads it as a workflow artifact.

## Current limitations

This is a prototype, not a working chess-analysis assistant yet. MediaProjection screen capture, chessboard/piece recognition, and Stockfish integration are not implemented. The app deliberately does not invent a FEN or suggest a misleading move.

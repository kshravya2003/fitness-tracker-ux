# Fitness Tracker UX Prototype

An Android interaction prototype built with Kotlin and Jetpack Compose, exploring glanceable activity information, voice controls, and haptic feedback.

## Implemented in source

- Steps, move, and heart-rate progress rings using sample values.
- Start/stop workout actions and voice-command parsing.
- Android speech-recognition intent integration.
- Nudge, achievement, and hydration vibration patterns; the UI exposes the achievement pattern.

## Open the project

1. Install Android Studio and JDK 17.
2. Open this repository directory in Android Studio.
3. Configure your local Android SDK (the original project targets API 34).
4. Sync Gradle, then run on a compatible emulator or Android device (minimum API 26).

Local SDK and Java installation paths are intentionally excluded. Configure the Gradle JDK in Android Studio for your machine.

## Current limitations

This is a UX prototype, not a live health-monitoring product. Progress values are fixed examples. The ViewModel state is a plain property, so workout changes do not reliably trigger Compose recomposition. The displayed voice prompt mentions high contrast, but that command is not implemented. Sensor integration, reminders, and accessibility extensions are future work.

The uploaded Gradle wrapper uses a Gradle 9 milestone with Android plugin 8.13.0; build compatibility has not been validated in this environment. No successful Android build is claimed.

## Documents

The project report is in `docs/HCI_Project.docx`. The original starter README is retained as `ORIGINAL_README.md`.

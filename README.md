# Atlas — Native Offline Life OS & Digital Assistant for Android

Atlas is a 100% native, offline-first Android Life OS and digital assistant. It combines personal productivity (notes, calendar, documents), time management, health and fitness tracking (Selene), offline maps, language tools, and smart hardware/media utilities into a unified, privacy-focused experience across phone and tablet form factors.

## Core Module Suite

* **Workspace:** Markdown notes, folders/tags, journal, ML Kit OCR/scanner, Digital Ink handwriting recognition, KaTeX math solver.
* **Time & Focus:** Single-ticker alarms, multi-timers, lap stopwatch, world clocks, and Pomodoro focus tracking.
* **Health & Fitness (Selene):** Health Connect integration, workout logging, exercise database, nutrition tracking, meditation timer, and CameraX + PPG optical heart rate monitoring.
* **Maps & Navigation:** Offline vector maps, tile management, POI search, offline routing, and spatial note/calendar pinning.
* **Polyglot & Translate:** Room phrasebooks, offline ML Kit neural translation, and live camera translation overlay.
* **Academy & Learn:** Sentence-based exercise generator, FSRS spaced-repetition engine, and streak tracking.
* **Smart Utilities & Media:** DAB+ digital radio, InfraRed and network remote controls, Chromecast/DLNA streaming, high-precision scientific calculator, and unit/currency converter.

## Technical Architecture & Toolchain Floor

* **Language & UI:** 100% Kotlin, Jetpack Compose, Material 3, Navigation 3.
* **Architecture:** MVVM + Clean Architecture, Hilt DI, Room, DataStore.
* **Toolchain:** JDK 25 LTS toolchain (`jvmTarget = JvmTarget.JVM_25`), Gradle 9.8.0 wrapper, Kotlin 2.4.21.
* **Target SDKs:** `compileSdk 37`, `targetSdk 37`, `minSdk 33`.
* **Native ABIs:** `arm64-v8a` and `x86_64` only.

## Build & Test Instructions

```bash
# Build debug APK
./gradlew app:assembleDebug

# Run JVM Unit Tests
./gradlew app:testDebugUnitTest
```

## Licence

Atlas is licensed under the **GNU Affero General Public License v3.0**. See [`LICENSE`](LICENSE).

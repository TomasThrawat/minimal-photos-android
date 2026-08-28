# Minimal Photos

Android photo gallery app, minimal by design.

- Kotlin + Jetpack Compose
- Reads device photos via `MediaStore` (no third-party image library)
- Runtime permission handling: `READ_MEDIA_IMAGES` (API 33+) / `READ_EXTERNAL_STORAGE` (below)
- 3-column grid of thumbnails, newest first

## Build

```
./gradlew assembleDebug
```

Output APK: `app/build/outputs/apk/debug/app-debug.apk`

## Requirements

- minSdk 24, targetSdk 34, compileSdk 34

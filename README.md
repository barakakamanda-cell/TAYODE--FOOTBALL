# TAYODE FOOTBALL™ — BUILD 01.47

Android-first / offline-first Alpha foundation.

## Target
- Android 9+ (API 28+)
- Recommended RAM: 3 GB+
- Alpha storage target: ~1.5–2.5 GB as content expands
- Performance target: 30 FPS on supported Alpha devices

## Included
- Native Android Studio project
- Offline launch screen
- Quick Match shell
- Teams & Players data layer
- Local JSON player database
- Settings/status panel
- Version metadata: 0.1.47-alpha / build 147

## Next engine integration
The project is intentionally structured as the Alpha foundation. Match simulation, formations, tactics, stamina, AI decision-making, commentary, saves and full 3D assets can be integrated without changing the package identity.

## Build
Open the root folder in Android Studio and build the `app` module. A network connection may be required by Gradle on the first dependency download; the app itself is designed to operate offline after installation.

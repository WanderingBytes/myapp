# MyApp - Project Status

## Current State
**Phase**: Project initialization
**Last updated**: 2026-02-05

## Stack
- Kotlin 2.0.0
- Jetpack Compose (BOM 2024.06.00)
- Material 3 with dynamic color support
- Min SDK 26 / Target SDK 34
- AGP 8.5.2 / Gradle 8.7

## Dev Cycle
- Edit code in Termux on device
- Push to GitHub → Actions builds debug APK
- Firebase App Distribution delivers APK to device
- Test on-device, iterate

## CI/CD
- [x] GitHub Actions workflow for debug APK builds
- [ ] Firebase project created
- [ ] Firebase App Distribution configured
- [ ] Service account key added as GitHub secret
- [ ] Firebase App ID added as GitHub secret

## Features
- [x] Basic Compose scaffold with greeting screen

## Known Issues
- None yet (fresh project)

## Next Steps
1. Push initial commit and verify Actions build succeeds
2. Set up Firebase project and App Distribution
3. Uncomment Firebase upload step in workflow
4. Start building actual app features

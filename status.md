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
- [x] Firebase project created (myapp-66fb1)
- [x] Firebase App Distribution configured
- [x] Service account key added as GitHub secret
- [x] Firebase App ID added as GitHub secret
- [x] APK uploads to Firebase on every push to main

## Features
- [x] Basic Compose scaffold with greeting screen

## Known Issues
- None

## Next Steps
1. Start building actual app features

# Fenix Style EN — Amazfit Cheetah 2 Ultra

Native Zepp OS watchface project (English edition).

## Target device

Verified against the current Zepp OS device list:
- Device: Amazfit Cheetah 2 Ultra
- Display: 480 × 480, round
- Zepp OS: 5.0
- API level: 4.3
- deviceSource: 9961728 (primary target; 9961729 is the alternate device variant)

## Design

- Dark embossed topographic background
- Graphite, bronze, copper and muted teal palette
- Analog hands plus large digital time
- Live steps, heart rate, calories, distance and battery
- Separate low-power AOD layout

## Build and installation

The official Zeus CLI builds the .zab package. Its `preview` command uploads/compiles a real-device preview and generates the QR code for Zepp App Developer Mode.

Zeus CLI requires Node.js >= 14. GitHub Actions can provide the build environment without installing software on the user's PC. Real-device QR preview requires a logged-in Zepp developer session; that authentication must be configured securely and cannot be assumed from GitHub access alone.

## Status

- Repository connected
- Device target verified
- Visual direction established
- App ID and Zepp preview authentication still need to be configured
- No installable .zab or QR code has been generated yet

Do not install this repository as a watchface.
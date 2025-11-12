# Flutter Breakdown (Breakdown Helper)

Breakdown Helper is a Flutter app for drivers that makes reporting vehicle breakdowns and finding nearby assistance quick and simple. Users can report issues, share their location, and view nearby helpers (mechanics/tow drivers) with estimated distance, ETA, and cost estimates. The project is structured for easy extension to production backends.

## Getting started

From the project root run (Windows PowerShell):

```powershell
cd C:\Users\tafar\Desktop\Breakdown\breakdwon
flutter pub get
flutter analyze
flutter run -d chrome    # or -d windows for desktop
```

If you're new to Flutter, these resources are helpful:

- Lab: Write your first Flutter app — https://docs.flutter.dev/get-started/codelab
- Cookbook: Useful Flutter samples — https://docs.flutter.dev/cookbook
- Official Flutter docs — https://docs.flutter.dev/

## Project structure (high level)

- `lib/` — main app code (models, services, state, UI screens)
- `assets/images/` — images (logo)
- `android/`, `ios/`, `web/`, `windows/`, `macos/`, `linux/` — platform folders
- `pubspec.yaml` — dependencies and assets

See `DEFENSE_NOTES.txt` and `CODE_EXPLAIN.txt` in the repo root for a detailed overview and developer guidance.

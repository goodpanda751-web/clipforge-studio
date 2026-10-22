# ClipForge Studio

CapCut-style video editor — cloud build project.

- App name: ClipForge Studio
- App ID: com.clipforge.studio
- Version: 1.0.0
- Web app: `www/index.html` (self-contained)
- Android: Capacitor (debug APK, test-signed) — built by GitHub Actions
- Windows: Electron Builder (NSIS installer .exe, unsigned) — built by GitHub Actions

## Getting the files

Go to the **Actions** tab, open the latest "Build ClipForge Studio (.apk + .exe)"
run, and download the artifacts at the bottom of the run page:

- `ClipForge-Studio-APK` → `app-debug.apk` (install on Android; you may need to
  allow "Install unknown apps" for your browser/file manager)
- `ClipForge-Studio-EXE` → the Windows installer `.exe` (unsigned, so Windows
  SmartScreen may show "More info → Run anyway" the first time)

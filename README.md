# Sendit Commander — releases

Downloads and in-app update manifests for **Sendit Commander**, a dual-pane, keyboard-driven file manager for macOS, Windows and Linux. The source code lives in a private repository; this repo holds only release builds.

- **Latest download:** https://github.com/AlucardBlack/sendit-commander-releases/releases/latest — pick the `.dmg` (macOS), the `-setup.exe` (Windows) or the `.AppImage` / `.deb` / `.rpm` (Linux). A platform's files appear once a build for it has been published.
- The app checks this page itself and installs new versions in one click (Settings → Updates).
- Every update package is signed with the Tauri updater key; the matching public key is built into the app, so a tampered file is refused.

## macOS: "Apple could not verify…"

Current builds are not yet notarized by Apple, so the first launch is blocked by Gatekeeper. To open the app once: try to launch it, then go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to "Sendit Commander". You only need to do this once per download; in-app updates are not affected.

# Pigeon Caller releases

Installers and the auto-update feed for the Pigeon Caller desktop app. The source lives in the private `MaherRaheem/pigeon-caller` repository (`desktop/`); this repository holds no code.

## Download

- **Windows:** [latest installer](https://github.com/MaherRaheem/pigeon-caller-releases/releases/latest). Run `Pigeon Caller Setup <version>.exe`. From 1.0.6 on, the app updates itself.
- **macOS (Apple silicon):** download `Pigeon Caller-<version>-arm64-mac.zip` from the [latest release](https://github.com/MaherRaheem/pigeon-caller-releases/releases/latest), move the app to Applications, then run:

  ```bash
  xattr -dr com.apple.quarantine "/Applications/Pigeon Caller.app"
  ```

  The macOS build is unsigned, so it can't update itself. Download new versions by hand.

You need a Pigeon Caller account to sign in.

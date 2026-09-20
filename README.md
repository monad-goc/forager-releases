# Forager Releases

Installer downloads for the Prodlogik desktop app.

## Download

Grab the latest installer from the [Releases page](https://github.com/monad-goc/forager-releases/releases):

- **Windows**: `.msi` or `.exe` installer
- **macOS**: `.dmg` installer

## First-run notes (unsigned builds)

These builds are not code-signed yet, so your OS will warn you before the first run:

- **macOS**: Gatekeeper will say the app "cannot be opened." Right-click the app and choose **Open**, or run:
  ```
  xattr -cr /Applications/Forager.app
  ```
- **Windows**: SmartScreen will show "Windows protected your PC." Click **More info** then **Run anyway**.

Builds are produced by CI directly from the source repository; no source code is published here.

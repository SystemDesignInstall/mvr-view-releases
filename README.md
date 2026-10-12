# MVR VIEW — Windows Releases

This repository is the **public distribution channel** for compiled Windows releases of MVR VIEW. Source code is stored in a separate private repository.

## Download and install

1. Open **Releases** and download the latest `MVR_VIEW_vX.Y.Z_windows_x64.zip` and matching `.sha256` file.
2. Verify the ZIP SHA-256 checksum, then extract into a **new folder** (do not overwrite a running version).
3. Launch `MVR_VIEW/START_EXE.bat`. Keep `_internal` and the other runtime files together with `MVR_VIEW.exe`.
4. Keep a backup of your old installation and any local projects before switching.

The application may check GitHub Releases and **download** an update to `workspace/updates/`, but will not automatically replace or execute it.

## Privacy and security

**Do not publish** MVR/VWX files, customer projects, logos, photographs, PDFs, backups, credentials, personal data, or source code here.

No official binaries are published yet. Windows builds must pass automated tests and be verified on Windows before an approved release.

> Portable builds are not code-signature verified unless a release explicitly says so.

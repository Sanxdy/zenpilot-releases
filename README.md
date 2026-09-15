# Zen Pilot — Releases

Distribution channel for **Zen Pilot** desktop builds.

Zen Pilot is a multi-account browser profile manager: isolate browser profiles with unique
fingerprints and run many accounts from one window.

## This repository contains no source code

It exists only to host signed release binaries. The source lives in a separate private
repository. Nothing here is buildable, and no source is published.

## Download

Get the latest build from the [Releases](../../releases/latest) page.

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `ZenPilot-<version>-arm64.dmg` |
| macOS (Intel) | `ZenPilot-<version>-x64.dmg` |
| Windows | `ZenPilot-<version>-Setup.exe` |
| Linux | `ZenPilot-<version>.AppImage` |

## Verify your download

Every release lists SHA-256 checksums in its notes. To verify on macOS or Linux:

```bash
shasum -a 256 -c SHA256SUMS.txt
```

On Windows (PowerShell):

```powershell
Get-FileHash .\ZenPilot-<version>-Setup.exe -Algorithm SHA256
```

Compare against the value in the release notes before running the installer.

## macOS: first launch

macOS builds are not notarized. If Gatekeeper blocks the app, open
**System Settings → Privacy & Security** and click **Open Anyway**.

## License

Zen Pilot is commercial software. Binaries are provided for end users to install and use.
No license to the source code is granted. See [LICENSE](LICENSE) for the full terms.

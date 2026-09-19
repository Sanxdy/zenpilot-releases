# ZenPilot Pro — Multi-Account & Anti-Detect Browser

**One window. Unlimited identities.**

ZenPilot Pro is a desktop browser that isolates every online account in its own profile — each with a unique fingerprint, dedicated proxy, and WebRTC leak protection. Built for marketers, agencies, and power users who run multiple accounts without getting flagged.

> 🚀 **[Get ZenPilot Pro](https://anzenpilot.gumroad.com/l/zenpilot)** · 💻 **[Main Website](https://vortex-freq.web.id)**

## Why ZenPilot Pro?

Stop juggling separate browsers, VPN windows, and spreadsheets of logins. ZenPilot gives you:

- **Unique fingerprints per profile** — canvas, WebGL, audio, and user-agent isolation
- **Per-profile proxies** — assign HTTP/SOCKS5 proxies per account
- **WebRTC leak protection** — keep your real IP hidden
- **Stealth mode** — automatic fingerprint randomization on launch
- **Built-in ad & tracker blocker** — blocks ads, trackers, pop-ups, cookie banners
- **Fast profile switching** — Chromium-based, instant open/close
- **Smart filtering & tags** — organize hundreds of accounts easily

## Pricing

- **Free** — 2 services, 3 profiles
- **Pro** — one-time purchase, unlimited profiles and services

No subscriptions. Lifetime updates. [Buy now on Gumroad](https://anzenpilot.gumroad.com/l/zenpilot).

## Download

Grab the latest build from the [Releases](../../releases/latest) page.

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `Zen.Pilot-<version>-arm64.dmg` |
| macOS (Intel) | `Zen.Pilot-<version>.dmg` |
| Windows | `Zen.Pilot.Setup.<version>.exe` |
| Linux (x64) | `Zen.Pilot-<version>.AppImage` |
| Linux (ARM64) | `Zen.Pilot-<version>-arm64.AppImage` |

## Verify your download

Every release lists SHA-256 checksums in its notes. On macOS or Linux:

```bash
shasum -a 256 -c SHA256SUMS.txt
```

On Windows (PowerShell):

```powershell
Get-FileHash .\Zen.Pilot.Setup.<version>.exe -Algorithm SHA256
```

Compare against the value in the release notes before running the installer.

## macOS first launch

macOS builds are not notarized. If Gatekeeper blocks the app, open **System Settings → Privacy & Security** and click **Open Anyway**.

## Support

- Website: https://vortex-freq.web.id
- Gumroad: https://anzenpilot.gumroad.com/l/zenpilot
- Releases: https://github.com/Sanxdy/zenpilot-releases/releases

## License

ZenPilot is commercial software. Binaries are provided for end users to install and use. No license to the source code is granted. See [LICENSE](LICENSE) for the full terms.

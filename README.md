# ZenPilot Pro — Multi-Account Browser Workspace

**One window. Separate sessions.**

ZenPilot Pro is a desktop workspace that keeps every web account in its own persistent Chromium profile — separate cookies, separate storage, separate cache, and an optional dedicated proxy. Built for agencies, social media managers, and freelancers who hold a lot of accounts open at once.

> 🚀 **[Get ZenPilot Pro](https://anzenpilot.gumroad.com/l/zenpilot)** · 💻 **[Main Website](https://vortex-freq.web.id)**

## Why ZenPilot Pro?

Stop juggling separate browsers, VPN windows, and spreadsheets of logins. ZenPilot gives you:

- **Isolated profile partitions** — each profile is its own persistent Chromium container with separate cookies, localStorage, IndexedDB, and cache
- **Per-profile proxies** — assign HTTP, HTTPS, SOCKS4, or SOCKS5 per account, plus an app-wide default
- **Custom browser settings per profile** — set the user agent, screen size, timezone, and rendering values a profile reports, so it stays consistent on every sign-in
- **Three memory modes** — Always On (sessions stay in RAM), Lazy Load (frees memory, keeps cookies), Manual Suspend (hibernate individual sessions)
- **Embedded browser workspace** — built-in address bar, back/forward/reload, home button, and tab pills, so you don't leave the app to work
- **Built-in ad & tracker blocker** — network-level request filtering plus DOM ad cleanup across active profiles
- **Encrypted at rest** — sensitive fields are encrypted with your OS keychain (macOS Keychain / Windows DPAPI); everything stays on your machine
- **Encrypted portable backups** — export and import all profiles, services, and settings
- **Six languages** — English, German, Spanish, French, Indonesian, Italian

## What ZenPilot is not

Stated plainly, because it matters when you are choosing where to put real accounts:

- **It is not an anti-detect browser.** It does not defeat or bypass any platform's abuse, fraud, or bot detection, and it makes no promise about how your accounts will be treated. ZenPilot does not modify the Chromium engine — it runs stock Electron/Chromium.
- **"Stealth mode" is a settings feature, not a disguise.** It makes a profile *report* consistent values for user agent, screen, timezone, canvas, WebGL, WebAudio, and WebRTC. Consistency is the goal, so a profile does not look like a brand-new device on every sign-in. That is not the same as being indistinguishable.
- **Isolation is the real, verifiable feature.** Separate partitions mean separate cookies, storage, and cache. It does not make accounts unrelated to each other in any platform's eyes — accounts already linked through payment details, a recovery address, or a phone number stay linked.
- **The WebRTC check is diagnostic, not a shield.** It reports the IPs your ICE candidates expose. Whether traffic actually goes through a proxy depends on your proxy configuration being correct and the proxy working.

If you need genuine anonymity, a hardened anti-detect stack, or to evade a specific platform's enforcement, this is not the tool for that.

## Pricing

- **Free** — 3 profiles, 2 built-in services. No time limit.
- **Pro** — $18.99 one-time. Unlimited profiles and services, custom services, up to 3 devices on one license.

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

> Use the Releases page rather than a hand-typed version number — a tag that has not been
> published yet returns 404.

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

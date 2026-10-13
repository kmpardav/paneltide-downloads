# PanelTide downloads

PanelTide helps comic creators review story intent, page flow, dialogue, lettering and continuity while keeping creative decisions explicit. This repository distributes **unsigned Windows x64 previews**. It contains distribution documentation and release assets; the development repository, design material and personal validation history remain private.

## Download 0.8.0

- [Windows installer](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/PanelTide-0.8.0-Windows-x64-setup.exe)
- [Windows portable executable](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/PanelTide-0.8.0-Windows-x64-portable.exe)
- [Photoshop 0.5.0 development ZIP](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/PanelTide-Photoshop-0.5.0-development.zip)
- [Getting started](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/GETTING-STARTED.md)
- [SHA256 checksums](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/SHA256SUMS.txt)
- [Third-party runtime notices](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.8.0/PanelTide-0.8.0-Third-Party-Notices.zip)
- [All release files and notes](https://github.com/kmpardav/paneltide-downloads/releases/tag/v0.8.0)

The versioned release links allow downloads without a GitHub account. No Mac or ARM executable is available. The Photoshop ZIP requires Adobe UXP Developer Tools; it is **not a signed `.ccx` installer**. Its API target is Photoshop 24.2+, with historical native evidence only on Photoshop 27.11.0 Windows. Clip Studio Paint has a companion file workflow; no native Clip Studio plugin is provided.

## AI access and creative control

The tested automatic route requires an existing compatible Codex CLI signed in with ChatGPT. PanelTide 0.8 does not automatically install or sign in to Codex. In the app, read the Connections notice and run **Check connection with a sample page** before using Analyze. The check shares one fixed PanelTide sample, not your comic. Analyze explicitly shares the selected review material with the configured AI provider. Provider permissions and limits apply; a subscription does not establish API credits or every model's entitlement.

Advice exposes scope, alternatives, uncertainty and citations. Registered sources are not automatically verified claim support. Tasks and Done are creator notes, not evidence that artwork changed. Independent novice/professional editorial evaluation and the final professional release remain in development.

The current preview keeps one local project and imports review derivatives up to 1600px; retain your original masters. Fuller New/Open/Save As, recovery, accessibility and large-project support remain roadmap work. Saved local data is OS-user-readable and unencrypted. No PanelTide billing, telemetry or automatic update service is active.

## Source and notices

GitHub's automatic source archives for **this downloads repository** contain public distribution documentation, not the PanelTide development source. Shipped Electron and plugin JavaScript remains inspectable; a private development repository is not an obfuscation guarantee.

The app includes Electron and Chromium third-party notices, including Node.js dependencies. The notices ZIP copies the actual packaged notices verbatim. These component licences do not grant an open-source licence to PanelTide itself. No paid plan, commercial licence terms or support SLA is invented by this preview repository.

## Report a preview issue

[Open an issue](https://github.com/kmpardav/paneltide-downloads/issues) with the app version, Windows version, installer/portable choice, steps and expected versus actual behaviour. Use the included original sample for public examples. Omit credentials, private client artwork and raw account logs.

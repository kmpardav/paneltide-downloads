# PanelTide downloads

PanelTide is a local editorial partner for comic creators. It helps you review story intent, page flow, dialogue, lettering and continuity, keeps your decisions explicit, and never changes your artwork without an explicit, reversible step. This repository distributes **unsigned Windows x64 previews**, their notes and the public website. The development repository, design material and personal validation history remain private.

Website and creator's guide: https://kmpardav.github.io/paneltide-downloads/

## Download 0.11.0

- [Windows installer](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/PanelTide-0.11.0-Windows-x64-setup.exe)
- [Windows portable executable](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/PanelTide-0.11.0-Windows-x64-portable.exe)
- [Photoshop 0.5.0 development ZIP](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/PanelTide-Photoshop-0.5.0-development.zip)
- [Getting started](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/GETTING-STARTED.md)
- [Release notes](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/RELEASE-NOTES.md)
- [SHA256 checksums](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/SHA256SUMS.txt)
- [Third-party runtime notices](https://github.com/kmpardav/paneltide-downloads/releases/download/v0.11.0/PanelTide-0.11.0-Third-Party-Notices.zip)
- [All release files](https://github.com/kmpardav/paneltide-downloads/releases/tag/v0.11.0)

The versioned links allow downloads without a GitHub account. Close PanelTide first. Installing 0.11.0 over 0.10 or 0.9 keeps your workspace in `%APPDATA%\PanelTide\workspace`; make a backup in **Backup and recovery** first. No Mac or ARM executable is available. The Photoshop ZIP requires Adobe UXP Developer Tools and is **not a signed `.ccx` installer**; the panel is optional because the app can work with Photoshop directly on Windows. Clip Studio Paint uses PNG exchange; no native Clip Studio plugin is provided.

## What 0.11 adds

Save comic in Page studio works again (it did nothing in 0.10.0). Every page now has the same header, with one name for each place. You can declare the page layout (printed facing pages, vertical scroll or one page at a time), so reviews know which pages face each other and where pages turn. You can mark panels on imported pages, so reviews can target single panels. The optional edit studio can place a candidate in Photoshop as one new layer, with Preview, Verify and Undo. Text contrast was fixed in every appearance, and saving retries briefly when Windows holds a file. 0.10 added large collections, scripts and story bibles, planned reviews with honest coverage, the managing editor, manual work, page exchange, direct Photoshop access and complete backups. See the release notes for details and limits.

## AI access and creative control

The tested automatic route requires an existing compatible Codex CLI signed in with ChatGPT; PanelTide does not install or sign in to it for you. Optional OpenAI, Anthropic, Gemini, Ollama and OpenAI-compatible routes can be configured but have not yet been verified against live provider accounts. Only the material you explicitly prepare is shared, and a chat subscription is not API credit.

Advice exposes scope, alternatives, uncertainty and citations. Registered sources are not automatically verified claim support. Tasks marked Done are your notes, not evidence that artwork changed. Independent editorial evaluation, accessibility review and code signing remain future release gates. Saved local data is readable by your Windows user and is not encrypted by PanelTide. No PanelTide billing, telemetry or automatic update service is active.

## Source and notices

GitHub's automatic source archives for **this downloads repository** contain public distribution documentation, not the PanelTide development source. The website is published from the `gh-pages` branch. Shipped Electron and plugin JavaScript remains inspectable; a private development repository is not an obfuscation guarantee.

The app includes Electron and Chromium third-party notices, including Node.js dependencies. The notices ZIP copies the packaged notices verbatim. These component licences do not grant an open-source licence to PanelTide itself. No paid plan, commercial licence terms or support SLA is offered by this preview.

## Report a preview issue

[Open an issue](https://github.com/kmpardav/paneltide-downloads/issues/new/choose) with the app version, Windows version, installer or portable choice, steps and expected versus actual behaviour. Use the included original sample for public examples. Omit credentials, private client artwork and raw account logs.

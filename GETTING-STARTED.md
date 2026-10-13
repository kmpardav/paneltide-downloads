# PanelTide 0.8.0: getting started

PanelTide is an unsigned Windows x64 preview for focused comic editorial review. A professional release is still in development.

## Open your workspace

1. Close an already open PanelTide before installing an update.
2. Download the Windows installer and open it. It installs for the current Windows user. The portable executable is the alternative when you want to run without installation.
3. Open PanelTide. The included original schematic comic lets you explore the workspace before importing your own material.
4. Choose one page or neighbouring pages, add your story intent and prepare a review.

## Verify AI access

This preview requires an existing compatible Codex CLI signed in with ChatGPT for its tested automatic route. PanelTide does not install or sign in to Codex automatically. See the [official CLI setup guide](https://learn.chatgpt.com/docs/codex/cli) and [official authentication guide](https://learn.chatgpt.com/docs/auth) when prerequisites are missing. A ChatGPT subscription is separate from API billing and does not establish every model's access.

In PanelTide, open Connections, read the sharing/allowance notice and choose **Check connection with a sample page**. The check sends one fixed PanelTide sample to your configured provider, not your comic. After a successful check, return to the prepared review and choose **Analyze**. Starting a review explicitly shares its included material with the selected provider. Account permissions and provider limits still apply; PanelTide does not display invented remaining allowance or costs.

## Keep creative control

Recommendations identify their scope, alternatives, uncertainty and references. A cited source is not automatically verified support. Tasks and Done are creator notes, not proof of an artwork edit. Broader chapter/script review and independent editorial-quality evaluation remain open. Imported images currently become review derivatives up to1600px; retain your original masters elsewhere. This preview keeps one local project, with a fuller New/Open/Save As lifecycle still being built.

## Photoshop and Clip Studio Paint

The Photoshop0.5.0 download is a **development ZIP**, loaded through Adobe UXP Developer Tools after extracting its folder. It is not a signed .ccx installer. Manifest API target is Photoshop24.2+, with historical native evidence only on27.11.0 Windows. The panel supports explicit text/image sends and selected-text Preview/Apply/Undo; it does not offer automatic generative-art API execution. Genuine Developer Mode, authentication and security prompts are the human's decisions. Photoshop is a separately licensed product.

Clip Studio Paint uses a companion file workflow; no native Clip Studio plugin is provided. No Mac or ARM executable is available.

## Data, notices and support

Saved work is local to the Windows profile and separate from app installation. It is OS-user-readable and unencrypted. AI sharing is a separate explicit action. No PanelTide account, billing, telemetry or auto-update service is active in this preview. Third-party runtime licences are included in the app and copied verbatim in the notices ZIP. This does not grant an open-source licence for PanelTide itself.

[Report a reproducible preview issue](https://github.com/kmpardav/paneltide-downloads/issues). Include version, Windows version, steps and whether you used installer or portable. Use original sample material for public examples; omit credentials, private client artwork and raw account logs.

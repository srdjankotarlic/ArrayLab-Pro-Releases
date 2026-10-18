# ArrayLab Pro — Experimental Preview

**Experimental software — not validated for professional sound-system design, certified rigging, or safety-critical decisions.**

Educational relative propagation, audience geometry and generic line array studies. No calibrated Meyer acoustic data, authentic Meyer rigging model, maximum SPL/headroom, room reverberation, or certified load calculation is supplied. Not affiliated with Meyer Sound.

[Downloads and release status](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases) · [Beta guide](BETA_GUIDE.md) · [Known issues](KNOWN_ISSUES.md) · [Report a bug](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/issues/new?template=bug.yml) · [Engineering discrepancy](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/issues/new?template=engineering.yml)

**Published experimental prerelease: [0.4.0-preview.1](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/tag/v0.4.0-preview.1).** Downloads are public and do not require a GitHub account.

| Platform | Download |
|---|---|
| Mac Apple Silicon | [Installer](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/download/v0.4.0-preview.1/ArrayLab.Pro_0.4.0-preview.1_aarch64.dmg) |
| Mac Intel | [Installer](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/download/v0.4.0-preview.1/ArrayLab.Pro_0.4.0-preview.1_x64.dmg) |
| Windows x64 | [Installer](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/download/v0.4.0-preview.1/ArrayLab.Pro_0.4.0-preview.1_x64-setup.exe) |

[SHA-256 checksums](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/download/v0.4.0-preview.1/SHA256SUMS.txt) · [Release notes](https://github.com/srdjankotarlic/ArrayLab-Pro-Releases/releases/download/v0.4.0-preview.1/RELEASE_NOTES.md)

The preview supports venue and listener-height editing, generic source placement/aiming, mechanically constrained generic rear-hinge arrays, geometric aiming-line optimization, relative complex-pressure propagation, virtual microphones, gain/delay/polarity/mute/filters, project files and state-derived exports. All acoustic results are approximate educational models. Generic collision checks are not hardware or rigging safety validation.

Installers are available for Mac Apple Silicon, Mac Intel and Windows x64, with offline WebView2 dependency installation. Mac minimum 12.0 is configured metadata; actual native GUI testing used macOS 27.0.1. Both Mac CI jobs passed, both DMGs were verified, and the Intel engine ran through Rosetta on the ARM test host. Windows installation, installed-engine, responding-window, Start Menu and uninstall checks passed on the windows-2025 runner. Human Windows workflows, physical Intel GUI and minimum-OS coverage remain pending. Mac is ad-hoc signed and not notarized; Windows is unsigned. Read the release notes before installing.

This distribution repository contains documentation, feedback forms and binary release assets. Development source remains private. The app performs no automatic project uploads or telemetry; feedback attachments are optional and user controlled.

![Installed Mac preview — educational relative prediction](screenshots/macos-simple-prediction.png)

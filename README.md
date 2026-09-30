<div align="center">

<img src="icon.png" width="64" height="64" alt="Vega">

# Vega

**Control your Windows PC with your voice — hands-free, offline.**
Say the wake word («Вега»), then your command — Vega opens apps and folders, controls windows, adjusts volume, and more.

[![Latest version](https://img.shields.io/github/v/release/vladkharitonov87/voice-helper-for-windows-releases?label=version&color=6C4AE2)](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases/latest)
[![Release date](https://img.shields.io/github/release-date/vladkharitonov87/voice-helper-for-windows-releases?label=released)](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/vladkharitonov87/voice-helper-for-windows-releases/total?label=downloads)](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows)

<br>

[![Download for Windows](https://img.shields.io/badge/Download_for_Windows-6C4AE2?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases/latest)

<sub>The <code>voice-helper-for-windows-&lt;version&gt;-setup.exe</code> file in the <b>Assets</b> section ·
<a href="https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases">Release history</a></sub>

</div>

---

> [!NOTE]
> Voice commands are currently **Russian only** — the wake word and command phrases are Russian,
> shown below in «quotes» with an English translation.

## What it does

- 🎙️ **Listens for the wake word.** Say «Вега» and Vega starts listening for your command — your hands stay free.
- 🗂️ **Opens apps and folders**, switches and closes windows, controls playback and volume, searches — by voice.
- ⌨️ **Push-to-talk fallback.** A hotkey (`Ctrl+Alt+W` by default, reassignable in the window) records a command without the wake word — for noisy rooms or a missed word.
- 🟢 **Shows its state** with the tray icon: listening, recognizing, paused, no microphone.
- 🚀 **Starts with Windows** (optional, toggled in the window) and runs in the background — closing the window just hides it.
- 🔒 **Recognizes everything locally**, offline: speech and command recognition never leave your computer.
- ✏️ **Learns from its mistakes.** The window's **«Исправить последнее»** ("Fix the last one") button lets you correct a misheard command — corrections are saved for retraining.
- 📋 **Keeps a journal** of recent commands with their recognized text, model output, and timings, plus manual text input when you'd rather type.

## Installation

1. Click **Download for Windows** above and download
   `voice-helper-for-windows-<version>-setup.exe` from the **Assets** section.
2. Run the installer. It installs into your user profile — no administrator rights needed.
3. If Windows shows "Windows protected your PC", click **More info → Run anyway**. The installer is
   not digitally signed yet, so SmartScreen does not recognize it.

After installation Vega appears in the tray and starts with Windows (turn this off in the window if
you prefer). Click the tray icon to open the window.

> [!TIP]
> You can check that the file was downloaded intact by its SHA-256 checksum, shown next to the file
> on the release page:
> `Get-FileHash .\voice-helper-for-windows-<version>-setup.exe`

## Requirements

| | |
|---|---|
| System | Windows 10 or 11, 64-bit |
| Microphone | Any: built-in, headset or USB |
| Command language | Russian |

Speech and command recognition are included in the installer — there is nothing else to set up.

## Updating

Vega does not check for updates automatically yet. Download and run the newer installer from the
[release history](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/releases) —
it installs over the existing copy and keeps your settings.

## Privacy

- Speech and commands are recognized locally (Whisper + a small fine-tuned language model) — audio
  and recognized text never leave your computer.
- The interaction log and any corrections you save stay on your computer only.

## Uninstalling

**Windows Settings → Apps → Installed apps → Vega → Uninstall.**

## Questions and bugs

Found a bug or have an idea? [Create an issue](https://github.com/vladkharitonov87/voice-helper-for-windows-releases/issues).

---

<sub>Vega is an independent personal project, not affiliated with any third party.</sub>

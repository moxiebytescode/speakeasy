<img src="logo.png" alt="SpeakEasy" width="128" />

# SpeakEasy

macOS menu bar dictation app. Press a hotkey from anywhere, speak, press it again to stop — your words are transcribed and pasted wherever your cursor is. No clicking, no switching windows.

Everything runs on-device. No cloud, no subscription, no account.

> **Requires macOS 26 (Tahoe) or later**

---

## Download

Grab the latest release from the [Releases page](../../releases/latest).

Mount the DMG, drag SpeakEasy to Applications, and launch it.

---

## How it works

1. Press **Control + Shift + Space** (customizable) from any app
2. Speak — a small floating indicator shows you're recording
3. Press the shortcut again to stop
4. Your transcribed text is pasted into wherever your cursor was

SpeakEasy uses Apple's on-device speech recognition (macOS 26+) or a locally downloaded Whisper model. An optional AI cleanup pass fixes punctuation and removes filler words before pasting. Both run entirely on your Mac.

---

## Permissions

SpeakEasy needs four permissions to function. An onboarding screen walks you through each one on first launch:

| Permission | Why |
|---|---|
| Microphone | Captures your voice |
| Speech Recognition | Converts speech to text on-device |
| Input Monitoring | Detects the hotkey while SpeakEasy is in the background |
| Accessibility | Pastes text into any app |

All four are required. The app won't proceed until they're all granted.

If you previously granted permissions but the app doesn't detect them (can happen after reinstalling), go to **System Settings → Privacy & Security** and remove/re-add SpeakEasy for the affected permission.

---

## Settings

Open **Settings** from the menu bar icon or press **⌘,**:

- **Hotkey** — change the shortcut, or switch to push-to-talk mode (hold to record, release to stop)
- **Speech Recognition** — Native (Apple Intelligence) or Whisper (local model download)
- **Text Cleanup** — toggle on/off; choose Native or a local model
- **Model Manager** — download and manage local Whisper / LLM models

---

## Why not the App Store?

Global hotkey detection requires a macOS capability that's incompatible with the App Store sandbox. Direct distribution with notarization is the only option — the app is still cryptographically signed and reviewed by Apple.

---

## Issues & Feedback

[Open an issue](../../issues/new/choose) to report a bug or request a feature.

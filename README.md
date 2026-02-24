<img src="images/logo.png" alt="SpeakEasy" width="128" />

# SpeakEasy

macOS menu bar dictation app. Press a hotkey from anywhere, speak, press it again to stop and your words are transcribed and pasted wherever your cursor is. No clicking, no switching windows.

Everything runs on-device. No telemetry. No cloud. No account. Your voice never leaves your Mac.

> **Requires macOS 26 (Tahoe) or later**

---

## ⬇️ Download

Grab the latest release from the [Releases page](../../releases/latest).

Mount the DMG, drag SpeakEasy to Applications, and launch it.

---

## 🎙️ How it works

1. Press **Control + Shift + Space** (customizable) from any app
2. Speak — a small floating indicator shows you're recording
3. Press the shortcut again to stop
4. Your transcribed text is pasted into wherever your cursor was

SpeakEasy uses Apple's on-device speech recognition (macOS 26+) or a locally downloaded Whisper model. An optional AI cleanup pass fixes punctuation, removes filler words, and converts spoken symbols ("slash settings" → `/settings`, "dot com" → `.com`) before pasting. With "Review before pasting" enabled, you can inspect cleaned text and give voice feedback to revise it before accepting. Everything runs entirely on your Mac.

---

## 🔐 Permissions

SpeakEasy needs four permissions to function. An onboarding screen walks you through each one on first launch:

| Permission | Why |
|---|---|
| Microphone | Captures your voice |
| Speech Recognition | Converts speech to text on-device |
| Input Monitoring | Detects the hotkey while SpeakEasy is in the background |
| Accessibility | Pastes text into any app |

All four are required. The app won't proceed until they're all granted.

If you previously granted permissions but the app doesn't detect them (can happen after reinstalling), go to **System Settings > Privacy & Security** and remove/re-add SpeakEasy for the affected permission.

---

## ⚙️ Settings

Open **Settings** from the menu bar icon or press **⌘,**. Settings are organized into tabs:

- **General** — hotkey, push-to-talk mode, clipboard mode, live transcription, sound feedback
- **Recognition** — Native (Apple) or Whisper (local model); language/locale picker; Whisper model downloads
- **Text Cleanup** — toggle on/off; choose Native or a local model; download local cleanup models; show cleaned text in HUD; review before pasting
- **Prompts** — choose a cleanup preset (General, Technical, Creative); expand any rule to see before/after examples; toggle individual rules on or off; add custom instructions
- **History** — browse past transcriptions with timestamps and raw vs. cleaned text; configure how many entries to keep (10, 25, 50, or 100)
- **Permissions** — check and manage required macOS permissions at a glance
- **About** — version info and links

---

## 🏪 Why not the App Store?

Global hotkey detection requires a macOS capability that's incompatible with the App Store sandbox. Direct distribution with notarization is the only option and the app is still cryptographically signed and verified by Apple.

---

## 🔒 Privacy

SpeakEasy collects no data. Not some data. Not anonymized data. No data.

- **Audio never leaves your Mac** — transcription runs entirely on-device via Apple Intelligence or a local Whisper model
- **Network access is used only to download models** — audio and text never leave your Mac
- **No account required** — nothing to sign up for, nothing to log in to

This is by design. SpeakEasy exists to be the voice tool you can trust completely.

---

## 🐛 Issues & Feedback

[Open an issue](../../issues/new/choose) to report a bug or request a feature.

---

## 📸 Screenshots

<p align="center">
  <img src="images/recording.gif" width="600" /><br/>
  <sub>Dictate anywhere — text appears at your cursor</sub>
</p>

<table>
  <tr>
    <td align="center"><img src="images/dropdown_menu.png" width="260" /><br/><sub>Menu bar</sub></td>
    <td align="center"><img src="images/recent_transcriptions.png" width="380" /><br/><sub>Recent transcriptions</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_general.png" width="300" /><br/><sub>Settings — General</sub></td>
    <td align="center"><img src="images/settings_recognition.png" width="300" /><br/><sub>Settings — Recognition</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_text_cleanup.png" width="300" /><br/><sub>Settings — Text Cleanup</sub></td>
    <td align="center"><img src="images/settings_prompts.png" width="300" /><br/><sub>Settings — Prompts</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_recognition_whisper.png" width="380" /><br/><sub>Whisper model downloads</sub></td>
    <td align="center"><img src="images/settings_text_cleanup_local_models.png" width="380" /><br/><sub>Local cleanup models</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_permissions.png" width="300" /><br/><sub>Settings — Permissions</sub></td>
    <td align="center"><img src="images/settings_about.png" width="300" /><br/><sub>Settings — About</sub></td>
  </tr>
</table>

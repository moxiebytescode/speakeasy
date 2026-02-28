<img src="images/logo.png" alt="SpeakEasy" width="128" />

# SpeakEasy

Speak your piece. We'll keep it between us.

A macOS menu bar dictation app. Press a hotkey from anywhere, say what you need to say, press it again — your words are transcribed and pasted right where your cursor sits. No clicking, no switching windows.

Everything runs on your machine. No wires out, no ears listening in. Your voice never leaves your Mac.

> **Requires macOS 26 (Tahoe) or later**

---

## ⬇️ Step Inside

Grab the latest release from the [Releases page](../../releases/latest).

Mount the DMG, drag SpeakEasy to Applications, and you're in.

---

## 🎙️ How It Works

1. Press **Control + Shift + Space** (customizable) from any app — one knock gets you in
2. Speak — a small floating indicator shows you're on the air
3. Press the shortcut again to stop
4. Your transcribed text is pasted into wherever your cursor was

The house cleans up after you — an on-device AI pass straightens out your grammar, sweeps away the "um"s and "uh"s, and translates the lingo ("slash settings" → `/settings`, "dot com" → `.com`) before pasting. With "Review before pasting" enabled, you can look it over and give voice notes to revise before it goes out. Everything runs entirely on your Mac, powered by Apple Intelligence.

---

## 🔐 The Door Policy

SpeakEasy needs four permissions to let you in. An onboarding screen walks you through each one on first launch:

| Permission | Why |
|---|---|
| Microphone | Hears your voice |
| Speech Recognition | Turns speech to text, on-device |
| Input Monitoring | Catches the hotkey while SpeakEasy's in the background |
| Accessibility | Pastes text into any app |

All four are required. No exceptions — the joint doesn't open until they're all granted.

If you previously granted permissions but the app doesn't detect them (can happen after reinstalling), go to **System Settings > Privacy & Security** and remove/re-add SpeakEasy for the affected permission.

---

## ⚙️ House Rules

Open **Settings** from the menu bar icon or press **⌘,**. The back office is organized into tabs:

- **General** — hotkey, push-to-talk mode, language picker, clipboard mode, text cleanup toggle, review before pasting, live transcription, show cleaned text in HUD, sound feedback, transcription history toggle, update checking
- **AI** — six cleanup presets (Standard, Formal, Casual, Technical, Minimal, Custom) with toggleable rules; write your own custom instructions for cleanup and revision; read-only system prompts
- **History** — a ledger of past transcriptions with timestamps and raw vs. cleaned text; configure how many entries to keep (10, 25, 50, or 100)
- **Permissions** — check and manage your door policy at a glance
- **About** — version info and links

---

## 🏪 Why Not the App Store?

The global hotkey requires a macOS capability that doesn't play nice with the App Store sandbox. Direct distribution is the only way in — but the app is still cryptographically signed, notarized, and verified by Apple. It's legit, even if it's not on the main drag.

---

## 🔒 What's Said Here Stays Here

SpeakEasy collects no data. Not some data. Not anonymized data. No data.

- **Your words don't leave the building** — transcription and text cleanup run entirely on-device via Apple Intelligence
- **No wires out** — transcription and text cleanup run locally, nothing is transmitted. An optional update check (disabled by default) connects to GitHub to see if a new version is available — that's the only network request the app ever makes
- **No account required** — nothing to sign up for, nothing to log in to

This is by design. We built the kind of place you can trust completely.

---

## 🐛 Got a Bone to Pick?

[Open an issue](../../issues/new/choose) to report a bug or request a feature.

---

## 📸 A Look Around the Place

<p align="center">
  <img src="images/recording.gif" width="600" /><br/>
  <sub>Dictate anywhere — your words appear at the cursor</sub>
</p>

<table>
  <tr>
    <td align="center"><img src="images/dropdown_menu.png" width="260" /><br/><sub>The menu bar</sub></td>
    <td align="center"><img src="images/recent_transcriptions.png" width="380" /><br/><sub>The ledger</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_general.png" width="300" /><br/><sub>House Rules — General</sub></td>
    <td align="center"><img src="images/settings_ai_text_cleanup.png" width="300" /><br/><sub>House Rules — AI (Text Cleanup)</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_ai_revision.png" width="300" /><br/><sub>House Rules — AI (Revision)</sub></td>
    <td align="center"><img src="images/settings_permissions.png" width="300" /><br/><sub>The Door Policy</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_about.png" width="300" /><br/><sub>About the Joint</sub></td>
    <td></td>
  </tr>
</table>

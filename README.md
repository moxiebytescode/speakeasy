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

The house cleans up after you — an on-device AI pass straightens out your grammar, sweeps away the "um"s and "uh"s, and translates the lingo ("slash settings" → `/settings`, "dot com" → `.com`) before pasting. With "Review before pasting" enabled, you can edit the text by typing, then press Return, the shortcut, or choose Accept Review from the menu. Escape or the close button discards it. Holding the acceptance shortcut never starts another recording. Everything runs entirely on your Mac, powered by Apple Intelligence.

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

- **General** — shortcut, push-to-talk mode, language, clipboard mode, cleanup on/off and one optional instruction field, review before pasting, live raw transcription, sounds, history enablement and update checking
- **History** — recent delivered text with timestamps, copy and Clear All; keeps the newest 25 after each new entry
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

## Updating from earlier versions

Live transcription now stays raw while you speak; cleanup applies to the final text. The previous effective cleanup preferences and enabled instructions migrate once into the single instruction field, which you can edit or leave empty. Voice revisions and the AI tab have been removed. Review accepts immediately on a shortcut press after a brief debounce, in either activation mode.

Existing history keeps its delivered text and timestamps. The next new entry trims history to 25. Turning history off stops collection without erasing saved entries; Clear All removes them. Migration preserves your expressed instructions, but model output can differ.

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
    <td align="center"><img src="images/settings_permissions.png" width="300" /><br/><sub>The Door Policy</sub></td>
    <td></td>
  </tr>
  <tr>
    <td align="center"><img src="images/settings_about.png" width="300" /><br/><sub>About the Joint</sub></td>
    <td></td>
  </tr>
</table>

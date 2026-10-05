---
title: yapping privacy policy
---

# Privacy policy

Effective October 5, 2026. Applies to yapping for iOS and iPadOS.

yapping has no server and no accounts. The developer receives none of your
audio, text, or usage. Everything below either stays on your device or goes
to OpenRouter under the API key you provide.

## What leaves your device

- **Dictation audio.** While you hold the keyboard's bar, the app records and
  sends that take's audio to [OpenRouter](https://openrouter.ai/privacy) and
  the transcription provider it routes to.
- **Transcripts for cleanup.** With Cleanup on, the transcript and your cleanup
  instructions, style rules, and vocabulary context go to OpenRouter and the
  cleanup provider.
- **Things you choose to send.** Calibration sends the writing samples you
  paste. "Improve from my edits" sends the history entries you corrected.

These requests use your OpenRouter account and are processed under OpenRouter's
and the providers' policies and your account settings. Zero-retention routing,
on by default, asks for cleanup requests to go only to providers that don't
retain them; audio retention follows your OpenRouter account's settings.

## The microphone and keyboard

The app records; the keyboard never does. The keyboard uses Full Access only to
exchange commands, drafts, and finished text with the app. Typing on its letter
keys never leaves the keyboard.

While the mic is on, iOS shows the recording indicator. Between takes the app
keeps only the newest half second of audio in memory, continuously overwritten,
so a take can begin the moment you press. It is never saved or sent. The mic
stays on until you turn it off, or, with Auto-off, after one minute of quiet or
twenty minutes.

## What stays on your device

Your API key, preferences, transcript history and edits, usage totals, and
diagnostic logs (which can contain transcripts). Keep recordings is on by
default and keeps each take's audio until you delete it; failed takes keep their
audio so you can retry them. The app and its keyboard share one app-group
container. Device backups may include these files.

yapping contains no advertising, analytics, or tracking.

## Your controls

History → Clear deletes history, logs, saved recordings, and recovery audio.
You can delete single entries, turn Keep recordings off, or clear the API key in
Settings. Microphone access and Full Access can be revoked in iOS Settings.
Deleting data on your device does not delete what a provider already retained.

## Changes and contact

Changes are published at this address with a new effective date. Questions go
to [GitHub issues](https://github.com/y0mingzhang/yapping/issues).

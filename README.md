# AI Take Call

> Your phone, now programmable. AI makes and takes calls on your Mac — on your iPhone number.

**[Website](https://aitakecall.com)** · **[Latest release](https://github.com/learners-superpumped/aitakecall-release/releases/latest)** · **[한국어 README](README.ko.md)**

---

## What is AI Take Call?

A macOS app that makes and takes calls with AI on your iPhone number. Hook up your own OpenAI, Gemini, or ElevenLabs key. AI answers inbound calls with a live transcript on your Mac, and places outbound calls from your iPhone number when you ask.

- **Your iPhone number — unchanged.** No new SIM, no porting, no side numbers.
- **Bring your own API key.** The app is free; you pay your AI provider directly.
- **Per-contact prompts, voices, and memory.** Tailor behavior for every number.
- **MCP tools on every call.** Extend the AI with your own tools, just like Claude Desktop or Cursor.

For the full product tour, visit **[aitakecall.com](https://aitakecall.com)**.

## Requirements

- macOS 13 Ventura or later
- An iPhone signed in with the same Apple ID
- An API key from OpenAI, Google (Gemini), or ElevenLabs

## Download

- **Latest release:** [github.com/learners-superpumped/aitakecall-release/releases/latest](https://github.com/learners-superpumped/aitakecall-release/releases/latest)
- After install, the app updates itself automatically through Sparkle using the `appcast.xml` in this repository.

## About this repository

This repository is **not** the app source code. It hosts the public-facing artifacts of the AI Take Call app:

| File / Feature | Purpose |
| --- | --- |
| `appcast.xml` | Sparkle auto-update feed consumed by the Mac app |
| `force-update.json` | Force-update switch the app checks at launch |
| GitHub Releases | Signed DMG downloads for every version |
| Issues tab | Public bug reports and feature requests |

For the product itself, see **[aitakecall.com](https://aitakecall.com)**.

## Report a bug or request a feature

We use [GitHub Issues](https://github.com/learners-superpumped/aitakecall-release/issues) as the public tracker.

- **Bug report** — include your macOS version, app version, AI provider (OpenAI / Gemini / ElevenLabs), and reproduction steps. Logs and screenshots help a lot.
- **Feature request** — describe the use case: what you're trying to do, and why the current behavior falls short.
- **Security issue** — please **don't** open a public issue. Contact us privately (see the security notice in the issue template).

> [!WARNING]
> Never paste API keys, recordings, or call transcripts that contain personal information into public issues. Redact phone numbers, names, and secrets before attaching logs.

## Links

- Homepage — [aitakecall.com](https://aitakecall.com)
- Releases — [github.com/learners-superpumped/aitakecall-release/releases](https://github.com/learners-superpumped/aitakecall-release/releases)
- Issues — [github.com/learners-superpumped/aitakecall-release/issues](https://github.com/learners-superpumped/aitakecall-release/issues)
- 한국어 README — [README.ko.md](README.ko.md)

## License

The release assets and feed files in this repository are distributed for use with the AI Take Call application. All rights reserved.

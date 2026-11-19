# Clipper

Turn a long video into ready-to-post **Shorts, Reels and TikToks** on your own PC or Mac: it finds the best
moments, frames them vertically, adds word-by-word captions and evens out the sound.

**Free.** Everything runs on your PC; your videos are never uploaded.

## Download

Get the newest version from **[Releases](../../releases/latest)**:

| File | For |
|---|---|
| `Clipper-GPU-setup.exe` | PCs with an **NVIDIA** graphics card (much faster) |
| `Clipper-CPU-setup.exe` | Any Windows 10/11 PC (slower) |
| `Clipper-mac.dmg` | Macs with Apple Silicon (M1 or newer), macOS 12+ |

Everything is included: no extra downloads on first run.

### "Windows protected your PC"

Clipper isn't code-signed (it's a free personal project), so Windows shows this warning the first time.
Click **More info** → **Run anyway**. The installer only installs Clipper for your Windows user.

### Mac: "Apple could not verify Clipper"

Clipper isn't notarized by Apple (free personal project). Open the .dmg, drag Clipper to Applications, try to open
it once, then go to **System Settings → Privacy & Security** and click **Open Anyway** (enter your password).
After that it opens normally.

## What it does

- Drop a long video (MP4, MOV, MKV, WebM; any length, up to 4K and beyond).
- Picks the best moments: with the free picker, or with **Claude AI** if you add your own key.
- Frames them for 9:16, 4:5, 1:1 or 16:9: follows the speaker, split screen for two people, follows the action in
  gameplay and sports.
- Word-by-word captions (English) in 11 styles and 7 fonts.
- Short editor: trim, change layout or who to follow, fix caption words, rename.
- Export in 720p, 1080p, 1440p or 4K.

## Claude AI (optional)

Clipper works without AI. With **your own** Anthropic API key, Claude picks the moments (with titles) and checks
caption words. In Clipper, click **AI: off** in the top bar, paste your key and press **Test and save**.

- Create a key at [console.anthropic.com](https://console.anthropic.com) → API keys (add a little credit first).
- Cost is billed by Anthropic to your account: about **$0.03** (Speed) to **$0.06** (Quality) per video.
- Your key is stored encrypted on your PC for your Windows user, and only sent to Anthropic.
- With a key, only the spoken words as text (and a few still frames for action videos) go to Anthropic.
- Tip: set a monthly spending limit in the Anthropic Console.

## Requirements

- Windows 10 or 11, 64-bit, ~5 GB free disk space; or a Mac with Apple Silicon and macOS 12 or newer.
- GPU edition: an NVIDIA graphics card with a recent driver. Other PCs: use the CPU edition.

## Licenses

Clipper uses open-source software, including FFmpeg (LGPL 2.1+), OpenAI Whisper, OpenCV and others. See
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt), also available in Clipper under **AI settings → Licenses**.

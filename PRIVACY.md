# Clipper Privacy Notice

Clipper is built to keep your videos on your own computer. This page explains exactly what stays local and what doesn't.

## What stays on your PC

- **Your videos.** Clipper processes video files locally. Your video files are never uploaded by Clipper.
- **Your clips and edits.** Everything Clipper creates is saved on your computer.
- **Transcription.** Speech-to-text runs locally on your machine.
- **Free moment picker.** The free picker runs entirely on your PC and sends nothing over the internet.

## What is sent when you use the optional AI picker

Only when you turn on the Claude AI picker, and only for the videos you process with it, Clipper sends the following to Anthropic:

- the **spoken words of the video as text** (the transcript);
- **a few still frames** for action videos.

Your video file itself is not sent. This data goes directly from your computer to Anthropic using your own API key. It does not pass through any server run by the author of Clipper.

Anthropic handles this data under its own terms and privacy policy: https://www.anthropic.com/legal/privacy

## Your API key

- Your Anthropic API key is stored encrypted on your PC, for your user account.
- It is sent only to Anthropic, to make the requests described above.
- You can remove it at any time from Clipper's settings.

## What the author receives

The author of Clipper does not receive your videos, transcripts, frames, clips or API key.

## Questions

Open an issue at https://github.com/prmoon1/clipper-downloads/issues

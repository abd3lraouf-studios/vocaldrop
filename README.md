<!-- BEGIN abd3lraouf-studios:hero -->
<p align="center">
    <img src="art/vocaldrop-icon.png" alt="VocalDrop" height="120">
</p>

<h1 align="center">VocalDrop</h1>

<p align="center">
    <strong>Separates vocals from any track on your own CPU or GPU. Studio-grade results, and your audio never leaves the machine.</strong><br>
    macOS (Apple Silicon) · Windows · Linux · Free
</p>

<p align="center">
    <a href="https://github.com/abd3lraouf-studios/vocaldrop/releases/latest"><strong>Download — macOS, Windows, Linux →</strong></a>
</p>

<p align="center">
    <a href="https://abd3lraouf.dev/projects/vocaldrop/">abd3lraouf.dev/projects/vocaldrop/</a>
</p>
<!-- END abd3lraouf-studios:hero -->

<p align="center">
  <a href="https://github.com/abd3lraouf-studios/vocaldrop/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/abd3lraouf-studios/vocaldrop?display_name=tag&label=download&color=b98cff" /></a>
  <a href="https://github.com/abd3lraouf-studios/vocaldrop/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/abd3lraouf-studios/vocaldrop/total?label=downloads&color=blue" /></a>
  <a href="#"><img alt="Platform" src="https://img.shields.io/badge/platform-macOS%20%C2%B7%20Windows%20%C2%B7%20Linux-000000" /></a>
  <a href="#"><img alt="Price" src="https://img.shields.io/badge/price-free-success" /></a>
  <a href="#"><img alt="Privacy" src="https://img.shields.io/badge/privacy-100%25%20offline-blueviolet" /></a>
  <a href="https://github.com/abd3lraouf-studios/vocaldrop/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/abd3lraouf-studios/vocaldrop?style=social" /></a>
</p>

<p align="center">
  <a href="#-installation">Install</a> ·
  <a href="#-features">Features</a> ·
  <a href="#-the-app">The app</a> ·
  <a href="#-why-vocaldrop">vs. other tools</a> ·
  <a href="#-faq">FAQ</a>
</p>

---

**VocalDrop** is a free **AI vocal isolator** that **extracts the vocals out of any song** — right on your own computer. Drop in a track or video, and state-of-the-art **RoFormer** neural models pull a clean **vocal stem** (a ready-to-use **acapella**) away from the music in seconds — with **no uploads, no accounts, no quotas, and no watermarks**. You get the **instrumental** in the same pass, so it doubles as a **vocal remover** too. It also converts between audio formats, removes silence, and chains it all into one run. Runs on **macOS, Windows, and Linux**, with automatic **Metal (MPS) GPU acceleration** on Apple Silicon.

Whether you're pulling an **acapella for a remix, an isolated vocal for sampling, a clean instrumental, a karaoke track, or a podcast edit**, VocalDrop gives you studio-grade separation without the subscription — your audio never leaves your machine.

## ✨ Features

- 🎤 **Extract vocals** — Isolate a clean vocal stem from any song. Two modes: **Fast** (a single BS-Roformer pass, quick and clean) or **Max** (a 3-model ensemble → blended → de-reverbed → de-noised/de-bleeded for the highest fidelity acapella).
- 🎸 **…and the instrumental** — Every separation gives you both stems, so VocalDrop is a **vocal remover** as well — mute the vocals for an instant instrumental or karaoke track.
- 🎛️ **Convert formats** — Transcode to `mp3`, `wav`, `flac`, `m4a`, `aac`, `ogg`, `opus`, or `aiff`, preserving metadata and cover art.
- 🤫 **Remove silence** — Adaptive silence detection with click-free crossfade welding — perfect for podcasts, lectures, and live recordings.
- 🔗 **Chain in one pass** — Extract vocals → remove silence → convert, all in a single drag-and-drop run.
- 🎞️ **Video support** — Drop in a music video or movie clip; VocalDrop extracts the audio, isolates the vocal (or instrumental), and can re-mux a synced video with the stem you chose.
- 🖱️ **Right-click Quick Actions** — Isolate a vocal straight from your file manager (Finder Quick Actions on macOS).
- ⌨️ **Full CLI** — Everything the app does is scriptable from the terminal (`vocaldrop vocals song.mp3 --quality max`), with `--json` output for pipelines.
- 🔒 **Private by design** — all processing runs locally; **your audio and files never leave your computer**. No sign-up, no API key. (Anonymous crash & usage diagnostics help improve the app — no personal data, no file contents or paths.)

## 📸 The app

<p align="center">
  <img src="docs/screenshots/01-workspace.png" width="900" alt="VocalDrop workspace: a queue of audio and video tracks on the left, the per-track signal chain (extract vocals, de-noise, enhance, remove silence, convert) in the center, and a feed of finished results on the right" />
</p>

<p align="center"><em>One window, whole workflow.</em> Drop a mix of <b>audio and video</b> into the queue, dial in the per-track signal chain — <b>extract vocals → de-noise → AI enhance → remove silence → convert</b> — and every finished stem lands in the Results feed, ready to play or reveal in your file manager. Everything runs locally.</p>

## 🆚 Why VocalDrop?

Most "free" vocal extractors are websites that **upload your audio to someone else's server**. VocalDrop is different.

| | **VocalDrop** | Online tools (e.g. vocalremover.org) | Ultimate Vocal Remover (UVR5) | Moises | iZotope RX |
|---|:---:|:---:|:---:|:---:|:---:|
| **Local processing / files stay private** | ✅ | ❌ uploads your files | ✅ | ❌ cloud | ✅ |
| **Free** | ✅ | limited free tier | ✅ | paid | $$$ paid |
| **Native desktop app (Mac/Win/Linux)** | ✅ | browser only | ❌ Python/Tk GUI | ✅ | ✅ |
| **No watermarks / quotas** | ✅ | ❌ | ✅ | ❌ | ✅ |
| **Apple Silicon GPU (Metal)** | ✅ | n/a | manual setup | ✅ | ✅ |
| **One-click install** | ✅ | n/a | ❌ dev setup | ✅ | ✅ |
| **No account / login** | ✅ | ⚠️ often required | ✅ | ⚠️ required | ✅ |

Looking for a **free UVR5 alternative**, a **private Moises alternative**, or an **offline acapella extractor with no upload**? That's VocalDrop. (It uses the same RoFormer model family as UVR5, but ships as a polished, native desktop app — no Python setup required.)

## 📥 Installation

Grab the build for your OS from the [**latest release**](https://github.com/abd3lraouf-studios/vocaldrop/releases/latest). The first run downloads the AI engine and models (~2 GB, one-time) — after that VocalDrop is **fully offline**.

### 🍎 macOS (Apple Silicon)
1. Download **`VocalDrop-<version>-arm64.dmg`**, open it, and drag **VocalDrop** into **Applications**.
2. ⚠️ **First launch:** this build isn't code-signed yet, so macOS says *"VocalDrop cannot be opened…"*. **Right-click (⌃-click) the app → Open → Open anyway.**

### 🪟 Windows (x64)
1. Download **`VocalDrop-Setup-<version>.exe`** and run it.
2. ⚠️ **First launch:** SmartScreen may warn (unsigned build). Click **More info → Run anyway**.

### 🐧 Linux (x64)
1. Download **`VocalDrop-<version>.AppImage`**, then `chmod +x VocalDrop-*.AppImage` and run it.

> **Verify the download:** each asset ships a matching `.sha256` — compare it with `sha256sum` (Linux/Windows) or `shasum -a 256` (macOS).

**Requirements:** macOS on **Apple Silicon** (M1–M4), **Windows 10/11 (x64)**, or **Linux (x64)**. **ffmpeg is bundled** — nothing else to install. Separation is **GPU-accelerated on Apple Silicon (Metal)**; Windows and Linux run on multi-core **CPU** (slower, but fully offline).

> VocalDrop is **free to use** and distributed as a ready-made app — no build step needed. (It's closed source; the public repo holds releases, screenshots, and this README.)

## 🚀 Quick start

**In the app:** drag an audio or video file onto the window → tick **Vocals / Silence / Convert** → press **Process**. Your isolated vocal (and the instrumental) land in the Results feed.

**From the CLI** (bundled inside the app at `…/Resources/bin/vocaldrop` — add it to your `PATH`):
```bash
# Extract vocals — fast (seconds) or max (best quality)
vocaldrop vocals song.mp3 --quality fast
vocaldrop vocals song.mp3 --quality max

# Convert formats (metadata + cover art preserved)
vocaldrop convert song.wav --to mp3 --bitrate 320k

# Remove silence
vocaldrop silence talk.m4a --threshold -40dB --min 0.5

# Chain everything in one pass
vocaldrop run song.mp3 --vocals=max --silence --convert mp3 --out ~/Desktop/out
```
Add `--json` to any command for machine-readable progress.

## 🧠 How it works

VocalDrop is built on the **RoFormer** family of separation models — the same state-of-the-art architecture behind the best commercial stem-separation tools.

- **Fast mode** runs a single high-SDR BS-Roformer pass. Great for clean sources and near-real-time on Metal.
- **Max mode** runs a **3-model ensemble**: three specialized RoFormer checkpoints are each run, their vocal estimates are **blended** (weighted averaging in `ensemble.py`), then **de-reverbed** and **de-noised / de-bleeded** for the cleanest possible acapella.

All inference runs through [audio-separator](https://github.com/nomadkaraoke/python-audio-separator). On Apple Silicon it uses **Metal (MPS)** acceleration (falling back to CPU per-op where needed via `PYTORCH_ENABLE_MPS_FALLBACK`); on Windows and Linux it runs on CPU. Under the hood it's an **Electron** shell over a **Deno** engine sidecar, with a matching **CLI** — so the same engine powers the GUI and your scripts.

## 🔒 Privacy & system requirements

- **Privacy:** **Your audio never leaves your computer** — all separation, conversion, and cleanup run locally; no cloud, no account. VocalDrop collects **anonymous diagnostics** (crash reports and basic usage events, via Google) to fix bugs and improve the app — never your file contents, file paths, or any personal data. Other network access is limited to the one-time engine/model download on first launch, online URL ingest when you paste a link, and the optional "check for updates" toggle.
- **System:** macOS on **Apple Silicon**, **Windows 10/11 (x64)**, or **Linux (x64)**. GPU acceleration (Metal) on Apple Silicon; CPU on Windows/Linux.
- **Disk:** ~2 GB for the full model set (Fast mode needs only ~200 MB).
- Runtime state (Python runtime, temp files, default output) lives in your user app-data dir (e.g. `~/Library/Application Support/VocalDrop/` on macOS).

## ❓ FAQ

**Does it extract the vocals, or remove them?**
Both. Every run separates the song into a **vocal stem** (acapella) and an **instrumental** — keep whichever you need.

**Is my audio uploaded anywhere?**
No. VocalDrop runs entirely on your computer. The first launch downloads the AI models once; after that it's fully offline.

**Does it use the GPU?**
On Apple Silicon, yes — Metal (MPS), automatically. On Windows and Linux it runs on CPU (you can force CPU on Mac too in Settings → Engine).

**Is it really free?**
Yes — free to use for everyone. No ads, no watermarks, no subscription, no feature paywall, no account. (VocalDrop is closed source; it's just given away free.)

**Which platforms are supported?**
macOS (Apple Silicon), Windows 10/11 (x64), and Linux (x64). Intel-Mac builds aren't provided.

**Why do I get an "unidentified developer" / SmartScreen warning?**
The current builds aren't code-signed/notarized yet. macOS: right-click → **Open**. Windows: **More info → Run anyway**. Signed builds are on the roadmap.

**How is this different from Ultimate Vocal Remover (UVR5)?**
Same underlying RoFormer models, but VocalDrop is a **native, polished desktop app** with drag-and-drop, video support, format conversion, silence removal, and file-manager integration — no Python/Tkinter setup required.

## 🛣️ Roadmap

- [ ] Code-signing & notarization (no Gatekeeper / SmartScreen warning)
- [ ] NVIDIA (CUDA) GPU acceleration on Windows & Linux
- [ ] In-app auto-update
- [ ] Real-time preview before committing a full render
- [ ] More separation targets (drums, bass, piano stems)

## 🤝 Feedback

VocalDrop is free to use and closed source. This repo hosts the downloads, screenshots, and this README — so **bug reports and feature requests are very welcome** in the [Issues](https://github.com/abd3lraouf-studios/vocaldrop/issues).

<!-- BEGIN abd3lraouf-studios:press -->
## Press & marketing assets

VocalDrop is a free AI vocal isolator and remover for macOS, Windows and Linux that runs entirely on your own hardware — no upload, no account, no watermark.

**Naming.** Written "VocalDrop" — one word, capital V and D. Never "Vocal Drop" or "Vocaldrop".

The press kit — icons, screen art, boilerplate, the fact sheet and a downloadable
archive — is at **[abd3lraouf.dev/press/vocaldrop/](https://abd3lraouf.dev/press/vocaldrop/)**.
<!-- END abd3lraouf-studios:press -->

## 📄 License & acknowledgements

VocalDrop is **free to use** software (closed source) © 2026 abd3lraouf Studios.

It stands on the shoulders of giants:
- The **RoFormer** separation models and their authors.
- [**audio-separator**](https://github.com/nomadkaraoke/python-audio-separator) — the inference engine.
- [Deno](https://deno.land), [Electron](https://www.electronjs.org/), and [ffmpeg](https://ffmpeg.org/).

> ⭐ If VocalDrop saves you a subscription, give it a star and tell a producer friend.

# AudioBookConverter

Converts any PDF or DRM-free ePub into an audiobook — for free.

<img width="2059" height="1420" alt="Screen 1" src="https://github.com/user-attachments/assets/49118e8c-bb57-4c25-88c5-610a570748a9" />
<img width="2059" height="1420" alt="Screen 5" src="https://github.com/user-attachments/assets/98397dec-eda1-4ac7-b441-701d45ea5947" />
<img width="2059" height="1420" alt="Screen 7" src="https://github.com/user-attachments/assets/4b8afc64-e067-4d19-b7bf-2b96c68ec2c7" />


## What it does

AudioBookConverter converts text and ebooks into narrated .m4b audiobooks using on-device text-to-speech (Kokoro TTS) — no cloud processing, no subscription. Import your source, choose a voice, edit chapters, add cover art, and export a ready-to-play audiobook file.

- On-device TTS conversion — text/ebooks → narrated audio, no internet required after setup
- Chapter editing — adjust and organize chapters before export
- Custom cover art — add artwork for your library
- Native .m4b export — plays natively in Apple Books, Overcast, and any standard audiobook player
- Free to use — no subscription, no account required

## Demo

[Embed or link a short screen recording / GIF here showing: import → convert → edit chapters → add cover → export]

## Download

[![Download DMG]((https://github.com/OmarPuig75/AudioBookConverter/releases/download/v1.1.0/AudioBookConverter.dmg))

Apple Silicon Macs only. Requires macOS 14 (Sonoma) or later on an M1 or newer Mac. Intel Macs are not supported — see System Requirements for why.

## System Requirements
- macOS 14 (Sonoma) or later
- Apple Silicon (M1 or later) — Intel Macs are not supported. AudioBookConverter's TTS conversion pipeline runs on MLX, Apple's machine learning framework built exclusively for Apple Silicon's unified memory architecture. There is no Intel/x86 code path, so the app cannot run on Intel-based Macs.
- ~500 MB free disk space (the app itself is ~20–30 MB; the Kokoro TTS voice model downloads separately on first use, ~300 MB, one-time)

## Installation
1. Download the .dmg from the latest release
2. Open the .dmg and drag AudioBookConverter into your Applications folder
3. On first launch, macOS will show a one-time security dialog — see Opening the app below.

## Opening the app (Gatekeeper warning)

Since AudioBookConverter isn't distributed through the Mac App Store, macOS will show a one-time warning on first launch, since it was downloaded from the internet rather than the App Store. This is expected — the app is notarized by Apple, so macOS will confirm no malicious software was detected.

1. Open the .dmg and double-click AudioBookConverter
2. You'll see a dialog: "AudioBookConverter is an app downloaded from the Internet. Are you sure you want to open it?" — along with confirmation that Apple checked it and found nothing malicious
3. Click Open

That's it — you won't be prompted again on future launches.

## Origin story

Ever bought an audiobook and wished you could hear it in a different voice? Unless you already know the narrator, picking an audiobook is often a bit of a gamble — you're stuck with whatever voice the publisher chose. AudioBookConverter started as a simple fix for that: convert the books and documents you already have into an audiobook narrated the way you want, on your own terms.



## License

AudioBookConverter is free to download and use. The source code is closed and not publicly available.


I code, tinker and build my own projects, AI or not, usually to fix a problem I actually have. The four below were built on my own and published together in September 2026; new projects go up here as I build them.

- [**fcpxml-roughcut**](https://github.com/Bouliw/fcpxml-roughcut): Roughcut, a Mac app that turns a folder of footage into a rough cut in Final Cut Pro, with vertical Shorts and subtitles (Swift, Python, Whisper). A language model picks the takes; the scripts do the frame maths and check every timeline before import. On a real test, 47 minutes of 4K vlog footage became a 22-minute rough cut and three Shorts in 31 minutes. [Download the app](https://github.com/Bouliw/fcpxml-roughcut/releases/latest).
- [**vigie**](https://github.com/Bouliw/vigie): a blue team tool that reads Windows and Linux logs (EVTX, Sysmon, auth.log), runs 23 Sigma detection rules with its own engine, including correlations like brute force and password spraying, and writes a report mapped to MITRE ATT&CK (Python). [See an example report](https://bouliw.github.io/vigie/example-report.html).
- [**boulito**](https://github.com/Bouliw/boulito): a voice assistant for macOS that runs entirely on the Mac (Python, MLX, Parakeet, Qwen 3.5). Hold a key or say its name to open apps, drive YouTube in Safari, set timers or dictate. Simple commands go through rules in about 0.2 s; the local model only steps in for free-form requests. [Download the app](https://github.com/Bouliw/boulito/releases/latest).
- [**doc-indexer-macos**](https://github.com/Bouliw/doc-indexer-macos): on-device OCR and text extraction for a folder of paperwork (Python, Swift, Apple Vision). It turns scanned and photographed documents into plain text that grep or an AI agent can search, without a single document leaving the Mac.

**Stack**: Python, Swift, shell, ffmpeg, whisper.cpp, MLX, local LLMs, Sigma

[LinkedIn](https://www.linkedin.com/in/martin-laffont-1a218b250)

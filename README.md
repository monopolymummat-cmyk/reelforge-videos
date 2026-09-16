# ReelForge Videos

Final video masters produced by the **ReelForge** studio. Every video is archived here permanently — the MP4 lives as a **release asset** (direct-download, works in any browser without login), and its script / upload kit / poster live in the folder of the same name.

## 📼 Why the US Government Refuses to Slow Down AI

**Download the master (1080p H.264, ~304 MB):**

> **[us-ai-slowdown-1080p.mp4](https://github.com/monopolymummat-cmyk/reelforge-videos/releases/download/us-ai-slowdown/us-ai-slowdown-1080p.mp4)**

| | |
|---|---|
| Runtime | **8:14** (494.4 s) · 1920×1080 · H.264 |
| Edit | fast-cut documentary — 199 scenes, ~2.5 s average shot |
| Sections | PART 1–4 + CONCLUSION chyrons |
| Media mix | **35 cinematic stock clips + 140 stock photos + 22 real photos of the named people** — no AI art, no captions |
| People featured | Sam Altman, Donald Trump, JD Vance, Dario Amodei, Jensen Huang, Mark Zuckerberg, Bernie Sanders, Elon Musk, Sundar Pichai, Lisa Su, Marc Andreessen, Pam Bondi, David Sacks, Lina Khan, Gina Raimondo, Andrew Yang (Xi Jinping on thematic US/China footage) |
| Audio | **silent master by design** — mux your own voiceover |

### Files in this repo

| File | What it is |
|---|---|
| [`us-ai-slowdown/narration-script.md`](us-ai-slowdown/narration-script.md) | Timed voiceover script — the owner's 1,221 words verbatim with per-scene timestamps (150 wpm sync map, TTS-ready) |
| [`us-ai-slowdown/upload-kit.md`](us-ai-slowdown/upload-kit.md) | YouTube upload kit — title, description, tags, chapters (from the 5 section chyrons) |
| [`us-ai-slowdown/poster.jpg`](us-ai-slowdown/poster.jpg) | Poster / thumbnail frame (1920×1080) |

### Adding narration

The master is silent so you can lay your own voice. Easiest ways:

- Studio: use the **“Upload audio”** flow in ReelForge, or
- Local: `ffmpeg -i us-ai-slowdown-1080p.mp4 -i voiceover.mp3 -c:v copy -c:a aac -shortest final.mp4`

---
*ReelForge — cinematic short-form studio. This archive exists so the owner can re-download any master at any time.*

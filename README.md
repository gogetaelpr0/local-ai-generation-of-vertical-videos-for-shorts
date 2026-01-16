<div align="center">

  <img src="https://placehold.co/1200x240/0f0f0f/6366f1?text=SHORTLOCAL&font=orbitron" alt="ShortLocal" width="100%">

  <h3>— generate shorts on your machine —</h3>

  <br>

  <a href="https://github.com/yourusername/shortlocal/releases/latest">
    <img src="https://img.shields.io/badge/Download%20v1.0-6366f1?style=for-the-badge&logo=github&logoColor=white" height="32">
  </a>

</div>

---

### What is ShortLocal?

ShortLocal is a free desktop application that creates simple AI-generated Shorts from text — entirely offline.

You provide a prompt:  
"A robot explaining photosynthesis in a garden"

The app generates:  
- A synthetic voiceover  
- AI-generated illustration-style scenes  
- Auto-synced captions  
- A 1080x1920 MP4 file  

All processing occurs on your computer. No internet connection is required after installation. No account. No watermark.

---

### Capabilities (v1.0)

- Text-to-script using Phi-3-mini (quantized, CPU-compatible)  
- Voice synthesis via Coqui TTS (4 English voices, synthetic quality)  
- Scene generation using Stable Diffusion Turbo (illustration style only)  
- Caption rendering with basic TikTok-style styling  
- Export to 1080x1920 MP4 (H.264/AAC)  
- Local storage only: projects saved to ~/Documents/ShortLocal  
- Zero network activity by default

---

### Hardware Requirements

| Device              | Performance                     |
|---------------------|---------------------------------|
| Raspberry Pi 5      | 720p output, max 30 seconds, ~3x real-time |
| Standard laptop     | 1080p, ~1.5x real-time         |
| Desktop with RTX 3060+ | 1080p, ~0.4x real-time       |

Limitations:  
- Maximum video length: 45 seconds  
- Output is illustration-based — no photorealistic or live-action footage  
- Voice quality is synthetic and not suitable for professional narration  
- Does not edit existing video files — only generates new content from text

---

### Intended Use Cases

- Educators creating quick explainers  
- Students producing project videos  
- Developers experimenting with local AI pipelines  
- Anyone seeking to avoid cloud-based video generators

This tool is not intended for professional content creators requiring cinematic quality or human-like voiceovers.

---

### Downloads

- Windows: [shortlocal-win.exe](https://github.com/yourusername/shortlocal/releases/download/v1.0/shortlocal-win.exe)  
- macOS (Apple Silicon): [shortlocal-mac-arm64.dmg](...)  
- Linux: [shortlocal-linux.deb](...)

All binaries are built from open-source code, contain no telemetry, and require no installation.

---

### License

MIT License. Free for personal and commercial use. You retain full ownership of all generated content.

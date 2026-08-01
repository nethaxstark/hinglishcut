# HinglishCut 🎬

> AI-Powered Hinglish Subtitle Generator & Editor for Indian Instagram Reels & YouTube Shorts.

HinglishCut transcribes Hindi audio using **Groq Whisper**, converts Hindi text to colloquial **Hinglish** (Hindi in Roman script) using **Groq Llama 3.1**, and provides full-fledged studio subtitle animation, positioning, and 100% loss-free or burned-in video export!

## ✨ Key Features

- 🎤 **Audio Extraction**: Native Web Audio API decoding (no SharedArrayBuffer or heavy WASM binaries required).
- ⚡ **Groq Whisper Transcription**: High-accuracy Hindi speech-to-text with word-level timestamp extraction (`timestamp_granularities[]=word`).
- 🤖 **Colloquial Hinglish Conversion**: Llama 3.1-8B Instant model transliterates Hindi to natural Hinglish in tight 2–3 word reel caption chunks.
- 🎨 **In-Depth Subtitle Styling**:
  - **Fonts**: Inter, Poppins, Baloo 2, Nunito.
  - **Presets**: Hormozi, Cyber Neon, Vertical Reel, Word Stack, Sidebar Strip, Minimal, Normal Clean.
  - **Text Customization**: Custom colors, active karaoke highlight color, stroke outline, letter spacing, text case (`ALL CAPS`, `lowercase`, `Title Case`), and background opacity.
- 📍 **Everywhere Subtitle Placement**:
  - **3x3 Position Grid**: 1-click positioning for Top-Left, Top-Center, Top-Right, Center, Bottom-Center, etc.
  - **X & Y Sliders**: Fine-tune position numerically.
  - **Drag & Drop**: Click or touch and drag subtitles directly anywhere on the video preview.
- ⏱️ **Timestamp Editor**:
  - `⏱ MM:SS.ms` timestamp badges.
  - 1-click `Set Start = Now` and `Set End = Now` buttons for syncing subtitles to video playback.
- 🎬 **Export Options**:
  - **Burned-In Video Export**: WebMediaRecorder renders subtitles directly onto canvas using native `requestVideoFrameCallback` for silky 60 FPS playback without lag.
  - **Package Export**: Raw untouched video file + separate `.SRT` subtitle file.
  - **SRT Export Only**.

## 🚀 Getting Started

1. Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Safari).
2. Enter your free **Groq API Key** (get one at [console.groq.com](https://console.groq.com)).
3. Upload your reel video (`.mp4` / `.mov` / `.webm`).
4. Click **"Generate Subtitles ✨"**.
5. Customize subtitle style and position, then click **`Export Burned-In Video (With Subtitles)`**!

## 📄 License

MIT License.

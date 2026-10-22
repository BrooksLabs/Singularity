# Singularity - The Everything Ai-Assistant

<p align="center">
  <img width="300" height="300" alt="Singularity" src="https://github.com/user-attachments/assets/d54501ca-435d-4a3c-abf7-08f62073d4c5" />
</p>
<p align="center"><em>Singularity - Unlock the Universe!</em></p>

---

**Singularity** is a self-learning, autonomous local desktop agent built for Windows. It acts as an ambient "everything app" running quietly in your system tray, capable of executing system tasks, managing universal file formats, streaming media, automating web workflows, and adapting its interface on the fly.

---

## 🚀 Core Capabilities

### 1. Adaptive Multi-Mode GUI & 3D Visuals
Powered by **Three.js**, Singularity features a real-time reactive 3D core that dynamically morphs its aesthetic based on your workflow:
* **Spotify Mode**: High-contrast OLED dark theme with vibrant neon green accents for music management.
* **Netflix Mode**: Crimson-accented cinematic carousels for video streaming and release schedules.
* **Console Mode**: Native-inspired layouts for retro and modern emulation.
* **Ambient RGB Wave**: Smooth mathematical color interpolation across all UI elements.

### 2. Zero-Path File Indexing & Universal ROM Launcher
* **Fuzzy File Crawler**: Automatically indexes your local hard drives (`Desktop`, `Downloads`, `Documents`, `Games`, `ROMs`) for instant retrieval. Just type *"Play Pokemon Emerald"* or drop a file onto the HUD.
* **Emulation Engine**: Features built-in WebAssembly RetroArch cores (`.gba`, `.nds`, `.nes`, `.snes`, `.n64`, `.psx`) and auto-provisioning standalone core routing for high-end consoles (`.iso`, `.rvz`, `.xci`, `.nsp`, `.xex`).

### 3. Browser Suite & Universal Media Downloader (`yt-dlp`)
* **Firefox Integration**: Automatically imports your Firefox bookmarks and profile data into an internal dashboard.
* **Context-Menu Web Bridge**: Right-click any video, audio stream, or webpage to instantly download high-definition **1080p `.MP4`** or **320kbps `.MP3`** files directly to your Downloads folder.
* **Auto-Tagging Pipeline**: Automatically queries public APIs (IMDb / iTunes / MusicBrainz) to inject official cover art, release years, cast credits, and ID3/MP4 metadata headers into downloaded files.

### 4. Autonomous Web Automation & Financial Sync ("Muse" Engine)
* **Web Task Execution**: Powered by Puppeteer/Playwright to natively navigate web apps, manage Amazon carts, and interact with services like Uber Eats.
* **Secure Banking & Calendar Sync**: Encrypted local credential vault framework to log into bank portals, categorize monthly spending habits, and sync schedules directly with Microsoft Outlook.

### 5. Self-Learning & Self-Healing Loop
* **Recursive Error Correction**: If a dynamically generated PowerShell script or OS task fails, Singularity captures the error, feeds it back to the local LLM, rewrites the code, and retries autonomously.
* **Permanent Neural Memory**: Successfully executed scripts are saved to `memory.json`, expanding the agent's capabilities over time without requiring user intervention.

---

## 🛠️ Tech Stack
* **Desktop Runtime**: Electron (Node.js backend with Administrator privileges)
* **AI Engine**: Local Ollama (`llama3`) / Cloud API fallback with strict JSON parsing
* **Graphics**: Three.js (WebGL)
* **Automation**: `@nut-tree/nut-js`, Puppeteer, PowerShell COM Automation
* **Media & Conversions**: FFmpeg, 7-Zip CLI, `yt-dlp`, Pandoc, ImageMagick

---

## ⚙️ Quick Setup & Development

1. Ensure you have **Node.js**, **Electron**, and **Ollama** installed on your Windows machine.
2. Place your assets (`image_0.ico`, `image_1.ico`) in the root directory.
3. Run the automated initialization/update batch script with full administrator rights:
   ```cmd
   Singularity.bat

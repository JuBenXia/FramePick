# FramePick 🎬✂️

**Drag & drop a video → Capture any frame → Add text overlays → Export your thumbnail**

A zero-dependency, single-file HTML tool for capturing video frames and designing custom thumbnails. Everything runs in your browser — no uploads, no servers, no AI.

![FramePick Preview](framepick_preview.png)

---

## ✨ Features

- **🎯 Frame Capture** — Click any point on the timeline to grab the perfect frame; fine-tune with precision slider
- **🎞️ Filmstrip Timeline** — Full-progress thumbnail preview loads on launch, instantly see what's at every moment
- **✏️ On-Canvas Text Editing** — Double-click text to edit content directly on the canvas, just like Photoshop/Canva
- **↕️ Drag & Resize** — Drag text to reposition (X/Y both axes); drag corner handles to scale font size
- **🎨 Full Style Control** — Font size, color, stroke (width + color), alignment (left/center/right), independent X/Y offset
- **📐 Aspect Ratio Presets** — Optimized for short-form video platforms:
  - **9:16** — TikTok, YouTube Shorts, Instagram Reels, Kuaishou
  - **16:9** — YouTube, Bilibili, standard landscape
  - **1:1** — Instagram feed, social media
  - **4:3, 21:9** — Classic & cinematic
  - **Original** — Auto-detect video aspect ratio
- **📥 One-Click Export** — Save as PNG directly to your device

## 🚀 Usage

1. Serve `framepick.html` with any static server:

   ```bash
   python -m http.server 8080
   # or VS Code Live Server, npx serve, etc.
   ```

2. **Drag & drop** any video file onto the page
3. Click the timeline to seek, then click **Capture Frame** to lock the frame into the editor
4. Add title/subtitle text, double-click to edit, drag to position, drag handles to resize
5. Select output resolution → **Export PNG**

## 🖱️ Quick Reference

| Action | Result |
|--------|--------|
| Drag video onto page | Load video |
| Click filmstrip / timeline | Seek to time position |
| Capture Frame | Lock current frame to editor |
| Click text on canvas | Select (blue outline + corner handles) |
| Drag selected text | Move X/Y position |
| Drag corner handle | Resize font size |
| Double-click text | Inline edit text content |
| Right-click → Save As | Export PNG |

## 🛠️ Tech Stack

Pure **HTML5 Canvas + Vanilla JavaScript** — zero dependencies, single HTML file, works entirely offline.

---

Made with ❤️ by [JuBenXia](https://github.com/JuBenXia/FramePick)

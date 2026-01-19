# Faster-Whisper Colab → CapCut-Ready SRT

Generate **CapCut-compatible subtitles** (`.srt`) directly from `.mp4` or audio files using **Faster-Whisper on Google Colab**.

✔ No UI  
✔ No local setup  
✔ Works with MP4  
✔ English + Kiswahili  
✔ One-click Colab run  

---


## 🚀 Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HT5SdVshbHqjuzR3nvp3nPdeHJ8e7gv5?usp=sharing)

---

## 🧠 Why This Exists

Whisper-generated SRT files often fail in **CapCut** due to timestamp formatting.

This notebook:
- Fixes timestamp format (`HH:MM:SS,mmm`)
- Produces **CapCut-ready subtitles**
- Works directly with `.mp4` videos

---

## 📂 How to Use

1. Open the notebook in Colab
2. Enable **GPU** (Runtime → Change runtime → GPU)
3. Upload your `.mp4` or `.mp3` via the sidebar
4. Run all cells
5. Download:
   - `transcript.txt`
   - `transcript.srt`

---

## 🎥 Supported Formats
- `.mp4`
- `.mp3`
- `.wav`
- `.mkv`

FFmpeg automatically extracts audio.

---

## 🌍 Languages
- Auto-detect
- English
- Kiswahili
- Mixed-language content supported

---

## 🛠 Model Used
- `large-v3` (best accuracy)
- You can change to `medium` or `small` for speed

---

## 📌 Notes
- CapCut requires strict SRT formatting
- Do NOT rename file extensions manually
- This notebook handles formatting correctly

---

## 📺 Tutorial Video
📌 YouTube walkthrough: **(link here)**

---

## 📄 License
MIT

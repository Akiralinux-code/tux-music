# 🎵 Tux Music

**Tux Music** is a lightweight, cross-platform music player written in C, designed for simplicity and speed. It runs on both **Linux** and **Windows**, offering basic audio playback from the terminal.

---

## ✨ Features

- 🎧 Play music files from the terminal
- 🐧 Linux and 🪟 Windows support
- ⚡ Minimal dependencies
- 💻 Lightweight and fast

---

## 🚀 Getting Started

### 📦 Dependencies

#### On Linux:

- `gcc` or `clang`
- Audio library (e.g. ALSA, PulseAudio, or SDL depending on implementation)
- `make` (optional)

Install required tools:

```bash
sudo apt update
sudo apt install build-essential

On Windows:

    Use MinGW

    or compile using a supported IDE like Code::Blocks or Visual Studio with C support.

🛠️ Build Instructions
Linux (GCC)

gcc tuxmusic.c -o tuxmusic
./tuxmusic

Windows (MinGW)

gcc tuxmusic.c -o tuxmusic.exe
tuxmusic.exe

    Note: You may need to link with audio libraries (-lSDL, -lwinmm, etc.) depending on your implementation.

📁 Project Structure

tux-music/
├── tuxmusic.c       # Main source code
├── README.md        # Project documentation
└── LICENSE          # MIT License

📌 TODO

Playlist support

Pause / resume functionality

Metadata (ID3) display

GUI frontend (optional)

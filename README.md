
````markdown
# 🎧 Audio Overlay Repeater

A Python application that overlays an audio track on top of itself multiple times, with a custom delay between each repetition. You can use it from the command line or launch a simple GUI for real-time playback and export.

---

## ✨ Features

- 🔁 Repeat any audio file multiple times
- ⏱ Set custom delay between repetitions (in milliseconds)
- 🎛 GUI with file pickers and input fields
- 🎧 Real-time audio playback
- 💻 Full CLI support for batch or scripting use
- 🧪 Export final mixed track to MP3

---

## 📦 Requirements

- Python 3.7+
- `pydub`
- `tkinter` (comes preinstalled with Python)
- `ffmpeg` (required by pydub for decoding MP3)

---

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/HackerPrat/AOR-Audio-Overlay-Repeater-
cd AOR-Audio-Overlay-Repeater-
````

2. Install dependencies:

```bash
pip install pydub
```

3. Install FFmpeg if you haven’t already:

   * [FFmpeg Downloads](https://ffmpeg.org/download.html)
   * Add to PATH on Windows/macOS/Linux

---

## 🚀 Usage

### 🔹 GUI Mode

Just run:

```bash
AOR.exe
```

* Choose your input and output files
* Set number of repetitions
* Set delay in milliseconds
* Click `Export` to save

---

### 🔹 CLI Mode

```bash
AOR.exe -i input.mp3 -o output.mp3 5 250
```

**Arguments:**

| Argument  | Description                           |
| --------- | ------------------------------------- |
| `-i`      | Input audio file                      |
| `-o`      | Output audio file                     |
| `repeats` | Number of repetitions                 |
| `delay`   | Delay between repeats in milliseconds |

---

## 📂 Example

```bash
AOR.exe -i sound.mp3 -o layered.mp3 4 300
```

This will overlay the `sound.mp3` file on itself 4 times, with 300ms delay between each repetition and save it to `layered.mp3`.

---

## 🛠 Tech Stack

* Python 3
* Tkinter (GUI)
* Pydub (audio processing)
* FFmpeg (backend decoder)

---

## 📄 License

MIT License. Feel free to fork, contribute, or use in your projects.

---

## 👨‍💻 Contributing

Pull requests welcome! If you'd like to request a feature (e.g. fade-in, stereo panning, waveform display), feel free to open an issue.

---

## 🐍 Author

Built with ❤️ by \HackerPrat

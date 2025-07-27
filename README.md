
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

## 🖼 GUI Preview

<img src="gui-preview.png" alt="Audio Overlay GUI" width="600"/>

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
git clone https://github.com/yourusername/audio-overlay-repeater.git
cd audio-overlay-repeater
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
python track.py
```

* Choose your input and output files
* Set number of repetitions
* Set delay in milliseconds
* Click `Play` to preview or `Export` to save

---

### 🔹 CLI Mode

```bash
python track.py -i input.mp3 -o output.mp3 5 250 --play
```

**Arguments:**

| Argument  | Description                           |
| --------- | ------------------------------------- |
| `-i`      | Input audio file                      |
| `-o`      | Output audio file                     |
| `repeats` | Number of repetitions                 |
| `delay`   | Delay between repeats in milliseconds |
| `--play`  | Play the result after processing      |

---

## 📂 Example

```bash
python track.py -i sound.mp3 -o layered.mp3 4 300 --play
```

This will overlay the `sound.mp3` file on itself 4 times, with 300ms delay between each repetition, play it, and save it to `layered.mp3`.

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

Built with ❤️ by \[YourNameHere]

```

---

Would you also like:
- A logo for the project?
- GitHub Actions to package it into a `.exe` or `.app`?
- Or a PyInstaller `.exe` bundler for distribution?

Let me know and I’ll generate that next.
```

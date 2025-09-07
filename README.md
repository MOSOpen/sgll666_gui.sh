# sgll666_gui.sh
SGLL666 GUI is a Bash-based audio purification tool with a Zenity interface. It cleans .wav files by removing metadata, applies a unique SGLL666 rhythmic code, and logs each transformation. Designed for independent artists and sonic hackers. Free software under GPL v3.
# SGLL666 GUI 🎛️

**Graphical Audio Purification & Sealing Tool for Independent Artists**

SGLL666 GUI is a Bash-based script with a Zenity-powered interface, designed to help sonic creators cleanse `.wav` files of compromising metadata and seal them with a unique rhythmic code. Built by the Undersound Collective — hackers, musicians, and free spirits.

---

## 🧪 Features

- 🖼️ Graphical interface for selecting `.wav` files
- 🧼 Cleans metadata (e.g. encoder tags like `Lavf60.16.100`)
- 🔐 Seals files with a unique SGLL666 timestamp code
- 📜 Logs each transformation in `changelog.txt`
- ✅ Visual feedback via Zenity dialogs

---

## 🚀 How to Use

1. Make sure you have `ffmpeg` and `zenity` installed
2. Clone this repository or download `sgll666_gui.sh`
3. Run the script from terminal:

```bash
bash sgll666_gui.sh

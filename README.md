## Prerequisites

- **Python 3.10+**
- **FFmpeg** installed on your system `PATH`:
  - **Ubuntu / Debian**: `sudo apt-get install ffmpeg`
  - **macOS**: `brew install ffmpeg`
  - **Arch Linux**: `sudo pacman -S ffmpeg`
  - **Windows (Winget)**: `winget install Gyan.FFmpeg`

## Setup

1. **Create and activate a virtual environment**:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. **Install dependencies**:

   ```bash
   .venv/bin/pip install -r requirements.txt
   ```

## Running the Notebook

1. Open `audio_compression_spectrogram.ipynb` in VS Code, Cursor, Antigravity, or JupyterLab.
2. Select the **`.venv` (`Python 3`)** kernel.
3. Run the cells sequentially from top to bottom.

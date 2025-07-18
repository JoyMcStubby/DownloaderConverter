#  Downloader & Converter

A powerful and easy-to-use desktop application that lets you download videos and audio from YouTube and other supported sites. Built with PyQt6 and powered by yt_dlp and ffmpeg, this tool provides flexible options for downloading entire playlists or individual videos, with full support for format selection and audio conversion.

## Key Features

- Download videos or extract audio-only tracks in popular formats (mp3, wav, m4a, aac, flac, opus).
- Fetch and select from available video/audio formats before downloading.
- Support for downloading entire playlists with queue management.
- Convert audio with ffmpeg to your preferred codec and quality.
- Choose your download folder with an intuitive folder selector.
- Monitor download progress with a real-time progress bar.
- Manage multiple downloads efficiently using a built-in queue system.
- Responsive and clean user interface built with PyQt6.
- Runs seamlessly on major platforms with Python and ffmpeg installed.

---

## Requirements

### Software Dependencies

- **Python 3.7 or higher**  
- **PyQt6**  
- **yt_dlp**  
- **ffmpeg** (must be installed separately and accessible in your system PATH)

### Hardware Requirements

- Modern computer running Windows, macOS, or Linux.
- Internet connection.
- Sufficient disk space for downloaded files.

---

## Installation Guide

### 1. Install Python

- **Windows:** Download from [python.org](https://www.python.org/downloads/windows/) and install (make sure to add Python to PATH).  
- **macOS:** Install via Homebrew:  
  ```bash
  brew install python
Linux: Use your package manager, e.g.,


sudo apt install python3 python3-pip
2. Install ffmpeg
Windows: Download from ffmpeg.org or gyan.dev. Add bin folder to PATH.

macOS:

brew install ffmpeg
Linux:


sudo apt install ffmpeg
Test by running:


ffmpeg -version
3. Install Python packages

pip install PyQt6 yt_dlp
4. Run the application
Navigate to the folder containing the script and run:


python your_script_name.py
Replace your_script_name.py with the actual filename.

Optional: Create an executable (Windows)
Install PyInstaller:


pip install pyinstaller
Build executable:


pyinstaller --onefile your_script_name.py
The executable will be in the dist folder.

If you have questions or want to contribute, feel free to open an issue or pull request.

© 2025 Joy McStubby. All rights reserved.


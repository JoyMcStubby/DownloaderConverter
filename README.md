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
DownloaderConverter Installation Guide
--------------------------------------------------

1. Prerequisites:
   - Python 3.8 or higher installed on your system.
   - Internet connection to download required Python packages.
   - FFmpeg installed and accessible via command line (ffmpeg must be in your system PATH).

2. Install Python:
   - Download from https://www.python.org/downloads/
   - Follow the instructions for your OS.
   - Ensure "Add Python to PATH" is checked during installation.

3. Install FFmpeg:
   - Windows:
     Download from https://ffmpeg.org/download.html
     Extract and add the 'bin' folder to your system PATH.
   - macOS:
     Use Homebrew: `brew install ffmpeg`
   - Linux:
     Use your package manager, e.g.:
     `sudo apt install ffmpeg`

4. Install Python dependencies:
   Open a terminal/command prompt and run:

pip install PyQt6 yt-dlp

5. Usage Notes:
- Enter the video or playlist URL.
- Click "Fetch Formats" to retrieve available formats.
- Choose "Audio Only Mode" if you want audio extraction/conversion.
- Select a download folder if not the default folder is C:\Users\"your user name"
- Download immediately or add to queue.
- Monitor progress in the GUI.

6. Troubleshooting:
- If downloads fail, verify your internet connection.
- Ensure FFmpeg is properly installed and accessible.
- Update `yt-dlp` with `pip install -U yt-dlp` if issues occur.

Thank you for using DownloaderConverter !

© 2025 Joy McStubby. All rights reserved.


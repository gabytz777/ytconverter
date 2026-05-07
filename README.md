YouTube to MP3 Downloader - Setup Guide

Just follow these steps in order and you should be good.

Install Python
Go to https://www.python.org/downloads/

Download Python 3.12 (or newer) and run the installer.
IMPORTANT: make sure you check the box that says “Add Python to PATH” before installing.
Install the required packages
Press Windows + R, type cmd, hit Enter.
Then run:

pip install yt-dlp
pip install moviepy

Install FFmpeg
Download it from:
https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-essentials.zip

Extract the zip.
Make a folder called:

C:\ffmpeg

Then go into the extracted folder → bin
Copy these files into C:\ffmpeg:

ffmpeg.exe
ffplay.exe
ffprobe.exe

Get the script
Download/save MP3.py wherever you want.
Double-click it to run.
If it opens in a text editor instead, right-click → Open with → Python.

How to use it
Run MP3.py, then pick an option:
1 = download one song
2 = download a playlist
3 = exit

Pick where you want the files saved, paste the YouTube link, and let it do its thing.

Troubleshooting
If something breaks:

“python not found” → reinstall Python and make sure “Add to PATH” is checked
“yt-dlp not found” → run: pip install yt-dlp
“FFmpeg not found” → make sure those 3 .exe files are actually in C:\ffmpeg

If it still won’t work, open cmd and run:

python --version
pip --version

If those don’t show anything, Python didn’t install correctly.

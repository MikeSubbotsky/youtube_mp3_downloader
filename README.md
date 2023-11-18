# YouTube Video to MP3 Downloader

This script allows you to download and convert YouTube videos into MP3 format using the `yt_dlp` module.

## Requirements

- Python 3.x
- yt_dlp module

## Installation

Before running the script, you need to install the `yt_dlp` module. You can do this via pip:

```bash
pip install yt-dlp
```

## Usage

To use the script, run it in a Python environment. The script will prompt you to enter the URL of the YouTube video you wish to download and convert.

### Steps:

1. Run the script.
2. Enter the URL of the YouTube video when prompted.
3. The script will download the video, extract the audio, and save it as an MP3 file.

## Functionality

- **download_ytvid_as_mp3:** This is the main function that orchestrates the download and conversion process.

### How it works:

1. **Input URL**: The function starts by asking the user to input the URL of the YouTube video.
2. **Extract Information**: It uses `yt_dlp` to extract information about the video without downloading it.
3. **Set Filename**: Sets the filename for the MP3 file based on the video title.
4. **Define Options**: Sets the options for `yt_dlp` to download only the audio in the best available quality and convert it to MP3 format.
5. **Download and Convert**: Downloads the video and converts it to MP3 format.
6. **Complete**: Once the process is completed, it notifies the user that the download is complete and displays the filename of the MP3 file.

## Note

- This script is for personal use and should not be used to infringe on the copyrights of the video owners.
- Ensure you have the right to download and convert the YouTube videos you are interested in.

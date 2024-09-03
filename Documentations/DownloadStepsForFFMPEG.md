# FFmpeg Installation on Windows

## 1. Download FFmpeg

- Go to the [FFmpeg official website](https://ffmpeg.org/download.html).
- Under "Windows," click on the link to download a static build (e.g., from Gyan.dev).

## 2. Extract the Files

- After downloading the ZIP file, extract it to a location of your choice (e.g., `C:\ffmpeg`).

## 3. Add FFmpeg to System PATH

- **Open Environment Variables**:
  - Right-click on "This PC" or "Computer" on your desktop or in File Explorer.
  - Click "Properties."
  - Click "Advanced system settings" on the left.
  - Click the "Environment Variables" button.
- **Edit PATH Variable**:
  - In the "System variables" section, find and select the `Path` variable.
  - Click "Edit."
  - Click "New" and add the path to the `bin` directory of FFmpeg (e.g., `C:\ffmpeg\bin`).
  - Click "OK" to close all dialogs.

## 4. Verify Installation

- Open Command Prompt (`cmd`).
- Type `ffmpeg -version` and press Enter.
- You should see FFmpeg version information if the installation was successful.

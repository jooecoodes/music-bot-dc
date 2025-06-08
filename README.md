## FFmpeg Installation Guide

For audio streaming functionality, you'll need FFmpeg installed on your system. Here's how to install it:

### Windows Installation
1. Download the full build of FFmpeg from:  
   https://www.gyan.dev/ffmpeg/builds/  
   (Choose the `ffmpeg-git-full.7z` version for all features)

2. Extract the downloaded archive to a permanent location (e.g., `C:\ffmpeg`)

3. Add FFmpeg to your system PATH:
   - Open Start Menu and search for "Edit the system environment variables"
   - Click "Environment Variables"
   - Under "System variables", find and select "Path", then click "Edit"
   - Click "New" and add the path to the bin folder (e.g., `C:\ffmpeg\bin`)
   - Click OK to save all changes

4. Verify installation:
   - Open a new Command Prompt (existing ones won't see the PATH changes)
   - Run: `ffmpeg -version`
   - You should see version information if successful

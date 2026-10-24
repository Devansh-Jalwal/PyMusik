🎵 Music Player 🎧

A simple music player that lets you play music directly from the internet while also giving you the ability to download music in high quality.

The downloaded music is temporarily stored inside the project's folder and will be automatically cleared when it is no longer needed. If you want to keep a downloaded song, simply copy it from the project folder and paste it somewhere else on your computer. 😄

🛠️ Requirements (MUST KNOW!)

Before running the project, make sure you have the following installed:

Visual Studio Code (or your preferred IDE)
Python 3.11 or 3.12
⚠️ Python 3.13+ may not be supported depending on the libraries being used.
💡 Python 3.12 is recommended because it currently has great library compatibility.
An Internet Connection is also Required (To play Song From the Internet)
FFmpeg
FFmpeg is required for audio processing and downloading/converting music.
🎬 Installing FFmpeg

FFmpeg is required for the project to work correctly.

📥 Step 1 — Download FFmpeg

The Official Link is : https://www.gyan.dev/ffmpeg/builds/
Scroll Down and click on - ffmpeg-git-full.7z 

📦 Step 2 — Extract FFmpeg

After downloading FFmpeg:

Extract the downloaded .7z file.
Move the extracted FFmpeg folder somewhere permanent.

For example:

C:\ffmpeg


You should eventually have a folder containing something similar to:

C:\ffmpeg\bin\ffmpeg.exe

⚙️ Step 3 — Add FFmpeg to PATH

To make FFmpeg available to Python and other programs:

Press Windows Key and search for:
Environment Variables
Select Edit the system environment variables.
Click Environment Variables...
Under System variables, find Path.
Click Edit.
Click New.
Add the path to FFmpeg's bin folder:
C:\ffmpeg\bin

Click OK on all the open windows.
✅ Step 4 — Check if FFmpeg works (OPTIONAL)

Open a new Command Prompt or PowerShell window and run:

ffmpeg -version

No need to ever click on ffmpeg.exe

If FFmpeg is installed correctly, you should see information about your FFmpeg installation.

🎉 If you see the FFmpeg version information, you're ready to go!

🚀 How To Run

Unlike a standalone .exe program, this project should be started from your Python environment.

1. See where your Project folder is..

Drag and drop the project's folder in:

Visual Studio Code
PyCharm
Another Python-compatible IDE

2. Open the Python File

Find the  PyMusik.py file.

3. Run the Program

Run the PyMusik.py file using your IDE or Python.


📦 Dependencies & Libraries

Don't worry about manually installing every Python library!

When you start the project, the required Python libraries will AUTOMATICALLY install themselves if they aren't already installed.

This makes the initial setup much easier. 🚀

You may see a terminal or installation window appear while the required packages are being installed.(DON'T BE WORRIED)

💡 Make sure you have an active internet connection during the first launch.

🌐 Playing Music From The Internet

The player can play music directly from the internet, so you don't necessarily need to have every song stored on your computer.

Simply use the music player's available options to search for or play the music you want.

🎶 Internet + Music Player = No giant music folder required!

💾 Downloading Music

The project can also download music in high quality.

When you download a song, it may temporarily appear inside the project's folder.

⚠️ Important!

Downloaded files are intended to be temporary.

The project automatically clears temporary downloaded music when it is no longer needed.

Want to keep a song? (FOR PERSONAL PURPOSES ONLY)

-Download/play the song.
-Look inside the project's folder for the downloaded music file.
-Copy the file.
-Paste it into another folder somewhere else on your computer.
-Keep your copied version. 🎵

📌 If you want to permanently keep a downloaded song, make sure you copy it before the project clears its temporary files.

🧹 Automatic Cleanup

To prevent the project folder from becoming a giant collection of downloaded music, temporary files are automatically cleaned up.

This means you don't have to constantly go through the folder and delete old downloads yourself.

Temporary music → Used → Automatically cleaned 🧹

If you want to keep something, simply copy it somewhere else first.

💡 Tips
💻 Use Python 3.12 for the best compatibility.
🌐 Keep an internet connection available when streaming or downloading music.
🎬 Make sure FFmpeg is installed and added to PATH.
📁 Don't keep permanent music inside the project's temporary download location.
💾 Copy any downloaded music you want to keep before automatic cleanup occurs.
🛠️ If something doesn't work, check that Python, FFmpeg, and the required libraries are installed correctly.
⚠️ Important Note

Please make sure that you have the necessary rights or permission to download and keep any music you download.

Respect the copyright and terms of service of the websites and services you use with this project. ❤️

🎵 That's It!

Once Python, the required libraries, and FFmpeg are set up, you're ready to start listening.

Open the project → Run the PyMusik.py file → Pick some music → Enjoy! 🎧🔥

And remember: If you want to keep a downloaded song, copy it out of the project's folder before the automatic cleanup gets it! 😄# PyMusik

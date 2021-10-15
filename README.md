# YouTube-Transcriber
 Transcribing YT Videos

This script work by downloading YT video, converting it to Audio and then making its transcript.
There are better ways to do it, I'm sure. but this script was written to fulfill my needs.

pytube module is used to download the video from youtube.
Next, moviepy module is used for converting the video to audio.
SpeechRecognition and pydub modules are used for transcribing the audio.
The transcript is stored in the file named transcript.txt
Finally the Downloaded video and the audio file created are deleted.

To use the programm just run "YouTube Transcriber.bat" file, 
or run the command "python YTTranscriber.py" after navigating to folder.
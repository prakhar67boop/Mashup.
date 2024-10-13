# Mashup.

Project: Mashup Audio Generator
# Overview
This project is a Flask-based web application that allows users to generate a mashup of audio clips from YouTube videos of a specified singer. The mashup is created by downloading videos, converting them to audio, trimming segments, merging them, and sending the final mashup as a downloadable ZIP file via email.

# Features:
Download videos from YouTube based on a singer's name and number of videos requested.
Convert video files to audio (.mp3 format).
Trim audio to a specified duration.
Merge multiple audio files into a single file.
Compress the merged audio file into a ZIP.
Send the final ZIP file to the user's email.
# Requirements:
Python 3.x
yt-dlp for downloading YouTube videos.
moviepy for handling video to audio conversion.
pydub for audio processing.
flask for the web server.
flask_mail for sending emails.
zipfile for creating a ZIP file.

# example:
![WhatsApp Image 2024-10-14 at 00 54 15_86d3dc45](https://github.com/user-attachments/assets/62735483-dbec-4c7c-a08e-984992be76f7)

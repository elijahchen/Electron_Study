# Electron_Study

This project is a study of how electron (cross platform deployment) takes standard JavaScript logic and renders it to a standalone window.
The idea is for the main window to listen to input, having my logic receive it, return the results, and finally render the results accordingly.

#What does this app do?
For demonstrational purposes, the application allows the user to select a local video file, loads it up, and returns the length of the file.

#How to run:
- After cloning the project to a local directory
- Run "npm install", this will install all dependencies required for the project
- This application, requires the installation of FFmpeg. See: http://ffmpeg.org/download.html
- In the console/terminal window, "npm run electron"

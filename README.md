# Intruder-detection
A Python code to detect intruder and send a telegram message. 

## Credits
The initial face recognition code was written by [TechWithTim](https://github.com/techwithtim/Face-Recognition).

## My contribution
My added feature to the initial code is that it recognises whether my face (which is present in the "known_faces" directory) is present in front of the camera else the image is sent to me via telegram-cli (a commandline client for telegram). 

## Usage
Run "face_rec.py". If you want to use this script for security purpose, add this to startup applications.

## Requirements
cmake
dlib
face_recognition
numpy
opencv-python
telegram-cli
imagemagick
streamer
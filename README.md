# Invisibility Cloak (OpenCV Project) -2022
> ⚠️ Note: This is a very old Python project built with older versions of OpenCV and NumPy.
> If you run it today, you may need to adjust the HSV range values and install compatible library versions for proper results.

This project is a fun computer vision demo inspired by the “invisibility cloak” effect from the Harry Potter movies.
It works by capturing the background first, detecting a specific colour (configured in HSV range), and replacing that colored region with the background, making it appear “invisible” on camera.

Features
Captures video from your webcam.
Detects a specific colour (default: shades of black in HSV).
Replaces the detected colour with the pre-recorded background.
Displays a live “cloak” effect and saves the output to an .avi file.

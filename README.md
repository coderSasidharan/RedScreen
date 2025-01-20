# Invisibility Cloak Project

This project demonstrates a simple **Invisibility Cloak** effect using OpenCV. It utilizes a webcam to capture real-time video and applies a background replacement effect, making objects of a certain color (in this case, red) appear invisible. This effect is often referred to as the "Invisibility Cloak" effect.

## Features

- Captures real-time video from the webcam.
- Detects red objects using color detection in the HSV color space.
- Replaces the background with the captured background to create the "invisibility" effect.
- Saves the final video to an output file (`output.avi`).
- Displays the processed video in a window in real time.

## Requirements

- Python 3.x
- OpenCV
- NumPy

🪄 Invisible Cloak using OpenCV & Python

This project creates a real-time invisibility illusion by detecting a specific cloak color (red/green/blue) and replacing it with a pre-captured background image. It uses Computer Vision, Color Segmentation, Image Masking, and Background Substitution techniques using OpenCV and NumPy.

Inspired by the “invisible cloak” concept popularized in movies, this project demonstrates practical applications of HSV color detection and frame manipulation in Python.

🚀 Features

Detects cloak color using HSV thresholding

Real-time video frame processing

Removes cloak region and replaces it with background

Works in both Google Colab and local Python

Clean output with morphological filtering

Beginner-friendly, high-impact computer vision project

🧰 Technologies Used

Python 3

OpenCV

NumPy

HSV Color Space

Google Colab / Jupyter Notebook

📷 How It Works

Capture the background image (empty scene).

Capture/stream video frames from the webcam.

Convert frames from BGR → HSV color space.

Create a binary mask for cloak color (e.g., red).

Clean mask using morphological operations.

Replace cloak region with background.

Display the final invisibility effect in real time.

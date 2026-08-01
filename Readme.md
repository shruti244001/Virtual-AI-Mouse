# 🖱️ Virtual AI Mouse

A computer vision project that allows users to control the mouse cursor using hand gestures captured through a webcam.

## Overview

The project replaces the traditional mouse with hand gestures by detecting hand landmarks in real time using Computer Vision.

## Features

- Cursor movement using hand gestures
- Click detection
- Real-time webcam processing
- Smooth cursor tracking

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Project Structure

```
Virtual-AI-Mouse/

│── Final_Project.ipynb
│── README.md
│── requirements.txt
│── images/
```

## Installation

```bash
git clone https://github.com/shruti244001/Virtual-AI-Mouse.git
```

```bash
pip install -r requirements.txt
```

## How It Works

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Finger positions are mapped to screen coordinates.
4. Cursor movement and click events are generated.

## Future Improvements

- Gesture shortcuts
- Multi-hand support
- Gesture customization
- Performance optimization

## Author

Shruti Sharma

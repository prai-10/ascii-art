# ASCII Art Video Converter

Convert MP4 videos to ASCII art animation in your terminal!

## Features

- Converts any MP4 video to ASCII art in real-time
- Plays video using text characters in your terminal
- Simple and easy to use

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy

## Installation

1. Clone this repository:
```bash
git clone https://github.com/prai-10/ascii-art.git
cd ascii-art
```
2. Install required packages:
   pip install opencv-python numpy

Usage
Place your video file in the same directory and name it vid.mp4
(or modify index.py to use your video filename)

Run the script:

```bash
python index.py
```

How It Works
The script:

Reads each frame from the video

Converts pixels to brightness values

Maps brightness to ASCII characters

Displays the result in your terminal

Customization
You can modify the ASCII character set in index.py to change the visual style:

python
ASCII_CHARS = "@%#*+=-:. "  # Dark to light

Author
prai-10


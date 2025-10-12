# Python Color Detection

## About

Color Detection with Python and OpenCV. This tool allows for the identification and detection of specific colors within images using the OpenCV library in Python.

## Table of Contents

- Features
- Prerequisites
- Installation
- Usage
- How It Works
- License

## Features

- Detects specific colors and their positions in images.
- Can highlight or mask regions matching the selected color.
- Easy-to-understand code suitable for beginners as well as advanced users.

## Prerequisites

- Python 3.x
- OpenCV (cv2)
- Numpy

Install requirements with:

```
pip install opencv-python numpy
```

## Installation

Clone this repository:

```
git clone https://github.com/mahmoudabozied4/Python-color-detection.git
cd Python-color-detection
```

## Usage

1. Run the color detection script (replace `color_detection.py` with the main script name in your repo):

```
python color_detection.py --image path_to_image
```
- The script will allow you to select colors to detect and display/output the result.

2. Adjust HSV or BGR color ranges in the script to detect different colors.

## How It Works

- The script reads an image using OpenCV.
- Converts the image from BGR to HSV color space for better color segmentation.
- Defines lower and upper bounds for the color to be detected.
- Creates a mask and extracts or highlights the regions matching the selected color.
- Optional: Uses a CSV file of color names to label highlighted colors.

## License

This project is licensed under the MIT License.

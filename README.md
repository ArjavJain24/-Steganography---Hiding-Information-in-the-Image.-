# -Steganography---Hiding-Information-in-the-Image.-
Steganography is the art of hiding data within other non-secret text or data. This project focuses on hiding secret information inside images using modern steganographic techniques.

# Image Steganography Project

A Python application that hides secret messages within images using LSB (Least Significant Bit) steganography.

## Features
- Encode text messages into images
- Decode hidden messages from images
- Simple GUI interface
- Supports common image formats (PNG, JPG, BMP)

## 1.Requirements
- Python 3.6+
- Libraries listed in `requirements.txt`

## Installation
Clone this repository:
   git clone https://github.com/your-username/Image-Steganography.git

## 2. Install dependencies:
pip install -r requirements.txt

## Usage
Run the application:

    python steganography.py
  
  
  1. Select an image file
  2. Enter a secret message and click "Encode Message".
  3. Save the encoded image
  4. To decode, load an encoded image and click "Decode Message"

## How It Works
The application uses the LSB (Least Significant Bit) technique to hide information in images. Each pixel's color channels (RGB) have their least significant bit modified to store binary data from the secret message.

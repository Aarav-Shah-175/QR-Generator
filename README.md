---

# QR Code Generator in Python

This Python script generates QR codes from a provided URL or text. The script uses the `qrcode` library to create the QR code image and save it as a PNG file.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)

## Description

The QR Code Generator script allows you to convert a given link or text into a QR code. The generated QR code is saved as a PNG file. The script uses the `qrcode` library for QR code creation and image processing.

## Installation

To use the QR Code Generator script, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Aarav-Shah-175/QR-Generator.git
   ```

2. **Navigate to the Project Directory:**
   ```sh
   cd qr-code-generator
   ```

3. **Install the Required Library:**
   You need to install the `qrcode` library if it's not already installed. You can do this using pip:
   ```sh
   pip install qrcode[pil]
   ```

## Usage

1. **Edit the Script:**
   Open the `qr_code_generator.py` file and modify the `link` variable to include the URL or text you want to encode in the QR code. You can also specify the name of the output file by modifying the `file_name` argument in the `generate_qr_code` function call.

   ```python
   link = "https://www.example.com"  # Your Link Goes Here
   generate_qr_code(link, 'output.png')  # Name of the file (png)
   ```

2. **Run the Script:**
   Execute the script using Python:
   ```sh
   python qr_code_generator.py
   ```

3. **Check the Output:**
   After running the script, the QR code image will be saved as a PNG file in the same directory. The default filename is `qrcode.png`, but you can specify a different filename if desired.

# PkSprite Image Converter

PkSprite is a simple image converter application that allows you to convert images to a 4-color palette and resize them to 56x56 pixels. This is intended for use for converting later pokemon sprites to be compatible with the Gameboy Color Generation 2 sprites. This has not been tested or designed for generation 1 sprites. 
If it does not work for gen 1, please let me know the technical requirements of gen 1 sprites and I will try and add support and functionality. The application is built using Python and Tkinter, and it can be packaged into a standalone executable for Windows.

## Features

- Select an image file (supports .jpg, .jpeg, .png, .bmp)
- Convert the image to a 4-color palette using K-Means clustering
- Resize the image to 56x56 pixels
- Toggle between the original converted image and the resized image
- Save the converted image as a .png file

## Requirements

- Python 3.x
- Required Python packages:
  - Pillow
  - numpy
  - scikit-learn
  - tkinter

## Installation
Download the executable and run it.

## Usage
Launch the application by running the executable or the Python script.
Click the "Select Image" button to choose an image file.
Click the "Convert Image" button to convert the image to a 4-color palette and resize it to 56x56 pixels.
Use the "Show Resized Image" button to toggle between the original converted image and the resized image.
Click the "Save Image" button to save the converted image as a .png file.

## License
This project is licensed under the GNU General Public License. See the LICENSE file for details.

## Acknowledgements
* Pillow
* Numpy
* scikit-learn
* Tkinter
* My friend, DwunD016

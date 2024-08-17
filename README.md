Document Scanner

This Python project is a document scanner application designed to automatically detect and crop the content of documents from images. It uses OpenCV for image processing and perspective transformation, Tkinter for user interface dialogs, and Tesseract for Optical Character Recognition (OCR).
Features

    Image Loading: Allows users to select an image file from their computer.
    Edge Detection: Applies edge detection to identify document contours.
    Perspective Transformation: Corrects the perspective to obtain a top-down view of the document.
    Image Processing: Converts the scanned document to grayscale and applies thresholding for better readability.
    Save and OCR: Saves the processed document and extracts text using OCR.

Requirements

    Python 3.x
    OpenCV
    NumPy
    imutils
    pytesseract
    Tkinter

How to Use

    Run the script.
    Select an image file from your file explorer.
    The application will process the image, detect the document, and display the result.
    Save the scanned document and view extracted text if needed.

Installation

Install the required packages using pip:

bash

pip install opencv-python numpy imutils pytesseract

Ensure Tesseract OCR is installed and properly configured on your system.

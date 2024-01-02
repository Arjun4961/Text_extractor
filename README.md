# Text_extractor
Using 
OCR-PDF-Converter

This Flask application allows users to upload a PDF file, convert it into images, perform OCR (Optical Character Recognition) on each image, and display the extracted text. The application uses Tesseract for OCR and supports PDF conversion using pdf2image.

Prerequisites
Before running the application, make sure you have the following installed:

Python 3.x
Flask
pytesseract
OpenCV (cv2)
pdf2image
Tesseract OCR


#Installation
Install dependencies:

bash
Copy code
pip install Flask pytesseract opencv-python pdf2image
Install Tesseract OCR: Follow the instructions here to install Tesseract OCR on your system. Make sure to set the Tesseract executable path correctly in the pytesseract.tesseract_cmd variable in the code.

Install Poppler: Download and install Poppler from here. Set the Poppler binary path in the pdf_to_images function if needed.

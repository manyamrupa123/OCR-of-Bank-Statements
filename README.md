# OCR-of-Bank-Statements

#Project Overview
This project automates the extraction and visualization of data from financial documents stored on Cloudinary. Using Optical Character Recognition (OCR) powered by Tesseract, it processes images to extract key fields, cleans the data, and generates visualizations such as bar and pie charts. A Gradio interface provides an intuitive way for users to interact with the system, choose document types, and view outputs.

#Features
Milestone 1: Fetching and Image Quality
Folder Retrieval: Fetch available folders from Cloudinary for document organization.
Image Fetching: Download specified numbers of images from Cloudinary folders.
Cloud Integration: Supports upload/download of financial document images.

Milestone 2: OCR Processing
OCR Engine: Extracts text from images using Tesseract OCR.
Document Types: Processes multiple formats like Payslips, Profit and Loss Statements, and Cheques.
Error Handling: Implements robust error handling for image processing and API interactions.

Milestone 3: Data Extraction and Visualization
Field Mapping: Extracts key fields based on predefined configurations for each document type.
Visualization: Generates Bar and Pie charts using Matplotlib for insights into extracted data.
Data Export: Outputs data as JSON and CSV for further analysis.

Milestone 4: Gradio-based Web Application
Interactive UI: Built with Gradio to provide an intuitive interface for folder selection, data visualization, and downloads.
Customizable Options: Allows users to select document types, chart styles, and the number of images to process.
Technologies Used

#Backend:
Python libraries: cloudinary, pytesseract, PIL, matplotlib, pandas, requests
OCR: Tesseract

#Frontend:
Gradio: Provides a responsive user interface for interaction with the system.

#Cloud Storage:
Cloudinary: Stores and retrieves financial document images.

#Data Visualization:
Matplotlib: Creates bar and pie charts for summarized insights.

#How to Run
Frontend:
Start the frontend server using:
npm run start
Backend:
Run the following Python scripts:
python Milestone.py (Default host: 127.0.0.1:5001)










# AI/Python Intern Assignment: PDF Content Extraction

## Overview
This project extracts all text and images from an educational PDF file and organizes the output in structured JSON format. The goal is to support AI-based question generation.

## Features
- Extracts page-wise text from PDF
- Saves all embedded images as PNG files
- Outputs a structured `output.json` file with page number, text, and image paths

## Files
- `extract_pdf.py`: Script to extract content from a PDF
- `output.json`: Structured content with extracted text and image references
- `images.zip`: ZIP file containing all extracted images

## How to Run
```bash
pip install PyMuPDF
python extract_pdf.py
```

## Author
This project was completed as part of an internship assignment.

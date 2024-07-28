# Automated Invoice Processing System

This project is a web application designed to automate the extraction and processing of data from multiple PDF invoices. Utilizing OCR, PyPDF2, and Google Generative AI, this system captures and organizes invoice details into structured formats, making it ideal for large-scale enterprises to manage their invoices efficiently.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)

## Features

- Upload multiple PDF invoices at once.
- Extract text from both text-based and image-based PDF invoices.
- Utilize Google Generative AI to accurately capture key invoice details.
- Organize extracted data into a structured format (Excel).
- Edit and preview extracted data before finalizing.
- Download the processed data in Excel format.

## Requirements

- Python 3.10
- Flask
- PyPDF2
- pytesseract
- Pillow (PIL)
- fitz (PyMuPDF)
- google.generativeai
- pandas

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/automated-invoice-processing-system.git
   cd automated-invoice-processing-system

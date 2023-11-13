# MediExtract

MediExtract is a FastAPI-based backend project designed for streamlined medical data extraction from prescription and patient detail PDFs. Leveraging pdf2image and pytesseract, it ensures accurate text extraction, while regex-based parsers decode key medical information.

## Features

- **FastAPI Backend:** Enables seamless PDF uploads for medical data extraction.
- **Text Extraction:** Utilizes pdf2image and pytesseract for precise content extraction.
- **Regex Parsers:** Specialized regex parsers for extracting patient names, medicines, and more.
- **Testing and Reliability:** Incorporates pytest for automated testing, ensuring robust functionality.

## Tech Stack

- FastAPI
- pdf2image
- pytesseract
- poppler-utils
- pytest

## Usage

1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the FastAPI server: `uvicorn main:app --reload`
4. Access the API at `http://127.0.0.1:8000/docs` and use the `/extract_from_doc` endpoint for PDF extraction.

## Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

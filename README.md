# ResumeFit Analyzer

**ResumeFit Analyzer** is a smart and flexible tool that evaluates resume quality based on key content sections such as Education, Experience, Skills, and Contact Information. It supports PDF, DOCX, and image files (PNG, JPG, JPEG), and provides a match score to help users improve their resumes for job applications.

## Features

- Accepts PDF, DOCX, and image-based resumes
- Uses OCR to extract text from image files
- Extracts text using PyPDF2, python-docx, and pytesseract
- Analyzes resume content for essential sections
- Outputs a match score (0–100%) and actionable feedback
- Detects phone numbers as valid contact info

## Supported File Types

- `.pdf`
- `.docx`
- `.png`, `.jpg`, `.jpeg`

## Technologies Used

- Python
- PyPDF2
- python-docx
- pytesseract (OCR)
- Pillow (image processing)
- Regular expressions for phone number detection

## How It Works

1. Upload a resume file
2. The tool extracts text from the document
3. It checks for the presence of:
   - Education
   - Experience
   - Skills
   - Contact (or phone number)
4. A match score is calculated and feedback is displayed

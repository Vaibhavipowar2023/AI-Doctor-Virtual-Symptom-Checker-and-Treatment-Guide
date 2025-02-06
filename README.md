# AI Doctor: Virtual Symptom Checker and Treatment Guide

## Overview
AI Doctor is a virtual healthcare assistant powered by AI, designed to help users check their symptoms, receive possible diagnoses, and get medication suggestions based on their input. It also allows users to upload medical reports (PDFs, images, or CSV files) for further analysis. This project uses Generative AI, natural language processing, and OCR technologies to offer an interactive and user-friendly healthcare experience.

## Features
- **Symptom Checker**: Users can describe their symptoms and get a list of possible medical conditions, along with follow-up questions for better understanding.
- **Medication Suggestions**: Based on the diagnosis, the system suggests relevant medications and treatments.
- **Medical Report Analysis**: Users can upload medical reports in PDF, image, or CSV formats for diagnosis and recommendations.
- **Interactive Conversations**: The system engages users in a friendly, empathetic tone, adding emojis and highlighting key points for better understanding.

## Technologies Used
- **Google Generative AI (Gemini-1.5-Pro)**: For generating responses and providing diagnosis and treatment suggestions.
- **PyPDF2**: To extract text from PDF documents.
- **Tesseract OCR**: To extract text from images using optical character recognition.
- **Pandas**: For extracting and displaying data from CSV files.
- **Python**: The main programming language for the project.

## Installation

### Requirements
- Python 3.x
- Google Cloud API key for Generative AI (Gemini-1.5-Pro)
- Tesseract installed for OCR

### Steps to Install
1. Clone the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/AI-Doctor.git
   cd AI-Doctor

## How to Use
1. **Symptom Checker:**
    * Start the program and describe your symptoms (e.g., fever, cough, sore throat).
    * The AI will suggest possible medical conditions and follow-up questions.

2. **Medication Suggestions:**
    * Based on the diagnosis, the AI will recommend medications and lifestyle changes.

3. **Upload Medical Report:**
    * Upload a PDF, image, or CSV file of your medical report.**
    * The system will extract data and provide an analysis of the report.

4. **Ask Follow-up Questions:**
    * You can ask the AI follow-up questions, and it will provide more detailed information or recommendations.

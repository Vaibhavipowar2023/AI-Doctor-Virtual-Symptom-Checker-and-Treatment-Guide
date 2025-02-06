# **Healthcare System Using Prompt Engineering **

## Overview 
Healthcare System using prompt engineering assistant powered by AI, designed to help users check their symptoms, receive possible diagnoses, and get medication suggestions based on their input. It also allows users to upload medical reports (PDFs, images, or CSVs) for further analysis.

## Features
- **Symptom Checker**: Provides possible diagnoses based on user-provided symptoms.
- **Medication Suggestions**: Suggests medications and treatments based on the diagnosis.
- **Report Analysis**: Extracts and analyzes text from uploaded medical reports (PDF, image, or CSV).
- **Interactive Follow-Up**: Engages users with follow-up questions to gather more information about their symptoms.

## Technologies Used
- **Google Generative AI (Gemini-1.5-Pro)**: For generating responses and providing diagnosis and treatment suggestions.
- **PyPDF2**: To extract text from PDF documents.
- **Tesseract OCR**: To extract text from images using optical character recognition.
- **Pandas**: For extracting and displaying data from CSV files.
- **Python**: The main programming language for the project.

## Installation
To run this project, you need to install the following libraries:
```bash
!pip install google-generativeai
!pip install PyPDF2
!pip install pytesseract
```

Additionally, you need to install Tesseract OCR software:
```bash
!apt-get install tesseract-ocr
```

## Usage
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Vaibhavipowar2023/AI-Doctor-Virtual-Symptom-Checker-and-Treatment-Guide.git
    cd AI-Doctor-Virtual-Symptom-Checker-and-Treatment-Guide
    ```

2. **Open the Jupyter Notebook**:
    Open `Healthcare_system (1).ipynb` in Jupyter Notebook or Google Colab.

3. **Run the Cells**:
    Execute each cell in the notebook to install dependencies and run the code.

4. **Interacting with AI Doctor**:
    - Describe your symptoms when prompted.
    - Upload any medical reports for further analysis.
    - Follow the interactive session to get possible diagnoses and treatment suggestions.

## Code Structure
- **Installation Cells**: Install necessary libraries and software.
- **Import Cells**: Import required libraries.
- **Function Definitions**: Define functions for symptom checking, medication prescription, report analysis, and follow-up questions.
- **Main Function**: `run_healthcare_system()` drives the workflow, interacting with the user and providing responses based on AI model outputs.

## Functions
### Symptom Checker
```python
def symptom_checker(symptoms_input):
    # Interacts with the user to suggest possible diagnoses
```

### Medication Prescription
```python
def prescribe_medication(diagnosis):
    # Suggests medications and treatments based on diagnosis
```

### Report Analysis
#### PDF Text Extraction
```python
def extract_pdf_text(file_path):
    # Extracts text from PDF files
```
#### Image Text Extraction
```python
def extract_image_text(file_path):
    # Extracts text from image files using OCR
```
#### CSV Data Extraction
```python
def extract_csv_data(file_path):
    # Extracts data from CSV files using pandas
```

### Follow-Up Questions
```python
def ask_follow_up():
    # Engages the user with follow-up questions
```

### File Upload Simulation
```python
def upload_report():
    # Simulates the file upload process
```

## Running the System
To start the healthcare system, run the `run_healthcare_system()` function:
```python
if __name__ == "__main__":
    run_healthcare_system()
```

## Notes
- Ensure that Tesseract OCR is properly installed and configured for text extraction from images.
- This project uses Google's generative AI model (genai) for generating responses. Make sure to configure the API key correctly.

## Disclaimer
This project is for educational purposes only and does not provide medical advice. Always consult a healthcare professional for medical concerns.


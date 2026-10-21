AI Document Comparison Assistant

Overview

AI Document Comparison Assistant is a Python-based application that compares two PDF documents and identifies important differences using Generative AI.

It uses the Gemini API to analyze document content and provides clear comparison results, helping users save time and avoid manual document review.

Features

- Upload and compare two PDF documents.
- Extract text using PyPDF.
- Identify important differences using the Gemini API.
- Display results through an interactive Streamlit interface.
- Handle common errors and invalid inputs.

Technologies Used

- Python
- Generative AI
- Gemini API
- Streamlit
- PyPDF
- Prompt Engineering

How It Works

1. Upload two PDF documents.
2. Extract text from both files.
3. Analyze the content using the Gemini API.
4. Display the comparison results.

Workflow: PDF Upload → Text Extraction → AI Analysis → Comparison Results

Installation

pip install streamlit pypdf google-genai python-dotenv

Configure your Gemini API key securely in a ".env" file, then run:

streamlit run app.py

Future Enhancements

- Support additional document formats.
- Highlight added, removed, and modified content.
- Generate downloadable comparison reports.

Learning Outcomes

Gained practical experience in Python development, Generative AI, prompt engineering, API integration, PDF processing, and building AI-powered applications.

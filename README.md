# Mentorness Projects

## Overview

This repository contains two projects:

* Chatbot Project
* Resume Parser Project

Each project serves a different purpose and functionatility.

## Chatbot Project

This Chatbot is designed to provide conversational interactions with users' PDFs. It is integrated with a PDF text extraction feature, allowing for users to ask questions related to the uploaded PDF Documents. It leverages Google Generative AI models for conversational responses and FAISS(Facebook AI Similarity Search) for efficient text similarity search. The PDF files can range from school work PDF to lengthy PDFs that are too wordy to go through. The Chatbot will concisely extract needed information and give it as output.

## Resume Parser Project

The Resume Parser project focuses on extracting contact information such as candidate names, phone numbers, and email addresses from resumes in various formats (PDF, text, Word). It uses regular expressions and document processing libraries to accurately extract and store the extracted data in a structured format (CSV).

## Technologies used

### Chatbot Project

* Streamlit
* PyPDF2
* LangChain(langchain, langchain_google_genai)
* FAISS(vectorstores)
* Google Generative AI(google.generativeai)

### Resume Parser Project

* PDFPlumber (for PDF extraction)
* python-docx (for Word document extraction)
* Regular Expressions (Regex)
* CSV (Comma-Separated Values) for data storage

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the respective project directories('chatbot_development', 'resume_parser').
3. Follow the instructions in the project-specific README files to set up and run each project.

## License

This project is licensed under the MIT license.

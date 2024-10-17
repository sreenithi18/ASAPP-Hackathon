# ASAPP-Hackathon
QA bot for Research Papers Given a knowledge base containing 100s of research papers, create a QA bot which when asked a question can reply with the right answer and cite the relevant research papers.
# Researcher Hub 
This project is a web app that allows users to upload PDF documents, extract the text, summarize it, and interact with a chatbot to get answers about the document's content. The system uses cutting-edge models for text summarization and question-answering to help users get quick insights from their PDFs.
# Key Features
1) Upload PDF: Users can upload PDF documents for text extraction.
2) Text Extraction: The app extracts and cleans the text content from the uploaded PDFs.
3) Text Summarization: Generates concise summaries of the extracted text.
4) Q&A Chatbot: Users can ask questions related to the PDF content and receive answers based on the document.
# Technologies Used
## Streamlit: 
   Used to build the web interface.
## Hugging Face Transformers: 
   Provides the models for summarization and question-answering tasks.
## PyPDF2: 
   Handles the text extraction from PDF files.
## Python: 
  The core programming language for the project.
  
# Set up
# Prerequisites
Ensure that Python 3.7 or above is installed. To check your Python version, 
run: python --version

# Installation Steps

## Clone the repository:
     git clone <repository_url>
     cd <repository_directory>

## Create and activate a virtual environment:
     python -m venv venv
     venv\Scripts\activate

## Install dependencies:
    pip install -r requirements.txt

## Running the Application
    streamlit run app.py

# Interact with the app:

1) Upload a PDF: Use the "Upload a PDF file" button to upload your document.

2) Summarize: After extraction, click the "Summarize" button to generate a concise summary of the document.

3) Ask Questions: Type a question in the text field to ask the Q&A chatbot, which will return answers based on the document's content.

# Future Enhancements
       Model Optimization for CPU

       Multi-document Summarization and Q&A

       Multi-language Support

       Collaboration and Sharing

       Voice-Enabled Q&A

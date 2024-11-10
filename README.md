# ai_medicalreport
# AI-Powered Medical Report Analysis System
## 🏥 Overview
This advanced medical report analysis system leverages artificial intelligence to process and extract insights from medical PDF documents. Using a multi-agent approach with Groq's AI capabilities, the system can preprocess text, extract medical entities, suggest possible diagnoses that can be made based on the tests the patient has taken. Kindly note it makes suggestions on all possible diagnoses that can be made based on the medical test taken, and generate critical alerts.

## 🚀 Key Features
- PDF Report Processing: Seamless extraction of text from medical PDF documents
- Multi-Agent AI Analysis:
  - Text Preprocessing
  - Medical Entity Extraction
  - Diagnosis Suggestion
  - Critical Alert Generation
- Groq AI Integration: Utilizes state-of-the-art language models for intelligent analysis
- Gradio Web Interface: User-friendly interface for easy report uploads and analysis
- Comprehensive Medical Insights:
  - Medication Detection
  - Test Result Analysis
  - Potential Diagnosis Suggestions

## 👥 Team Members
- Akanksha Kulkarni - PES1UG23AM032
- Monika PM - PES1UG24CS275

## 🛠 Installation & Setup


Clone this repository

git clone https://github.com/meh01234/ai_medicalreport.git

cd ai_medicalreport

# Create and activate a virtual environment

Windows:
python -m venv venv
venv\Scripts\activate

Linux/Mac:
python -m venv venv
source venv/bin/activate

# Install required packages

pip install pymupdf

pip install gradio

pip install groq --upgrade

# Configuration

Open main.ipynb in a Jupyter notebook environment
Replace YOUR_API_KEY with your actual Groq API key:

GROQ_API_KEY = "your-actual-groq-api-key"
Usage

Start Jupyter Notebook:


Open main.ipynb in Jupyter Notebook
Run all cells in the notebook. The last cell will launch a Gradio interface.
Upload a PDF medical report through the Gradio interface to get the analysis.
   


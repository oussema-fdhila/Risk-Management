# PMBOK Risk Management – NLP Analysis

NLP-based analysis of PMBOK 6 to extract concepts, keywords, and relationships for risk management knowledge discovery.

## 📌 Overview

This project applies Natural Language Processing (NLP) techniques to the PMBOK 6 document in order to transform unstructured project management knowledge into structured information.

The pipeline extracts:

- Concepts
- Keywords
- Semantic relationships
- Subject–Verb–Object (SVO) triplets
- Knowledge graph information

## 🔄 Project Pipeline

PMBOK 6 PDF  
↓  
Text Extraction  
↓  
Text Cleaning  
↓  
Chapter Detection  
↓  
Concept Extraction  
↓  
Keyword Extraction  
↓  
Relationship Extraction  
↓  
Structured Data  
↓  
Power BI Visualization

## 🛠️ Technologies

- Python
- Google Colab
- Pandas
- NumPy
- PyMuPDF
- PyPDF2
- KeyBERT
- Sentence Transformers
- Transformers
- BERTScore
- spaCy
- NLTK
- Textacy
- RDFLib
- FAISS
- Scikit-learn

## 📁 Project Structure

```text
Risk-Management/
│
├── Notebooks/
│   └── Risk_Management.ipynb
│
├── src/
│   └── risk_management.py
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore


# 📄 PDF Summarizer (Python)

This project is a simple Python script that extracts text from a PDF file and creates a short summary of the content.

---

## 📌 About the Code
- Uses **PyPDF2** to read and extract text from PDF files  
- Splits text into sentences using **NLTK (Natural Language Toolkit)**  
- Converts sentences into numerical form with **TF-IDF Vectorizer**  
- Measures sentence importance using **cosine similarity**  
- Selects the most relevant sentences to generate a summary  

---

## ⚡ How It Works
1. Reads text from all pages of a PDF  
2. Breaks the text into sentences  
3. Ranks sentences using TF-IDF + cosine similarity  
4. Picks top sentences to form the summary  

---

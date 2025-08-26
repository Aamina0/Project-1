# Project-1
My Bootcamp project

# GIKI Prospectus Q&A Chatbot using Retrieval-Augmented Generation (RAG)

## ðŸ“Œ Project Overview
This project implements a **Retrieval-Augmented Generation (RAG)**-based chatbot for answering queries related to the **GIKI Prospectus**, fee structure, and academic rules.  
It allows users to upload documents and ask natural language questions, providing accurate answers retrieved from the uploaded content.

## âœ¨ Features
- Upload up to **5 documents** (PDF/DOCX/TXT)
- Extract and chunk document content for efficient retrieval
- Generate embeddings using HuggingFace models
- Store and retrieve data using **FAISS** vector database
- Generate context-aware answers using **Flan-T5**
- Web-based chatbot interface built with **Streamlit**
- Optional **English/Urdu language toggle**

## ðŸ› ï¸ Technologies Used
- **Programming Language:** Python
- **Libraries:** PyMuPDF, python-docx, FAISS, HuggingFace Transformers, Streamlit
- **Models:** Flan-T5, GPT alternatives
- **Deployment:** Google Colab / Local Execution

## ðŸš€ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/GIKI-RAG-Chatbot.git
cd GIKI-RAG-Chatbot
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

### 4. Usage
- Upload up to 5 GIKI-related documents.
- Ask any natural language question.
- Get context-aware, accurate answers.

## ðŸ“Š Project Structure
```
GIKI-RAG-Chatbot/
â”‚â”€â”€ data/                 # Sample GIKI documents
â”‚â”€â”€ models/               # Pre-trained embedding models
â”‚â”€â”€ app.py                # Streamlit chatbot app
â”‚â”€â”€ utils/                # Helper scripts
â”‚â”€â”€ requirements.txt      # Dependencies
â”‚â”€â”€ README.md             # Project documentation
â”‚â”€â”€ notebooks/            # Jupyter notebooks
```

## ðŸ‘©â€ðŸ’» Author
**Aamina Shabbir**  
Built with â¤ï¸ for **GIKI** students.

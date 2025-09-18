# AI Chatbot with OCR, Multilingual Support, and FAISS Search

This project provides an AI chatbot capable of answering questions from uploaded documents in multiple formats:

- PDFs (both text-based and scanned)
- Word documents (`.docx`)
- PowerPoint presentations (`.pptx`)
- Images (`.png`, `.jpg`, etc.)
- Multilingual text (English, Hindi, Marathi, etc.)

It combines **OCR (Tesseract)**, **translation (Google Translate)**, **embeddings (SentenceTransformers)**, and **FAISS vector search** with a **Flask web interface**.

---

## ✨ Features

- 📄 Extracts text from PDFs, DOCX, PPTX, and images.  
- 🔍 OCR support for scanned PDFs and images.  
- 🌐 Multilingual input support (English, Hindi, Marathi, etc.).  
- ⚡ Semantic similarity search with FAISS.  
- 💬 Chatbot powered by SentenceTransformers embeddings and Hugging Face Transformers.  
- 🌍 Access Flask app publicly via `pyngrok`.  

---

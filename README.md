# 🚀 Insurance Automation Suite

### **AI-Powered Document Processing & Quote Comparison**

This repository contains two end-to-end AI systems built to automate and streamline workflows in the insurance domain:

---

## 🧠 **1. Document Classification Agent**

An intelligent pipeline that processes multi-page insurance documents and automatically:

* Splits PDFs into logical sections using **Sentence-BERT embeddings**
* Classifies each segment (Invoice, Claim Form, Inspection Report, Receipt)
* Extracts key fields with **regex-based parsers**
* Validates cross-document consistency (policy number, invoice totals, assessed damage)
* Produces a clean, structured **JSON summary**
* Includes a full **Streamlit UI** for PDF upload and results preview

**Technologies:**
Python, PyMuPDF, Tesseract OCR, Sentence-BERT, scikit-learn, Streamlit

---

## 🤖 **2. Quote Comparison Chatbot**

An AI assistant that compares multiple insurance quotes and recommends the best plan based on:

* Premium
* Deductible
* Coinsurance
* Out-of-Pocket Maximum
* Coverage score
* Family size, region, income profile

It uses:

* **OCR + PDF parsing** to extract quote information
* A configurable **scoring engine** for cost/coverage ranking
* A **local RAG module** (TF-IDF + cosine similarity) for insurance term explanations
* A **GPT-powered explanation engine** for natural-language recommendations
* A **Streamlit UI** for uploading PDFs, manual entry, comparison, and asking questions

**Technologies:**
Python, Streamlit, Tesseract OCR, pdfplumber, TF-IDF RAG, OpenAI GPT-4o

---

## 📂 **What This Repo Provides**

* Fully modularized codebases for both projects
* OCR, extraction, classification, scoring, and validation logic
* Clean and interactive Streamlit frontends
* Ready-to-run examples
* Requirements and environment setup

---

## 🏁 **Goal of the Suite**

To automate manual insurance operations using AI/ML — decreasing processing time, improving accuracy, and enabling smarter decision support through RAG and LLMs.

---


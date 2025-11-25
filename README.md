# 🧾 ClaimGen – LLM-Powered Insurance Template Auto-Filler

ClaimGen is an automated **General Loss Report (GLR) generation pipeline** that extracts text from **photo report PDFs**, interprets **insurance templates (.docx)** using an LLM, and generates a **filled insurance report automatically** — all through a simple **Streamlit web app**.

This project was built as part of a backend engineering assignment and demonstrates:
- Document parsing & text extraction
- LLM-based field mapping using OpenRouter APIs (DeepSeek/Qwen/etc.)
- Automated DOCX template filling
- Streamlit UI for easy uploads & downloads

---

## 🚀 Features

### 🔍 1. PDF Text Extraction
Extracts text from multiple **photo report PDF files** using `pypdf`.

### 🧠 2. LLM-Based Field Mapping  
Uses **OpenRouter LLMs** (DeepSeek/Qwen) to:
- Read template structure  
- Understand placeholders  
- Identify key-value pairs from report text  
- Return JSON mapping of fields → values  

### 📝 3. Auto Template Filling  
Automatically fills the `.docx` insurance template using extracted values.

### 🌐 4. Streamlit App UI  
User-friendly interface:
- Upload template (.docx)
- Upload PDF reports
- Preview extracted mappings
- Download filled report

---





# 🧾 AI-Powered Invoice & Expense Analyzer

## 📄 Overview
A smart tool that lets you upload invoices (PDF/JPG/PNG), automatically extracts key data using OCR + OpenAI (e.g., Vendor Name, Amount, GST, Category), stores it in a SQL database, and visualizes it with Power BI or Streamlit.

---

## 🚀 Features
- OCR text extraction using `pytesseract`
- NLP + OpenAI GPT-4 for field detection & categorization
- Expense data stored in `SQLite` (can be switched to PostgreSQL)
- Dashboard using `Streamlit` or `Power BI`
- Upload PDFs or images in UI

---

## 🧰 Tech Stack
| Layer       | Tools Used                |
|-------------|---------------------------|
| Language    | Python 3.10+              |
| OCR         | pytesseract               |
| AI/NLP      | OpenAI API (GPT-4)        |
| Database    | SQLite (or PostgreSQL)    |
| Dashboard   | Streamlit / Power BI      |
| Storage     | Local (or AWS S3 optional)|

---

## 🖥️ Installation & Setup

### 1. Clone Repo
```bash
git clone https://github.com/yourusername/ai-invoice-analyzer.git
cd ai-invoice-analyzer
```

### 2. Install Python Packages
```bash
pip install -r requirements.txt
```
> `requirements.txt` contains:
```
pytesseract
Pillow
openai
streamlit
sqlite3
pdf2image
```

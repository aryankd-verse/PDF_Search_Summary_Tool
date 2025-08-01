# 📄 PDF Search & Summary Tool

## 🧠 Project Explanation

The **PDF Search & Summary Tool** allows users to **search for specific keywords** across multiple PDF documents and automatically generate a **summary of the matched content**.

This tool is especially helpful for:
- Researchers who need to extract specific topics across many PDFs
- Students who want to study relevant parts of long study materials
- Professionals reviewing reports or papers for key terms

---

## 🎯 1. Objective

This project allows users to search for keywords across multiple PDF files and generate a summary of matching content.  
It helps researchers and students quickly extract relevant information from large collections of documents.

---

## 🛠 2. Tech Stack Used

- **Python 3.10**
- **Jupyter Notebook**
- **Libraries:**
  - `PyPDF2` – PDF reading
  - `nltk` – Sentence tokenization
  - `pandas` – Data storage and tabular output
  - `re` – Regex for keyword matching
  - `os` – File handling

---

## 📤 3. Output Includes

- Matching **sentences** with:
  - Keyword found
  - Page number
  - File name
- **Keyword frequency count** across all PDFs
- **Optional output files**:
  - Excel/Text summary
  - Highlighted PDF (if implemented)

---

## ⚠️ 4. Challenges Faced

- `PyPDF2` sometimes misses text from scanned/image-based PDFs
- Line breaks and irregular formatting affect clean text extraction
- Needed to normalize and clean sentences for accurate matching
- Performance issues with very large PDFs or many files

---

## 📚 5. Learnings

- Learned how to use `PyPDF2` for reading and parsing PDFs
- Understood how to use `nltk.sent_tokenize()` for sentence-level text splitting
- Applied list comprehensions, filters, and regex for matching logic
- Strengthened skills in managing and analyzing tabular data using `pandas`

---

## 🚀 Future Improvements

- Add OCR support using `pdfplumber` or `pytesseract` for scanned PDFs
- Implement PDF highlighting using `fitz` / `PyMuPDF`
- Add GUI for user-friendly keyword entry
- Export results as an automated email report






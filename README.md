# Google Drive Document Compiler

A personal tool to batch-convert and merge Google Drive files into a single Master PDF. Optimized for organization-locked (TAMU) materials and NotebookLM ingestion.

## 🛠️ Personal Notes & Quirks
* **Authentication:** Must run `auth.authenticate_user()` to access university-restricted files.
* **File IDs:** The script extracts IDs from full URLs or shortened `rebrand.ly` links.
* **Microsoft Word (.docx) Handling:** * **The Problem:** The Drive API cannot "Export" raw Word files as PDFs.
    * **The Fix:** Open the Word file in Drive -> **File > Save as Google Doc**. Use the new Doc link.

## 📖 Quick Start
1.  Open `Master_Note_Compiler.ipynb` in [Google Colab](https://colab.research.google.com/).
2.  Run the script and follow the OAuth prompt.
3.  Enter the output filename and paste URLs (one per line).
4.  **Output:** Saved to `Colab Notebooks/Compiled_Documents` in Google Drive.

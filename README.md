# Google Drive Document Compiler

This tool automates the process of converting and merging multiple Google Drive files (Docs, Slides, and PDFs) into a single, high-quality Master PDF. It was specifically designed to handle organization-locked documents (like university course materials) for use in tools like NotebookLM.

## 🚀 Features
* **URL Expansion:** Automatically handles shortened links.
* **Bulk Conversion:** Converts Google Docs and Slides to PDF on the fly.
* **Smart Merging:** Combines everything into one file with a custom title.
* **Auth-Ready:** Uses Google OAuth to access files restricted to your organization.

## 🛠️ Important: Handling Word (.docx) Files
If you are trying to compile Microsoft Word files stored in Drive, please follow these steps before running the script:
1. Open the `.docx` file in Google Drive.
2. Go to **File > Save as Google Doc**.
3. Use the new Google Doc link in this compiler. 
*Note: The script is optimized for native Google Editor formats.*

## 📖 How to Use
1. Open the [Master_Note_Compiler.ipynb](Master_Note_Compiler.ipynb) in **Google Colab**.
2. Run the cells and authenticate with your Google Account.
3. Enter your desired file title.
4. Paste your list of URLs (one per line).
5. Find your finished PDF in your Drive under `Colab Notebooks/Compiled_Documents`.

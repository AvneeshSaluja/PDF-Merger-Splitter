# PDF-Merger-Splitter
This is a lightweight desktop application for managing PDF files using Python. Built with Tkinter for GUI and PyPDF2 for PDF operations, the application allows users to merge multiple PDF files, split a PDF into individual pages, and extract specific pages from a given PDF.
Key Features:
-------------
- Select and merge multiple PDF files into one document.
- Split one PDF file into multiple single-page files.
- Extract specific page numbers and save them into a new file.
- Simple GUI to allow easy file selection and execution.

Technologies Used:
------------------
- Python 3.12
- Tkinter (GUI)
- PyPDF2 (PDF library)

File Structure:
---------------
- main.py        → Entry point to the application.
- ui.py          → Contains GUI layout and control flow.
- pdf_utils.py   → All PDF operations (merge, split, extract).

How to Run:
-----------
1. Install Python 3.12 and PyPDF2: `pip install PyPDF2`.
2. Open the project in any IDE.
3. Run `main.py` and the GUI will open.
4. Use buttons to perform operations on selected PDF files.


# PDF Comparison Tool

This tool compares two PDF files based on various criteria such as similarity ratio, page number, size, and readability.

## Features

- **Fuzzy Logic Comparison**: Uses fuzzy logic to calculate the similarity ratio between PDFs.
- **Page Number Comparison**: Compares the number of pages in each PDF.
- **Size Comparison**: Compares the file size of each PDF.
- **Text Readability**: Checks if the PDF is readable and extracts text for comparison.

## Requirements

- Python 3.x
- PyPDF2
- FuzzyWuzzy
- Requests
- BeautifulSoup

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the script `pdf_comparison.py`.
4. Provide the file paths for the two PDFs to compare.
5. The tool will output a CSV file containing the comparison results.

## Example

```python
python pdf_compair.py

# Python Libraries for Extracting Tables and Text from PDFs

A curated list of Python libraries for extracting tables and text from PDF files. These tools range from simple text extractors to advanced table extraction utilities capable of handling complex layouts.

---

## Table of Contents

- [Camelot](#camelot)
- [Tabula](#tabula)
- [pdfplumber](#pdfplumber)
- [Pdftables](#pdftables)
- [LLMWhisperer](#llmwhisperer)
- [PyMuPDF (fitz)](#pymupdf-fitz)
- [PyPDF2](#pypdf2)
- [Tabula-py](#tabula-py)
- [pdfminer.six](#pdfminer-six)
- [PyPDF4](#pypdf4)
- [pdfquery](#pdfquery)
- [pdfrw](#pdfrw)
- [pdf2image](#pdf2image)
- [Tesseract-OCR](#tesseract-ocr)
- [layoutparser](#layoutparser)
- [Additional Libraries](#additional-libraries)
  - [pdfminer](#pdfminer)
  - [PyPDF](#pypdf)
  - [OCRmyPDF](#ocrmypdf)
  - [pdf2text](#pdf2text)
  - [PDFBox (via PyPDFBox)](#pdfbox-via-pypdfbox)
  - [Slate](#slate)
  - [pdflib](#pdflib)
  - [ExtractTable](#extracttable)
  - [ABBYY FineReader SDK](#abbyy-finereader-sdk)
  - [camelot-py\[cv\]](#camelot-pycv)

---

## Camelot

Camelot is a user-friendly Python library for extracting tables from PDFs. It works well with simple table structures.

- **Table Parsing**: Efficiently extracts tables from PDF files, including those with complex layouts.
- **Export Options**: Supports exporting tables into multiple formats like CSV, JSON, Excel, HTML.
- **Visual Debugging**: Provides tools for visualizing and adjusting the table extraction process.
- **Easy Integration**: Seamlessly integrates with other Python libraries.

📌 [Camelot on GitHub](https://github.com/camelot-dev/camelot)

---

## Tabula

Tabula is popular for handling multi-page PDFs. It uses Java with a Python wrapper.

- **Java-Based Backend**: Uses a Java library for PDF processing.
- **Multiple Page Support**: Extracts tables across all pages in a PDF.
- **Export Options**: Offers exporting capabilities in formats such as CSV, JSON, and TSV.
- **Ease of Use**: Provides a simple API via `tabula-py`.

📌 [Tabula-py on GitHub](https://github.com/chezou/tabula-py)

---

## pdfplumber

Known for its precision and flexibility with complex tables.

- **High Precision**: Capable of extracting intricate table structures with great accuracy.
- **Detailed Control**: Offers granular control over the extraction process.
- **Versatility**: Supports extraction of both text and tables.
- **Output Options**: Allows saving extracted data in formats like CSV and JSON.

📌 [pdfplumber on GitHub](https://github.com/jsvine/pdfplumber)

---

## Pdftables

Pdftables is a commercial API-based service with high accuracy.

- **High Accuracy**: Provides accurate extraction of tables.
- **Multiple Output Formats**: Converts tables to formats including CSV, Excel, and XML.
- **Ease of Use**: Offers a straightforward API.
- **API-Based Service**: Requires an API key.

📌 [Pdftables Website](https://pdftables.com/)

---

## LLMWhisperer

Converts PDFs to text while preserving table layouts.

📌 [LLMWhisperer on GitHub](https://github.com/Zipstack/llmwhisperer-handwritten-pdf-extraction)

---

## PyMuPDF (fitz)

PyMuPDF is a high-performance rendering library.

- **Fast Rendering**: Provides rapid rendering of PDF pages.
- **Text Extraction**: Extracts text, images, and other objects.
- **Annotation Support**: Can read and write annotations.

📌 [PyMuPDF on GitHub](https://github.com/pymupdf/PyMuPDF)

---

## PyPDF2

A pure Python library capable of splitting, merging, cropping, and transforming PDF files.

- **PDF Manipulation**: Merge and split PDFs.
- **Text Extraction**: Extract text and metadata.
- **Encryption/Decryption**: Handles encrypted PDFs.

📌 [PyPDF2 on GitHub](https://github.com/py-pdf/PyPDF2)

---

## Tabula-py

A simple Python wrapper of tabula-java, which can read tables in a PDF.

- **Simple Interface**: Easy to use and integrate.
- **Multiple Formats**: Exports to DataFrame, CSV, JSON, TSV.
- **Batch Processing**: Handles multiple PDFs.

📌 [Tabula-py on GitHub](https://github.com/chezou/tabula-py)

---

## pdfminer.six

An open-source Python library for extracting text and information from PDFs.

- **Text Extraction**: High-level API for text extraction.
- **Layout Analysis**: Detailed layout information.
- **Unicode Support**: Handles various character encodings.

📌 [pdfminer.six on GitHub](https://github.com/pdfminer/pdfminer.six)

---

## PyPDF4

A fork of PyPDF2 with additional features and fixes.

- **PDF Manipulation**: Similar capabilities to PyPDF2.
- **Improved Functionality**: Additional methods and bug fixes.

📌 [PyPDF4 on PyPI](https://pypi.org/project/PyPDF4/)

---

## pdfquery

A lightweight Python library for extracting data from PDF files using CSS-like selectors.

- **XPath and CSS Selectors**: Query PDF elements easily.
- **Layout Preservation**: Maintains the structure of the PDF.

📌 [pdfquery on GitHub](https://github.com/jcushman/pdfquery)

---

## pdfrw

A pure Python PDF reader and writer.

- **PDF Manipulation**: Read and write PDF files.
- **Form Support**: Modify form fields.

📌 [pdfrw on GitHub](https://github.com/pmaupin/pdfrw)

---

## pdf2image

A Python module that wraps pdftoppm and pdftocairo to convert PDF to a PIL Image object.

- **Image Conversion**: Convert PDF pages to images.
- **High Quality**: Preserves the quality of the PDF.

📌 [pdf2image on GitHub](https://github.com/Belval/pdf2image)

---

## Tesseract-OCR

An OCR engine for extracting text from images, including scanned PDFs.

- **Optical Character Recognition**: Extracts text from images.
- **Language Support**: Supports multiple languages.

📌 [Tesseract-OCR on GitHub](https://github.com/tesseract-ocr/tesseract)

---

## layoutparser

A toolkit for document image analysis.

- **Layout Detection**: Detects layout elements in documents.
- **Deep Learning Models**: Utilizes advanced models for detection.

📌 [layoutparser on GitHub](https://github.com/Layout-Parser/layout-parser)

---

## Additional Libraries

### pdfminer

- **Text Extraction**: High-accuracy text extraction from PDFs.
- **Layout Analysis**: Detailed layout, fonts, and structure information.
- **Customization**: Programmable interface for custom parsing.

📌 [pdfminer on GitHub](https://github.com/euske/pdfminer)

---

### PyPDF

- **PDF Manipulation**: Improved fork of PyPDF2.
- **Text Extraction**: Extract text and metadata.
- **Merging & Splitting**: Merge multiple PDFs and split pages.

📌 [PyPDF on PyPI](https://pypi.org/project/PyPDF/)

---

### OCRmyPDF

- **OCR Integration**: Adds OCR text layer to scanned PDFs.
- **Retention of Original File**: Keeps original images.
- **Automation**: Suitable for batch processing.

📌 [OCRmyPDF on GitHub](https://github.com/ocrmypdf/OCRmyPDF)

---

### pdf2text

- **Simple Text Extraction**: Converts PDFs to text files.
- **Command-Line Tool**: Easy scripting and batch processing.
- **Lightweight**: Minimal dependencies.

📌 [pdf2text on PyPI](https://pypi.org/project/pdf2text/)

---

### PDFBox (via PyPDFBox)

- **Java-Based Processing**: Uses Apache PDFBox through Python wrapper.
- **Text and Metadata Extraction**: Access detailed document info.
- **Form Handling**: Extract and fill form data.

📌 [PyPDFBox on PyPI](https://pypi.org/project/PyPDFBox/)

---

### Slate

- **Built on PDFMiner**: Simplifies PDFMiner's interface.
- **Text Extraction**: Easily extract text.
- **User-Friendly**: Straightforward for quick tasks.

📌 [Slate on PyPI](https://pypi.org/project/slate/)

---

### pdflib

- **Commercial Library**: Professional tools for PDF manipulation.
- **Advanced Features**: Text and table extraction, PDF generation.
- **Support and Documentation**: Extensive resources.

📌 [PDFlib Website](https://www.pdflib.com/)

---

### ExtractTable

- **API Service**: Extract tables from PDFs and images.
- **High Accuracy**: Advanced algorithms for table detection.
- **Easy Integration**: REST API.

📌 [ExtractTable Website](https://extracttable.com/)

---

### ABBYY FineReader SDK

- **Commercial OCR**: High-quality OCR for text and tables.
- **SDK Access**: Python SDK for integration.
- **Complex Layouts**: Handles complex documents.

📌 [ABBYY FineReader SDK](https://www.abbyy.com/en-us/finereader/sdk/)

---

### camelot-py\[cv\]

- **OpenCV Support**: Uses OpenCV for table detection.
- **Enhanced Detection**: Better with images and scanned PDFs.
- **Customization**: Parameters for tweaking extraction.

📌 [Camelot with OpenCV Support](https://camelot-py.readthedocs.io/en/master/user/install-deps.html)

---

## Contributing

If you know of any other useful libraries or tools for extracting tables and text from PDFs, feel free to contribute to this list by opening a pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Acknowledgments

- Thanks to all the developers and contributors of these libraries.
- Inspired by community efforts to make PDF data extraction accessible.

---


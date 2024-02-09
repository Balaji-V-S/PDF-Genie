# AI Knowledge Genie: Leveraging FAISS Algorithm for Intelligent Document Understanding

## Overview

The PDF-Genie project aims to develop an intelligent system capable of understanding and processing the content within uploaded PDF documents. Leveraging the FAISS (Facebook AI Similarity Search) algorithm, this system can efficiently index and search through vast amounts of textual data, providing users with valuable insights and knowledge extraction.

## Features

- **Document Upload**: Users can upload PDF documents containing valuable information.
- **Text Extraction**: The system extracts text content from uploaded PDF documents for further analysis.
- **Document Indexing**: Utilizing the FAISS algorithm, the system indexes the textual data to enable fast and accurate search capabilities.
- **Knowledge Retrieval**: Users can search for specific information within the uploaded documents, with the system retrieving relevant sections or documents.
- **Intelligent Insights**: The AI Knowledge Genie provides intelligent insights and summaries based on the content of the uploaded documents.

## Requirements

- Python 3.x
- FAISS-cpu
- Streamlit
- PyPDF2
- google-generativeai
- python-dotenv
- langchain_google_genai
- chromadb

## Installation

1. Clone this repository:

```bash
git clone https://github.com/Balaji-V-S/PDF-Genie
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Run the script
```bash
streamlit run main.py
```

4. Access the web interface by opening your web browser and navigating to the provided URL/IP

# Contribution
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to submit a pull request.

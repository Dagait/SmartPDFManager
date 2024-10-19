# SmartPDFManager

**Smart PDF Manager** is a Python-based tool designed to automate the organization of PDF files. It uses natural language processing (NLP) to analyze the contents of PDF files and classify them into categories based on extracted entities such as organizations, people, and more. The project uses **SpaCy** for entity recognition, allowing for smart PDF categorization based on both English and German documents.

## Features

- **Organize PDFs**: Classify and move PDFs into directories based on the most common entity (e.g., Organization, Person) found in the document.
- **Supports English and German**: Detects entities in both English and German, improving classification for multilingual documents.
- **Customizable**: Add or adjust categories and keywords to tailor the classification logic to your needs.


1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/smart-pdf-manager.git
   cd smart-pdf-manager
   ```

2. Install the required dependencies:
   ```bash
    pip install -r requirements.txt
    ```
   
3. Install the SpaCy models for English and German:
   ```bash
   python -m spacy download en_core_web_sm
   python -m spacy download de_core_news_sm
   ```
   
## Usage

1. Place the PDF files you want to organize a directory of your choice (e.g., `pdfs/`).
2. Choose a directory "input" where the PDFs are located and a directory "output" where the PDFs will be moved to.
# PDF Number Analyzer Project

## Description

This Jupyter Notebook project analyzes PDF files to find the maximum number on each page and identifies the page with the overall maximum number. It's designed to help users efficiently extract and analyze numerical data from a collection of PDF documents stored in the `pdfs` folder.

## Prerequisites

- Python 3.8 or newer
- pip (Python package installer)

## Installation

Clone this repository to your local machine or download the ZIP file and extract it.

```bash
git clone https://github.com/alecjcn/conductor.git
cd your-project-directory
```

````

## Setting Up a Virtual Environment

Create a virtual environment to manage dependencies separately from your global Python setup:

### For macOS and Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### For Windows:

```cmd
python -m venv .venv
.venv\Scripts\activate
```

## Installing Dependencies

Install the necessary Python packages specified in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Running the Project

1. Launch Jupyter Notebook:

```bash
jupyter notebook
```

2. Open the `notebook.ipynb` file within the Jupyter Notebook interface.
3. Modify the `pdf_path` variable in the notebook to point to the desired PDF in the `pdfs` folder.
4. Run all cells in the notebook to see the output, which includes the maximum numbers found and their respective pages.

## Project Structure

- **notebook.ipynb**: The main Jupyter Notebook containing all the analysis code.
- **pdfs/**: Directory containing the PDF files to be analyzed.
- **requirements.txt**: Lists all Python libraries that the project depends on.
````

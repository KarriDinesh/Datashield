# Sensitive Data Shield

A Flask-based web application for detecting and masking sensitive personal information in documents.

## Features

- **Email Detection & Masking** - Identifies and masks email addresses
- **Phone Number Detection** - Detects and masks phone numbers
- **Credit Card Detection** - Identifies credit card patterns
- **SSN Detection** - Detects Social Security Numbers
- **Multi-format Support**:
  - PDF files
  - Word documents (.docx)
  - Excel spreadsheets (.xlsx)
  - Plain text

## Installation

1. Clone the repository:
```bash
git clone https://github.com/KarriDinesh/Datashield.git
```

2. Create a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Flask application:
```bash
python3 app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

3. Upload a document to analyze and mask sensitive data

## Project Structure

```
masking/
├── app.py              # Main Flask application
├── templates/
│   └── index.html      # Web interface
├── requirements.txt    # Python dependencies
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Dependencies

- **Flask** - Web framework
- **pypdf** - PDF processing
- **python-docx** - Word document support
- **openpyxl** - Excel file support

## License

MIT License

## Author

Dinesh Karri

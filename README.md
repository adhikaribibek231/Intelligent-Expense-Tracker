# Intelligent Expense Tracker

A Django-based app for scanning receipts with OCR, extracting expenses, and categorizing them.

## Features
- Upload receipts
- OCR via Tesseract
- Regex + ML for parsing and categorization
- Dashboard with charts

## Setup
```bash
git clone https://github.com/adhikaribibek231/Intelligent-Expense-Tracker.git
cd expense-tracker
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

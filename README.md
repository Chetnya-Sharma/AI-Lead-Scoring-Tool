# README.md
# ------------------
# AI Lead Scoring Tool for Caprae Capital

## Overview
This tool was created as part of the Caprae Capital internship challenge. It demonstrates an AI-first approach to prioritize B2B leads based on relevance and value.

## Features
- Upload CSVs with basic company info: Company, Role, Location, Industry, Revenue
- Automatically engineer features using NLP and regex patterns
- Train a LightGBM model (if labeled data is present)
- Score and categorize leads as High, Medium, or Low impact
- Download scored results instantly

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Input Format
CSV file should include the following columns:
- Company
- Role
- Location
- Industry
- Revenue
- (Optional) Label (binary: 1=high quality lead, 0=not)

## Output
CSV with scores and lead quality categories for immediate business use.

---

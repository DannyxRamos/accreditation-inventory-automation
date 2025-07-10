# Accreditation Inventory Automation (Ad Hoc Request)

In preparation for Bergen Community College’s 2025 accreditation site visit, I was asked — on less than 24 hours’ notice — to produce an inventory of over 10 years’ worth of institutional documents stored in hundreds of folders.

Rather than manually count and record files, I used Python to automate the process and generate an accurate inventory in minutes — saving hours of manual labor and delivering documentation quickly to support the accreditation response.

## Tools Used
- Python: `os`, `pandas`, and `pathlib` for recursive folder inventory and file summary

## What the code does
- Recursively scans folders by year and category
- Counts files, captures folder structure, and generates summary tables
- Outputs CSV or Excel for easy review and submission

##  View the code
 [`accreditation_inventory_demo.py`](./accreditation_inventory_demo.py)

> *Note: This version uses a synthetic folder structure for demonstration purposes.*

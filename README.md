# SDE-2
# Data Ingestion Tool

## Enhancement: Bidirectional ClickHouse & Flat File Integration

This submission includes the complete implementation for the bidirectional data ingestion tool. Due to size limitations, the full modified project is included as a ZIP file.

### How to Access

Please download and unzip the file `data_ingestion_tool.zip` located in the root of this repository.

### What's Included

- Backend implementation (app.py)
- Frontend UI (index.html, script.js, styles.css)
- Configuration files (requirements.txt)
- Sample test datasets (test_data/)
- Unit tests (tests/)
- prompts.txt listing AI tools usage prompts
- Screenshots of successful executions
- Evidence of build and test execution (test_output.log)

### Usage Examples

1. ClickHouse → Flat File:
```python
# Configure via UI:
# Direction: ClickHouse → Flat File
# Host: localhost | Port: 9000
# Database: test | Table: products
# Output: output.csv

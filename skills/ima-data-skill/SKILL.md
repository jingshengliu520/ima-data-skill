---
name: ima-data-skill
description: A Python-based agent skill for processing and analyzing 'ima' data.
---

# `ima-data-skill`

This skill provides the ability to process, analyze, and transform "ima" data using Python.

## Usage Instructions

When asked to process ima data, you should use the provided Python scripts in the `scripts/` directory.

### Processing Data
1. Ensure the Python environment has the necessary dependencies installed (`pip install -r requirements.txt`).
2. Run the main processing script using the `run_command` tool:
   ```bash
   python3 skills/ima-data-skill/scripts/main.py --input <path_to_input_data> --output <path_to_output_file>
   ```

### Notes
- The default `main.py` script accepts JSON or CSV data. 
- You can extend the python script to accommodate any specific data processing rules for "ima" data.
- If you need to make API calls to fetch data, you can use the `requests` library which is included in `requirements.txt`.

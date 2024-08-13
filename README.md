# FEMA Disaster Declarations Data Extraction

This Python script extracts data from FEMA's Disaster Declarations API and organizes it into a pandas DataFrame. It fetches disaster declaration details such as the state, incident type, and the start and end dates of the incidents.

## Project Overview

The script performs the following steps:
1. **Fetch Data**: Sends an HTTP GET request to the FEMA Disaster Declarations API.
2. **Parse Data**: Parses the JSON response to extract the fields of interest.
3. **Organize Data**: Stores the extracted data into separate lists.
4. **Create DataFrame**: Combines these lists into a pandas DataFrame for further analysis.

## Prerequisites

- **Python 3.x**
- **Libraries**: `requests`, `pandas`

You can install the required libraries using pip:

```bash
pip install requests pandas


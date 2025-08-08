# Window-Log-Analysis-

This project focuses on analyzing sample Windows 2000 system event logs to extract key system activity patterns, detect anomalies, and understand event trends.

## Data Source

The log file used is:

- **File**: `Windows_2k.log`
- **Format**: Plain text with typical Windows event entries (e.g., Event ID, timestamps, system/user actions)

## Objectives
- Parse and structure raw Windows event log entries
- Identify common system activities:
  - Logon/logoff events
  - Application and system errors
  - Administrative changes
- Detect anomalies:
  - Multiple failed login attempts
  - Unauthorized access
  - Unexpected service or process activity
 
 - ## 🛠 Tools & Technologies

- **Python** – Data parsing and analysis
- **Pandas / Polars** – Structured data handling
- **Regex** – Extract event details from unstructured logs
- **Splunk** – For visual dashboards and advanced queries

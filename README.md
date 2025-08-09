 🖥 Windows Log Analysis with Splunk

## Overview
This project demonstrates the ingestion, analysis, and visualization of Windows event logs using **Splunk**.  
The logs were generated via a custom PowerShell script to simulate real system activity and security events, then parsed in Splunk to identify trends, anomalies, and potential threats.  

---

## Data Source
- **Generated Log File:** `Windows_2k.log` (based on Windows Event Log structure)  
- **Format:** Plain text with typical Windows event entries (Event ID, timestamps, system/user actions)  
- **Generation Method:** PowerShell script that simulates logon/logoff events, process starts, file changes, and failed login attempts.  

---

## Objectives
1. **Parse and structure raw Windows event log entries**
2. **Identify common system activities**
   - Logon/logoff events
   - Application and system errors
   - Administrative changes
3. **Detect anomalies**
   - Multiple failed login attempts
   - Unauthorized access
   - Unexpected service or process activity

---

## Tools & Technologies
- **Splunk** – Ingestion, SPL queries, dashboards, and alerts  
- **PowerShell** – Log generation script (`generate_logs.ps1`)  
- **Python** – Optional data parsing and pre-processing  
- **Pandas** – Structured data handling (optional)  
- **Regex** – Extracting event details from unstructured logs  

---

## Workflow
1. **Generate Logs**  
   - Run the PowerShell script in `/scripts` to produce Windows-style logs.
   - Output stored in `/logs` as `.log` or `.csv`.

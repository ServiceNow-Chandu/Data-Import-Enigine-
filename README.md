# Data Import Engine – ServiceNow

This project demonstrates how to design a controlled enterprise data ingestion pipeline in ServiceNow using Import Sets and Transform Maps.

The solution simulates a real-world scenario where employee directory data is imported from an external source and synchronized with a ServiceNow table.

---

# Project Objective

To implement a structured data import process that:

- Loads external CSV data into ServiceNow
- Prevents duplicate records
- Normalizes incoming data
- Logs import errors
- Supports scheduled synchronization

---

# Technologies Used

- Import Sets
- Transform Maps
- Coalesce Logic
- Transform Scripts
- Scheduled Data Imports
- Scoped Application Development
- GitHub Source Control

---

# Key Features

• Import employee directory data via CSV  
• Transform raw import data into structured records  
• Prevent duplicate employees using coalesce logic  
• Normalize department and status values  
• Log missing or invalid data  
• Automatically run imports using scheduled jobs  

---

# Data Pipeline Overview

External CSV → Import Set Table → Transform Map → Employee Directory Table

---

# Demo Scenario

1. Upload employee CSV file
2. Run Transform Map
3. Employee records are created
4. Run import again
5. Existing records update instead of creating duplicates
6. Scheduled import runs automatically

---

# Interview Talking Point

"I designed a controlled data ingestion pipeline using ServiceNow Import Sets and Transform Maps, implementing coalesce logic, normalization scripts, and scheduled imports to safely synchronize external employee data with the platform."

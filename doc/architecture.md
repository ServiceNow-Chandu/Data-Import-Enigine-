# Architecture

The architecture consists of three main layers.

1. Source Data Layer
External CSV file containing employee records.

2. Import Set Layer
Temporary staging table that receives raw data from the import file.

3. Target Table Layer
Employee Directory table where normalized records are stored.

Flow:

CSV File
   ↓
Import Set Table (u_employee_import)
   ↓
Transform Map
   ↓
Employee Directory Table (u_employee_directory)

This approach ensures that raw data is processed before entering production tables.

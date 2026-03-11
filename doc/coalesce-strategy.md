# Coalesce Strategy

Coalesce is used to prevent duplicate records during data imports.

Field Used:
u_employee_id

Logic:

If employee_id exists:
Update existing record

If employee_id does not exist:
Create a new record

This ensures employee records remain unique and synchronized.

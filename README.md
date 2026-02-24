# output_util_by_service_CMS
CMS Medicare outpatient utilization analysis by service type using Python and SQL.

## CMS Medicare Outpatient Utilization Analysis (2023)

This project analyzes Medicare outpatient utilization patterns using CMS Program Statistics
(MDCR OUTPATIENT 5). The analysis focuses on utilization by service type, highlighting
differences in volume across outpatient services such as emergency room, laboratory,
clinic, and pharmacy care.

Data preparation required normalization of multi-row CMS Excel headers, removal of
aggregate and non-data rows, and conversion of utilization fields to numeric formats.
Utilization metrics were computed in Python (pandas) and independently validated using
SQL (SQLite) to ensure consistency and transparency.

**Tools:** Python, pandas, matplotlib, SQLite  
**Data Source:** CMS Program Statistics – Medicare Outpatient Facilities

Here is your **final GitHub README (clean, professional, no fluff, no exaggeration, copy-paste ready)**:

---

# HR Analytics Dashboard | Power BI, Power Query, DAX

## Overview

This project analyzes employee attendance data from AtliQ Technologies (April–June 2022) using Power BI. It converts raw Excel attendance files into an interactive dashboard to track workforce presence, work-from-home behavior, and sick leave trends.

---

## Business Problem

Attendance data was stored in separate monthly Excel files, which made it difficult to:

* Combine data across months
* Track attendance trends consistently
* Analyze work-from-home usage
* Monitor sick leave patterns
* Identify workforce behavior trends

A centralized reporting system was required to improve visibility and reduce manual reporting effort.

---

## Dataset

Daily employee attendance data for April, May, and June 2022.

**Attendance Codes:**

* P → Present
* WFH → Work From Home
* SL → Sick Leave
* WO → Weekly Off
* HO → Holiday

---

## Data Preparation (Power Query)

* Combined multiple monthly Excel sheets into one dataset
* Removed duplicate headers and cleaned inconsistent formatting
* Standardized attendance codes
* Transformed date columns using unpivoting
* Created a single fact table for analysis
* Built a refreshable query structure for future updates

---

## Data Model & DAX

A single fact table was used to calculate KPIs.

**Key Measures:**

* Total Working Days (excluding WO and HO)
* Present Days (P + WFH)
* Work From Home Count
* Sick Leave Count
* Presence %
* WFH %
* SL %

**DAX Functions Used:**

* CALCULATE()
* DIVIDE()
* VAR

---

## KPIs

| KPI                | Value  |
| ------------------ | ------ |
| Presence %         | 91.83% |
| WFH %              | 10.00% |
| SL %               | 1.10%  |
| Total Working Days | 4369   |

---

## Dashboard Features

* Attendance trend analysis over time
* Work-from-home distribution tracking
* Sick leave monitoring
* Employee-level attendance view
* Weekday-based attendance patterns
* Monthly filtering and segmentation

---

## Key Insights

* Attendance remained stable across the three-month period
* Work-from-home activity was higher on Mondays and Fridays
* Sick leave levels remained consistently low
* Clear hybrid working pattern observed in employee behavior

---

## Tools Used

* Power BI
* Power Query
* DAX
* Microsoft Excel

---

## Outcome

Built a centralized Power BI dashboard that replaces manual Excel-based attendance tracking and provides structured visibility into workforce presence, work-from-home usage, and sick leave trends.

---

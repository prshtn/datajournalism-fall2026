# DC Crime Data Analysis

## 1. NEWSWORTHINESS / RESEARCH QUESTION

**QUESTION:** How have reported violent and property crimes in Washington, D.C. changed from 2022-2026?

This question is potentially newsworthy for American University's audience because AU students live, study, work and travel throughout D.C. Crime trends can affect students' perceptions of safety and their understanding of the city surrounding campus. Looking at multiple years also provides more context than reporting on individual incidents.

## 2. METHODOLOGY / PIVOT TABLE

### DATA SOURCE
- Dataset: D.C. crime records
- Total records analyzed: **2,156**
- Relevant fields:
  - `YEAR`
  - `offensegroup`

### PROCESS
1. Imported the D.C. crime dataset into a spreadsheet.
2. Identified `YEAR` and `offensegroup` as the variables needed for the analysis.
3. Created a pivot table.
4. Set `YEAR` as the **row variable**.
5. Set `offensegroup` as the **column variable**.
6. Used **COUNT** to calculate the number of crime records in each category.
7. Added row and column totals.
8. Compared yearly totals for property and violent crime.

### PIVOT TABLE OUTPUT

| YEAR | PROPERTY | VIOLENT | TOTAL |
|---|---:|---:|---:|
| 2022 | 109 | 14 | 123 |
| 2023 | 535 | 32 | 567 |
| 2024 | 562 | 16 | 578 |
| 2025 | 543 | 17 | 560 |
| 2026 | 312 | 16 | 328 |
| **TOTAL** | **2,061** | **95** | **2,156** |

## 3. ANSWER

The dataset shows that **property crime was substantially more common than violent crime** during the period analyzed.

The highest yearly total was **2024, with 578 reported incidents**. Property crime accounted for **2,061 of the 2,156 records**, while violent crime accounted for **95**.

Property crime increased sharply from **109 incidents in 2022 to 535 in 2023**, remained high in 2024 and 2025, and totaled 312 records in 2026.

Violent crime remained comparatively low, ranging from **14 to 32 incidents per year** in the dataset.

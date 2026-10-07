# DC Crime Data Analysis

## https://docs.google.com/spreadsheets/d/1VJiYis5rmeS3fGkPb7CNPeMW9isP0UkK/edit?usp=sharing&ouid=105133396608207245639&rtpof=true&sd=true

## 1. NEWSWORTHINESS / RESEARCH QUESTION

**QUESTION:** How have reported violent crimes in Washington, D.C. changed from years 2022-2026?

This question is newsworthy for AU's audience because AU students live, study, work and travel throughout the D.C. area. Crime trends can impact a students perception of safety and understanding of the city right outside of campus. Looking at an array of years also provides  context as opposed to reporting on an individual incident.

## 2. METHODOLOGY / PIVOT TABLE

### DATA SOURCE
- Dataset: D.C. crime records
- Total records analyzed: **2,156**
- Relevant fields:
  - `YEAR`
  - `offensegroup`

### PROCESS
1. Imported the Washington D.C. crime dataset into a spreadsheet.
2. Identified `YEAR` and `offensegroup` as the variables needed for the analysis.
3. Created a pivot table.
4. Set `YEAR` as the **row variable**.
5. Set `offensegroup` as the **column variable**.
6. Used **COUNT** to calculate the number of crime records in both categores.
7. Added totals for the row and columns.
8. Counted yearly totals for property and violent crime by year and compared them.

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

**Property crime was far more common than violent crime** during the period analyzed, according to my dataset. This is likely due to the relatively low population density and high concentration of residential and commercial infrastructure around Northwest D.C.

The highest year for crime in total was **2024, with 578 reported incidents**. Property crime accounted for **2,061 of the 2,156 records**, while violent crime accounted for just **95**.

Property crime increased from **109 incidents in 2022 to 535 in 2023**, remained high in 2024 and 2025, and totaled 312 records in 2026.

Violent crime stayed low compared to property crime, going from from **14 to 32 incidents per year** in the dataset.

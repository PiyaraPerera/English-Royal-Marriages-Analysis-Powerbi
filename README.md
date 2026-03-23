# English Royal Marriages Analysis — Power BI Dashboard

A personal Power BI project analysing 1,100 years of English royal 
marriage patterns from 851 to 1947, driven by a passion for royal 
history and data storytelling.

## Research Question
How have age gaps between English monarchs and their consorts 
changed across 1,100 years of royal marriages?

## Overview
This project involved sourcing, cleaning, enriching and merging two 
datasets to analyse patterns in English royal marriages from the 
House of Wessex to the House of Windsor. The analysis explores age 
gaps, consort ages and dynasty comparisons across 56 royal marriages.

## Data Sources
- **Marriages dataset** — Kaggle: English Monarchs and Marriages 
  (851–1947)
- **Monarchs dataset** — manually compiled from Wikipedia, 
  containing house/dynasty, reign length and biographical data

## Data Preparation
- Cleaned raw dataset in Power Query — removed null values, fixed 
  encoding issues, removed incomplete records
- Created and merged a second dataset containing dynasty, reign 
  length and gender data for each monarch
- Engineered an `age_gap` column (king_age minus consort_age) 
  for trend analysis
- Final merged dataset: 56 records across 5 columns

## Dashboard Visuals
- **Line chart** — Average age gap trend over time (851–1947)
- **Scatter plot** — Monarch age vs consort age at marriage
- **Bar chart** — Average age gap by royal house/dynasty
- **Grouped bar chart** — Average monarch vs consort age by dynasty
- **Cards** — Biggest age gap (40 years), youngest consort (age 3), 
  average age gap (8.38 years), average reign length

## Key Insights
- Age gaps were significantly larger in medieval marriages than 
  modern ones
- The Plantagenet dynasty had the largest average age gap
- The youngest consort in the dataset was just 3 years old 
  (Margaret of France, married Henry the Young King in 1160)
- Average age gap has declined consistently over the centuries 
  reflecting changing social norms
- Negative age gaps exist — some consorts were older than their 
  monarchs (Eleanor of Aquitaine was 11 years older than Henry II)

## Technologies Used
- Power BI, Power Query, DAX

## Files
- `English_Royal_Marriages_Dashboard.pbix` — Power BI dashboard
- `english_monarchs_marriages_df.csv` — Original marriages dataset
- `monarchs.csv` — Manually compiled monarchs dataset
- `dashboard_export.pdf` — Static PDF export of dashboard

<img width="1306" height="701" alt="image" src="https://github.com/user-attachments/assets/0be8b6a1-a478-4c7d-93fb-b02c3f8b4dc8" />

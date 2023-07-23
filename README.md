# GLOBAL SHARK ATTACKS
![](SHARK_ATTACK_IMAGE.jfif)
## Introduction
As part of my internship programme, I was handed a raw Global Shark attacks dataset to wrangle, clean, model, analyse and generate valuable insights that could help in understanding the pattern of attacks and preventing future occurences. Power BI was used for this project and the following Power BI DAX concepts were applied

- Calculated columns
- calculated measures
---
## Problem Statement
It seemed like Shark attacks have intensified in the last couple of years. But:

- What is the trend like?
- What triggers these attacks?
- Which places are hotbeds for Shark Attacks?
- How can it be prevented and/or avoided going forward?
---
## Data Sourcing
This dataset is a single table of an excel csv file, and it contains 5763 rows and 16 columns. It came in a zipped format, I extracted the file and proceeded to import into my Power BI desktop for cleaning and visualization.

---
## Data transformation/Cleaning
The data was effectively cleaned on the Power Query Editor of Power BI. This was done to ensure data quality before subsequent visualization. Actions include:

- Removing duplicates
- Checked for all empty columns (null) and effectively renamed to "Unspecified".
- The dates in ther date column were in different date format; I converted them to the same format
- Duplicated the date column and renamed it "year". I further extracted the year only using the format "YYYY" in the column tools
- converted all columns to the correct data types (text for text, date for date, whole numbers for whole numbers etc.)
---

## Data Modelling
Modelling was not necessary as the dataset was a single table 5763 rows and 16 columns. However, below is the model view with the calculated columns and measures

![](SHARK_ATTACK_MODEL_VIEW.png)

## Visualization
Below is the report which is a single page dashboard
![](GLOBAL_SHARK_ATTACKS_DASHBOARD.jpg)

You can interact with the report [here](https://app.powerbi.com/groups/me/reports/8b5da2e6-3835-4111-b046-00b6d4b891b1/ReportSection671bb8b7525cb9b706ac?experience=power-bi)

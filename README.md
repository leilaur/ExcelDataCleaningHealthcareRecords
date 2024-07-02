
# Excel Data Cleaning Project - Healthcare records

### Dataset Source : https://www.kaggle.com/datasets/prasad22/healthcare-dataset

## Overview

The initial dataset contained numerous duplicates and required standardization to enhance clarity and usability.

The objective is to clean the data, create pivot tables and an interactive dashboard for visualization.

### Key Takeaways from this Project

- Identifying and removing duplicates across various columns.
- Standardizing data columns.
- Creating pivot tables.
- Creating a dashboard for visual presentation.


### Steps followed 

- Step 1 : Create working sheet, pivot table and dashboard sheet.
- Step 2 : Remove duplicates.
- Step 3 : Insert filter and check columns for empty or missing data.
- Step 4 : Standardize name column.
- Step 5 : Define an age bracket for easier grouping:

        •  0-9 years: Children
        •  10-19 years: Adolescents
        •  20-29 years: Young Adults
        •  30-49 years: Adults
        •  50-64 years: Middle-aged Adults
        •  65+ years: Seniors

- Step 6 : Extract year from admission date column.
- Step 7 : Create pivot tables:
        
        • Patient profile – shows patient demographics (age bracket, gender) throughout the years
        • Patient admissions trend – shows trend of patient admissions from May 2019 to May 2024 by month
        • Patient count by medical condition – shows medical condition by patients admitted
        • Admission type x test results – shows results of tests based on admission type
	
- Step 8 : Create dashboard - add slicers to easily navigate through age bracket, gender and year.

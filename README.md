# Mobile-Phones-Dashboard-Analyzing-Smartphone-Models-and-Specifications

## Problem Statement
- The Mobile Phones Dashboard is designed to help smartphone manufacturers and retailers understand their product offerings and market positioning. By analyzing the number of models per company, front and back camera resolutions, and key metrics like average price, RAM, and weight, the dashboard provides insights into product diversity and specifications. This enables stakeholders to identify trends, such as which companies dominate specific camera resolution segments or offer competitive pricing, and make data-driven decisions to optimize their product portfolios. For instance, identifying companies with high-spec models or affordable pricing can guide marketing strategies or highlight areas for improvement in product design.
The dashboard also highlights that Realme dominates with a higher number of models, and companies like Nokia and Huawei have significantly higher average prices, suggesting premium positioning. These insights help manufacturers refine their strategies to meet consumer demands in the competitive smartphone market.

## Steps Followed
The following steps were taken to create the Mobile Phones Dashboard using Power BI Desktop, inspired by the Airlines-Dashboard process:

- Step 1: Loaded the dataset from a CSV file (assumed format based on the provided PDF data) into Power BI Desktop.

- Step 2: Opened the Power Query Editor and enabled "Column Distribution," "Column Quality," and "Column Profile" under the View tab to inspect data quality.

- Step 3: Selected "Column Profiling Based on Entire Dataset" to ensure comprehensive data analysis, as the default profiles only the first 1,000 rows.

- Step 4: Observed that the dataset (from Page 2) had no missing values in the "Company Name," "Model Name," "Front Camera Resolution," or "Back Camera Resolution" columns. However, the "Price Analysis" section (Page 3) was incomplete, so only the matrix visual data (Page 5) was used for price-related metrics.

- Step 5: In the Report View, applied a professional theme from the View tab to enhance visual appeal.

- Step 6: Created a bar chart to visualize the number of models by company, using "Company Name" from Page 5 and counting occurrences from Page 2.

- Step 7: Added two bar charts to represent the distribution of models by front camera resolution (e.g., 8 MP, 16 MP, 32 MP) and back camera resolution (e.g., 48 MP, 50 MP, 50 MP + 8 MP, etc.), based on Page 2 data.

- Step 8: Inserted a matrix visual to display average price (USD), average RAM (GB), and average weight (g) by company, using data from Page 5.

- Step 9: Added slicers for "Company Name" and "Front Camera Resolution" to allow interactive filtering of the dashboard, enabling users to focus on specific brands or camera specs.

- Step 10: Created card visuals to highlight key metrics, such as the total number of models (23 from Page 2) and the company with the most models (Realme, with 17 models).

- Step 11: Used a calculated column to categorize models by storage capacity (e.g., 128 GB, 256 GB, 512 GB) for deeper analysis.
![Image](https://github.com/user-attachments/assets/77f52148-736c-467d-8577-658cf32243b1)


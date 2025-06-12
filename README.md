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

## Snapshot of Dashboard (Power BI Desktop)
- A bar chart showing Oppo (115 models) and Apple (97 models) as the primary contributors.
- Bar charts for front and back camera resolution distributions.
- A matrix visual displaying average price, RAM, and weight by company.
- Slicers for interactive filtering by company and camera resolution.
- Card visuals for total models and Realme’s dominance.

### Insights
- The following insights were derived from the Mobile Phones Dashboard, based on the provided dataset:

#### Total Number of Models
- Total Models: 914

#### Company Breakdown:

- Oppo: 115 models (12.58% of total).
- Apple: 97 models (10.61% of total).
- Honor: 91 models (10.04% of total).

- Inference: Realme dominates the dataset with the highest number of models, indicating a strong market presence in this sample.

![Image](https://github.com/user-attachments/assets/77f52148-736c-467d-8577-658cf32243b1)

#### Camera Resolution Analysis
- Front Camera Resolution:

- 16 MP: 14 models (mostly Realme’s 13 and 14 series).
- 32 MP: 6 models (Realme 13 Pro 5G 256/512 GB and Honor 30 Pro 5G variants).
- 8 MP: 1 model (Honor 10X Lite).
- Back Camera Resolution:

- 50 MP + 8 MP: 7 models (Realme 14 Pro 5G variants).
- 48 MP + 2 MP: 4 models (Realme 14 Pro 5G and Honor 10X Lite).
- 50 MP + 2 MP: 3 models (Realme 13 series).
- 50 MP + 8 MP + 2 MP: 2 models (Realme 13 Pro 5G 128/256 GB).
- 50 MP + 8 MP + 50 MP: 2 models (Realme 13 Pro 5G 256/512 GB).
- 50 MP: 3 models (Honor 30 Pro 5G variants).
- 48 MP: 1 model (Honor 30 Pro 5G).
- Inference: Realme offers diverse back camera configurations, with 50 MP + 8 MP being the most common, while Honor focuses on higher front camera resolutions (32 MP) in its Pro models.

#### Matrix Visual Metrics (Average Price, RAM, Weight)
##### Top Companies by Average Price (USD):
- Nokia: $3,760.18 (highest, indicating premium positioning).
- Huawei: $1,116.57.
- Apple: $1,028.48.
- Realme: $271.91 (lowest among listed companies, suggesting budget-friendly models).

##### Average RAM (GB):
- Huawei: 9.71 GB (highest).
- Oppo/OnePlus: 9.43 GB.
- Realme: 8.07 GB.
- Nokia: 4.00 GB (lowest).
##### Average Weight (g):
- iQO: 538.33 g (highest, possibly an outlier or specialized device).
- Honor: 284.79 g.
- Realme: 245.97 g.
- Motorola: 182.42 g (lightest).
- Inference: Nokia and Huawei target premium markets with higher prices, while Realme offers budget-friendly options. Huawei and Oppo lead in RAM, and iQO’s high weight may indicate rugged or specialized devices.

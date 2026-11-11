#Seabass Hospital Dashboard | Power BI Practice Project

Project Overview:
    This personal Power BI project uses a publicly available hospital dataset to demonstrate data preparation, understanding of dataset structure, DAX calculations, and interactive dashboard development.

Data Source & Preparation
    Source: Kaggle – Hospital Dataset for Practice https://www.kaggle.com/datasets/blueblushed/hospital-dataset-for-practice?resource=download
-Used Python in Spyder to transform and expand the original 984 records into a synthetic appointment dataset containing 25,600 records.
Added appointment IDs, visit dates and timestamps, appointment statuses, department IDs, procedure IDs, and machine codes.
-Prepared separate datasets for appointments, departments, procedures, and treatment costs.
-Imported the prepared tables into Power BI for analysis.

Power BI Development
    Data Modeling: Worked with multiple related tables to analyze appointments, departments, procedures, and costs.
    DAX Measures: Calculated Average Length of Stay (excluding blanks) and Readmission Rate (using records with vali
                  Yes/No indicators).
    Dashboard: Visualized appointment trends and statuses, treatment costs by department, age groups, and key performance                  indicators.

Interactivity: Added date-range and department slicers for dynamic filtering.

Tools:
  Python (Spyder), Excel,Power BI,DAX

Note: This project uses synthetic data for learning and demonstration purposes. Results do not represent actual hospital performance.

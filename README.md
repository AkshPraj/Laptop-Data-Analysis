# Laptop data Analysis
In this Project, I’m going to clean laptop dataset in Microsoft Power Query. The task is to analyze the Laptop dataset and answer some key questions like, more expensive laptop, cheapest laptop laptop w.r.t. the brand, most expensive brand, distribution of price etc. Then, I use Microsoft Power BI to Visualize data and create an interactive dashboard.

## Data Source:

### Laptop:

column names: 
index, Company, Typename , Inches, Screen_resolution, has_ips_panel, Is_touchscreen, resolution_with, resolution_height, cpu_brand, cpu_name, cpu_speed, Ram, memory_type, primary_storage, secondary_storage, gpu_brand, gpu_name, OpSys, Weight, Price.



## Data Inspection:
Before starting the cleaning process I manually assessed the dataset, to look for inconsistencies, errors, null values, duplication, unwanted columns, irrelevant characters, and errors.

## Data Cleaning Process;
- Loaded file using Get data Tab, I chose text/csv
- I loaded the file into PowerQuery Editor for cleaning using Data type detection: based on entire dataset.

## Laptop.csv

- Corrected data types for each column
- Renamed column headings for clarity and consistency
- Checked for missing values, duplicates and Nulls, found none.
- Merging, removing unwanted column

DATASET BEFORE CLEANING         |        DATASET AFTER CLEANING
:-------------------------------:|:---------------------------------:
![](https://github.com/AkshPraj/Laptop-Data-Analysis/blob/main/image./before.PNG) | ![](https://github.com/AkshPraj/Laptop-Data-Analysis/blob/main/image./aftercleannnnn.PNG))

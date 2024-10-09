# Project 1: Data Cleaning and Preparation

# Overview

This project focuses on cleaning and preparing a dataset related to height and weight, which was initially provided in an Excel format.
The main goal of this project is to ensure that the data is clean, well-structured, and ready for further analysis and exploratory data analysis (EDA). 

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets), and it includes information such as gender, height, and weight of individuals.

# Repository Structure

The repository is organized as follows:

```
Portfolio/
│
├── Project1_DataCleaning/
│   ├── data/          # Contains the original and cleaned datasets
│   ├── scripts/       # R scripts for data cleaning
│   ├── results/       # Knitted HTML/PDF reports and output files
│   └── README.md      # Project description and instructions
```

# Files

- data
  - `Height_wight_dataset.xlsx`: The original dataset downloaded from Kaggle.
  - `cleaned_height_weight_data.csv`: The cleaned dataset, saved in CSV format after performing data cleaning tasks.
  
- scripts
  - `data_cleaning.R`: R script that contains the code for data cleaning, including loading the dataset, inspecting the data, handling missing values, and saving the cleaned dataset.
  
- results
  - `cleaned_data_project1.html`: The knitted HTML report that documents the data cleaning process.
  - `cleaned_data_project1.pdf`: A PDF version of the HTML report.

# Data Cleaning Steps

1. Creating Project Folders: Organized directories for storing data, scripts, and results.
2. Loading Dataset: Used the `readxl` package to load the Excel file.
3. Inspecting Data: Checked the structure of the dataset, inspected the first few rows, and generated a summary of the data.
4. Handling Missing Data: Verified that the dataset did not contain missing or inconsistent values.
5. Verifying Data Types: Ensured that all variables have the correct data types (numeric for height and weight, and categorical for gender).
6. Saving Cleaned Data: Saved the cleaned dataset in CSV format for further analysis.

# How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Ade-Idong/project1-data-cleaning.git
   ```
2. Open the R scripts in your R environment or RStudio to replicate the data cleaning process.

3. View the knitted HTML or PDF reports in the `results/` folder to follow the steps and outcomes of the data cleaning.

# Requirements

To run the R script and replicate the data cleaning process, you will need the following R packages:
- `readxl` (for reading Excel files)
- `tidyverse` (for data manipulation and cleaning)
  
You can install them using the following commands in R:
```r
install.packages("readxl")
install.packages("tidyverse")
```

# Conclusion

In this project, we successfully prepared the dataset for further analysis by performing basic cleaning tasks.
The cleaned dataset is now ready for use in subsequent exploratory data analysis and predictive modeling projects.


# Avaliable languages

The project is available in two languages, English and Nigerian Pidgin.


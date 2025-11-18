# Data Cleaning and Preprocessing Task

## 📋 Project Overview
This project involves cleaning and preprocessing a raw dataset using Microsoft Excel as part of a Data Analyst Internship Task. The goal is to handle common data quality issues and prepare the dataset for analysis.

## 🎯 Objective
Clean and prepare a raw dataset containing null values, duplicates, and inconsistent formats to make it analysis-ready using Excel functions and tools.

## 📊 Dataset Used
- **Dataset Name**: ["customer 1,Medical1,Mall1,Sales data1, Netflix Movies and TV shows"]
- **Source**: Kaggle


## 🛠️ Tools & Technologies
- **Primary Tool**: Microsoft Excel
- **Features Used**: Filters, Remove Duplicates, Find & Replace, Text Functions, Data Validation

## 🧹 Data Cleaning Steps Performed

### 1. Handling Missing Values
- Used Excel filters to identify blank cells in each column
- **Strategy Applied**: [Choose what you did]
  - Removed rows with critical missing values
  - Filled numerical columns with average or median
  - Filled categorical columns with "Unknown" or most frequent value

### 2. Removing Duplicates
- Used Excel's "Remove Duplicates" feature (Data tab)
- **Duplicates Removed**: [Number of duplicates found and removed]

### 3. Standardizing Text Values
- Used Find & Replace and Text functions (UPPER, LOWER, PROPER)
- **Examples**:
  - "M" → "Male", "F" → "Female"
  - "USA" → "United States", "UK" → "United Kingdom"
  - Standardized case consistency across text columns

### 4. Date Format Standardization
- Used Format Cells to set consistent date format: `dd-mm-yyyy`
- Applied Text to Columns for date conversion where needed

### 5. Column Header Cleaning
- Renamed column headers to be clean and uniform
- **Changes Made**:
  - Converted to proper case/lowercase
  - Removed special characters and spaces
  - Made headers descriptive and consistent

### 6. Data Type Correction
- Ensured proper data types using Format Cells:
  - Numerical columns → Number format
  - Date columns → Date format
  - Text columns → Text format

### 7. Data Validation
- Used Data Validation to prevent future inconsistent entries
- Created dropdown lists for categorical columns where appropriate


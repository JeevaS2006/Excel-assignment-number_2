# Excel Data Cleaning and Transformation – Product Dataset

### Data Analyst Portfolio | Microsoft Excel

## 📌 Project Overview

This project focuses on data cleaning and preparation using Microsoft Excel to transform a raw product dataset into a clean, consistent, and analysis-ready format.

As an aspiring Data Analyst, I performed essential data preprocessing operations to improve data quality, eliminate inconsistencies, standardize formats, and enhance dataset usability.

The project demonstrates practical Excel skills commonly used in real-world data analytics workflows.

## 🎯 Project Objectives

* Identify and handle missing values.
* Correct inconsistent text formats and category typos.
* Detect and remove duplicate records.
* Split and merge columns to improve data structure.
* Apply appropriate date and currency formatting.
* Use conditional formatting to highlight important information.
* Prepare a structured dataset for further analysis.

## 📂 Dataset Description

**Dataset Name:** Product Dataset

The dataset contains product-related information with the following attributes:

| Column       | Description                                              |
| ------------ | -------------------------------------------------------- |
| Product ID   | Unique identifier containing product-related information |
| Product Name | Name of the product                                      |
| Brand Name   | Manufacturer or brand of the product                     |
| Quantity     | Available product quantity                               |
| Category     | Product classification                                   |
| Price        | Product price                                            |

## 🛠️ Tools & Technologies

* Microsoft Excel
* Find and Replace
* Remove Duplicates
* Text to Columns
* Flash Fill
* Excel Formulas
* Number Formatting
* Conditional Formatting
* Data Validation and Quality Checks

## 🔍 Data Cleaning and Transformation Process

### 1. Handling Missing Values

* Checked the Price column for blank or missing values.
* Identified products with missing category information.
* Proposed appropriate strategies for handling missing values without introducing inaccurate information.
* Recommended verifying missing prices against reliable product records before updating them.
* Suggested using product information to determine missing categories, while retaining an appropriate label for records that cannot be classified reliably.

### 2. Correcting Inconsistent Data

* Identified inconsistent capitalization and text formatting in the Product Name column.
* Used Excel's Find and Replace functionality to standardize product names.
* Identified spelling mistakes and inconsistent labels in the Category column.
* Corrected category typos and standardized category names.

### 3. Removing Duplicate Records

* Checked for duplicate records using all columns.
* Used Excel's Remove Duplicates feature to eliminate exact duplicate rows.
* Preserved records containing legitimate differences in product attributes.

### 4. Splitting and Merging Data

**Product ID Transformation**

* Split the Product ID column into Manufacturing Date and Country Code.
* Removed unnecessary characters, where applicable.
* Structured the extracted information into separate columns for easier analysis.

**Product Brand Creation**

* Combined Brand Name and Product Name into a single column named Product Brand.
* Improved readability and simplified product identification.

### 5. Number Formatting

* Formatted the Price column using an appropriate currency format.
* Converted Manufacturing Date into a date format.
* Standardized the date display to `DD-MM-YYYY`.

### 6. Conditional Formatting

* Applied data bars or color scales to the Price column to visualize price variations.
* Created a custom conditional formatting rule to highlight products belonging to the Electronics category.
* Improved the visual readability of the cleaned dataset.

## 📊 Final Outcome

The data cleaning process aims to produce a structured and analysis-ready product dataset with:

* Improved data consistency and accuracy.
* Reduced duplicate records.
* Standardized product names and categories.
* Properly formatted numerical and date fields.
* Enhanced readability through conditional formatting.
* Better suitability for further analysis and reporting.

## 📁 Repository Structure

```text
Excel-Data-Cleaning-Product-Dataset/
│
├── README.md
│
├── Dataset/
│   └── Product_Dataset.xlsx
│
├── Output/
│   └── Cleaned_Product_Dataset.xlsx
│
└── Screenshots/
    ├── Missing_Values.png
    ├── Duplicate_Removal.png
    ├── Text_Transformation.png
    ├── Column_Splitting_Merging.png
    └── Conditional_Formatting.png
```

*Note: Update the folder and file names according to your actual repository structure.*

## 💡 Key Learnings

Through this assignment, I gained practical experience in:

* Understanding the importance of data quality in analytics.
* Identifying and correcting common data quality issues.
* Using Excel tools for data preprocessing and transformation.
* Structuring raw datasets into meaningful analytical formats.
* Applying visual techniques to improve data interpretation.
* Preparing datasets for subsequent analysis and visualization.

## 🚀 Future Scope

The cleaned dataset can be used for further exploratory data analysis, including:

* Product category-wise analysis.
* Brand-wise product distribution.
* Price comparison across categories.
* Inventory quantity analysis.
* Dashboard development using Excel or Power BI.

## 👩‍💻 About Me

I am an aspiring Data Analyst with an interest in data cleaning, data visualization, exploratory data analysis, and transforming raw data into meaningful insights.

This project is part of my growing Data Analytics portfolio, where I document my practical learning and hands-on assignments.

**Skills:** Microsoft Excel | Data Cleaning | Data Preprocessing | Data Transformation | Data Quality

---

⭐ *Thank you for visiting my portfolio repository!*

# Python Data Transformation and Crowdfunding Database Project

## Description

This project demonstrates the process of extracting, transforming, and loading data to create a comprehensive crowdfunding database. It includes transforming raw Excel data into structured CSV files. The goal is to showcase how to handle data transformations and database schema creation for real-world applications.

---

## Summary

The project is divided into the following parts:

### **Data Transformation**

Transform raw data from Excel files into well-structured DataFrames and CSV files.

- **Category and Subcategory DataFrames:**

  - Created from the `crowdfunding.xlsx` file.
  - Each category and subcategory is assigned a unique identifier (`category_id` and `subcategory_id`).
  - Exported as `category.csv` and `subcategory.csv`.

- **Campaign DataFrame:**

  - Extracted from the `crowdfunding.xlsx` file and includes detailed information such as goals, pledges, and launch/end dates.
  - Renamed and formatted columns for clarity and consistency.
  - Exported as `campaign.csv`.

- **Contacts DataFrame:**
  - Extracted and cleaned from `contacts.xlsx` using Python dictionary methods or regular expressions.
  - Added columns for first and last names, ensuring a clean and organized structure.
  - Exported as `contacts.csv`.

## Key Deliverables

**Data Transformation:**

- Cleaned and formatted CSV files:
  - `category.csv`
  - `subcategory.csv`
  - `campaign.csv`
  - `contacts.csv`

## Tools and Libraries

### Python Libraries:

- Pandas
- Numpy
- Matplotlib (for optional data visualization)
- Regex (for data cleaning and extraction)
- JSON

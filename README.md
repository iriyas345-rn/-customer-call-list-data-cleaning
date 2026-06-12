# Customer Call List Data Cleaning Project

## Project Overview

This project focuses on cleaning and preparing a customer call list dataset using Python and Pandas. The original dataset contained duplicate records, inconsistent formatting, unnecessary columns, missing values, and customers who should not be contacted. The objective was to transform the raw data into a clean, contact-ready dataset suitable for business use.

## Objectives

* Clean and standardize customer information.
* Remove duplicate records.
* Eliminate unnecessary columns.
* Format phone numbers consistently.
* Separate address information into meaningful components.
* Exclude customers who requested not to be contacted.
* Prepare a final dataset ready for customer outreach activities.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook / VS Code

## Data Cleaning Steps Performed

### 1. Imported the Dataset

* Loaded the Excel dataset into a Pandas DataFrame.

### 2. Removed Duplicate Records

* Identified and removed duplicate customer entries to ensure data accuracy.

### 3. Dropped Unnecessary Columns

* Removed the `Not_Useful_Column` as it did not provide any value for the business objective.

### 4. Standardized Text Fields

* Cleaned the `Last_Name` column by removing unwanted special characters and inconsistencies.

### 5. Cleaned and Formatted Phone Numbers

* Removed non-numeric characters from phone numbers.
* Standardized phone numbers into a consistent format (`XXX-XXX-XXXX`).

### 6. Split Address Information

* Separated the `Address` column into:

  * Street Address
  * State
  * Zip Code (where available)

### 7. Processed Contact Preferences

* Removed customers marked as `Do_Not_Contact` to comply with customer communication preferences.

### 8. Handled Missing Contact Information

* Removed records without valid phone numbers, as the purpose of the dataset was to create a usable customer call list.

### 9. Reset the DataFrame Index

* Reset the index after data cleaning to maintain a clean and organized structure.

## Final Outcome

The final dataset contains only customers who:

* Have valid contact information.
* Have not opted out of communication.
* Are free from duplicate records.
* Follow a standardized data format.

The cleaned dataset is ready for customer calling campaigns and further business analysis.

## Files Included

* `Customer Call List.xlsx` – Original dataset
* `data_cleaning.ipynb` – Jupyter Notebook containing the cleaning process
* `cleaned_customer_call_list.csv` – Final cleaned dataset
* `README.md` – Project documentation

## Key Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Handling Missing Values
* String Manipulation
* Data Transformation
* Pandas Operations
* Preparing Data for Business Use

## Author

**Riyas Ismail**

Aspiring Data Analyst with an interest in transforming raw data into meaningful and actionable insights.

# Customer Call List Data Cleaning Project

## Project Overview

This project focuses on cleaning and preparing a customer call list dataset using Python and Pandas. The original dataset contained duplicate records, inconsistent formatting, unnecessary columns, missing values, and customers who should not be contacted. The objective was to transform the raw data into a clean, contact-ready dataset suitable for business use.

## Objectives

* Clean and standardize customer information.
* Remove duplicate records.
* Eliminate unnecessary columns.
* Format phone numbers consistently.
* Separate address information into meaningful components.
* Exclude customers who requested not to be contacted.
* Prepare a final dataset ready for customer outreach activities.

## Tools and Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook / VS Code

## Data Cleaning Steps Performed

### 1. Imported the Dataset

* Loaded the Excel dataset into a Pandas DataFrame.

### 2. Removed Duplicate Records

* Identified and removed duplicate customer entries to ensure data accuracy.

### 3. Dropped Unnecessary Columns

* Removed the `Not_Useful_Column` as it did not provide any value for the business objective.

### 4. Standardized Text Fields

* Cleaned the `Last_Name` column by removing unwanted special characters and inconsistencies.

### 5. Cleaned and Formatted Phone Numbers

* Removed non-numeric characters from phone numbers.
* Standardized phone numbers into a consistent format (`XXX-XXX-XXXX`).

### 6. Split Address Information

* Separated the `Address` column into:

  * Street Address
  * State
  * Zip Code (where available)

### 7. Processed Contact Preferences

* Removed customers marked as `Do_Not_Contact` to comply with customer communication preferences.

### 8. Handled Missing Contact Information

* Removed records without valid phone numbers, as the purpose of the dataset was to create a usable customer call list.

### 9. Reset the DataFrame Index

* Reset the index after data cleaning to maintain a clean and organized structure.

## Final Outcome

The final dataset contains only customers who:

* Have valid contact information.
* Have not opted out of communication.
* Are free from duplicate records.
* Follow a standardized data format.

The cleaned dataset is ready for customer calling campaigns and further business analysis.

## Files Included

* `Customer Call List.xlsx` – Original dataset
* `data_cleaning.ipynb` – Jupyter Notebook containing the cleaning process
* `cleaned_customer_call_list.csv` – Final cleaned dataset
* `README.md` – Project documentation

## Key Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Handling Missing Values
* String Manipulation
* Data Transformation
* Pandas Operations
* Preparing Data for Business Use

## Author

**Riyas Ismail**

Aspiring Data Analyst with an interest in transforming raw data into meaningful and actionable insights.


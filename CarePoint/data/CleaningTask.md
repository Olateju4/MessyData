# Data Cleaning Tasks
## CarePoint: Dirty Clinic Patient Dataset

### Objective

Clean and prepare the dataset for analysis using any analytics tool.

---

# Task 1: Initial Assessment

1. Load the dataset.
2. Examine the structure.
3. Determine:
   - Number of rows
   - Number of columns
   - Missing values
   - Duplicate records
   - Data types

Deliverable:
- Data Quality Assessment Report

---

# Task 2: Handle Missing Values

Identify missing values in:

- First_Name
- Last_Name
- Gender
- Age
- Phone_Number
- Email
- Diagnosis
- Payment_Status

Choose an appropriate strategy:

- Remove rows
- Impute values
- Replace with Unknown

Document all decisions.

---

# Task 3: Remove Duplicates

Identify:

- Exact duplicates
- Partial duplicates
- Duplicate Patient_IDs

Remove unnecessary duplicates.

Deliverable:
- Duplicate Removal Summary

---

# Task 4: Standardize Text Fields

Clean:

- First_Name
- Last_Name
- City
- State
- Doctor_Assigned

Tasks:

- Remove extra spaces
- Standardize capitalization
- Correct obvious spelling errors

---

# Task 5: Standardize Gender Values

Convert all gender values into:

- Male
- Female

---

# Task 6: Clean Date Fields

Standardize:

- Date_of_Birth
- Visit_Date

Convert all dates into a single format.

Recommended:

YYYY-MM-DD

---

# Task 7: Validate Age Values

Identify:

- Negative ages
- Ages above 120
- Missing ages

Correct or remove invalid values.

---

# Task 8: Clean Contact Information

Phone Numbers:

- Remove spaces
- Remove special characters
- Standardize format

Emails:

- Identify invalid emails
- Correct where possible

---

# Task 9: Standardize Diagnosis Categories

Examples:

HTN → Hypertension

High Blood Pressure → Hypertension

Diabetis → Diabetes

Create a standardized diagnosis list.

---

# Task 10: Clean Payment Information

Standardize:

Paid

Pending

Insurance

---

# Task 11: Validate Numeric Fields

Review:

- Weight
- Height
- Payment_Amount

Identify:

- Negative values
- Missing values
- Unrealistic values

Correct where appropriate.

---

# Task 12: Create a Clean Dataset

Create:

clean_CarePoint_dataset.csv

Requirements:

- No duplicates
- Consistent formats
- Valid data types
- Standardized categories

---

# Task 13: Data Quality Report

Prepare a summary showing:

| Metric | Before Cleaning | After Cleaning |
|----------|----------|----------|
| Rows | | |
| Missing Values | | |
| Duplicate Records | | |
| Invalid Emails | | |
| Invalid Ages | | |

---

# Bonus Tasks

### Exploratory Data Analysis

After cleaning:

1. Determine the most common diagnosis.
2. Calculate average patient age.
3. Analyze gender distribution.
4. Calculate total revenue.
5. Identify top-performing doctors.
6. Create visualizations.

---

# Submission Requirements

Share your learning points on your socials:
- Data quality report
- Cleaning methodology
- Visualizations (optional)
Tag me to it, I will love to see your work (LinkedIn- Mariam Jaiyeola)
---

## Learning Outcomes

After completing this project, students should be able to:

- Assess data quality
- Clean messy datasets
- Handle missing values
- Standardize data formats
- Remove duplicates
- Prepare data for analysis
- Document data cleaning workflows

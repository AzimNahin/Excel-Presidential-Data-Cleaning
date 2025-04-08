# 🧹 President Information – Data Cleaning (Excel Project)

This repository showcases a data cleaning project performed entirely in **Microsoft Excel**, using a dataset of U.S. Presidents. The work includes identifying and correcting inconsistencies, formatting data for readability, and preparing the dataset for future data analysis or visualization.

## 📊 Dataset Overview

The dataset contains historical information about U.S. Presidents, including:
- **President Name**
- **Political Party**
- **Vice President**
- **Salary**
- **Date Created**
- **Date Updated**
- *(Originally included more columns like “prior role” and row indexes)*

## ✅ Data Cleaning Process

All cleaning was done manually using **Excel formulas**, **formatting tools**, and **filters**. Below are the key changes made:

### 🔧 Removed Redundancies & Irrelevant Data
- Deleted the **index column** (`Unnamed: 0`) and unnecessary metadata.
- Removed the **“prior”** column due to inconsistent formatting and encoding errors.

### 👤 Standardized Names
- Fixed inconsistent casing (e.g., `john adams`, `JAMES MONROE`) by converting all names to **title case**.
- Trimmed extra spaces within names (e.g., `George    Clinton` → `George Clinton`).

### 🏛️ Party Standardization
- Standardized inconsistent party names like:
  - `Democratic-  Republican` → `Democratic-Republican`

### 💼 Cleaned Salary Data
- Verified numeric consistency and formatting for the **salary** column.

### 📅 Date Format Fixes
- Ensured all **date_created** and **date_updated** fields follow the standard ISO format: `YYYY-MM-DD`.

## 📁 Repository Contents

- `President Information - Data Cleaning.xlsx`: The Excel file containing:
  - `US_Presidents Data` – original raw dataset
  - `US_Presidents Data Fixed` – cleaned and formatted version

## 🛠️ Tools Used

- **Microsoft Excel** (no code required!)
  - Find & Replace
  - Text functions (e.g., `PROPER()`, `TRIM()`)
  - Filter and Sort
  - Manual inspection and correction

## 🚀 Potential Next Steps

- Export cleaned dataset to CSV for public data analysis.
- Visualize trends in U.S. Presidential data (e.g., salaries, party changes).
- Augment dataset with additional fields like education, birthplace, or term years.

## 👥 Contributor

- [Azim Nahin](https://github.com/AzimNahin)

# 🛳️ Titanic Dataset Analysis using Pandas

This project demonstrates basic data analysis using the **Pandas** library on the Titanic dataset. It covers common data handling tasks such as loading data, inspecting it, handling missing values, filtering, grouping, and computing statistics.

---

## 📁 Dataset Used

- **File Name:** `titanic3.csv`
- **Source:** Converted from `titanic3.xls` to CSV format.

---

## ✅ Tasks Performed

### 1. Load the Dataset
The dataset was loaded into a Pandas DataFrame for analysis.

### 2. View First 5 Rows
The first five rows of the dataset were displayed to get an overview of the data.

### 3. Dataset Information
The structure of the dataset was examined, including data types and the number of non-null values for each column.

### 4. Describe Data
Basic statistical summaries (mean, median, min, max, standard deviation) were generated for the numerical columns.

### 5. Count Missing Values
The number of missing values in each column was counted to understand which features require cleaning.

### 6. Filter by Gender
All rows where the passenger was female were filtered and viewed.

### 7. Survival Rate
The percentage of passengers who survived was calculated to understand the overall survival distribution.

### 8. Average Age
The average age of the passengers was computed.

### 9. Group by Class and Average Fare
The dataset was grouped by passenger class and the average fare for each class was calculated.

### 10. Sort by Fare
The dataset was sorted in descending order based on the fare column to identify the top 10 highest fares.

---

## 🧹 Handling Missing Data

### Columns with missing values:
- `age`, `fare`: numeric — filled with mean or median values to preserve data consistency
- `boat`: categorical — missing values were filled with the string "Unknown" to indicate missing lifeboat info

---

## 🧰 Tools & Libraries Used

- Python 3.x
- Pandas
- Jupyter Notebook / VS Code

---

## 💡 Notes

- This lab task focused on fundamental data analysis techniques using real-world data.
- Handling missing data and understanding dataset structure are key skills in data science.

---

## 🔗 License

For educational and academic use only.


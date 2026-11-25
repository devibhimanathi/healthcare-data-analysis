# Healthcare Data Analysis

Exploratory analysis of a healthcare patient dataset using Python, Pandas, NumPy and Matplotlib. The project cleans the data, summarizes key patterns, and presents them through charts.

## Objective
Understand patient information, diseases, medical costs and recovery status, and generate meaningful insights from the data.

## Dataset
Patient records with these columns: Patient_ID, Age, Age_Group, Gender, Blood_Group, City, Disease, Medicine, Height_cm, Weight_kg, BMI, Sugar_Level, Cholesterol, Admission_Date, Discharge_Date, Medical_Cost, Recovery_Status.

File: `healthcare.xlsx`

## Tools and technologies
- Python
- Pandas and NumPy
- Matplotlib
- Google Colab

## What I did
- **Data cleaning:** checked missing values, removed duplicate records, converted admission and discharge dates to datetime format
- **Summary statistics:** total patients, average age, BMI, weight, height, sugar level, cholesterol and medical cost, plus the top disease, medicine and city
- **Grouped analysis:** average medical cost by disease and by gender, and the patients with the highest and lowest cost
- **Visualization:** bar charts, pie charts, histograms, a line chart, scatter plots and a box plot

## Visualizations
- Patients by disease, age group, blood group and medicine
- Average medical cost by disease and by gender
- Gender distribution and recovery status
- Age and BMI distribution
- Age vs medical cost, BMI vs sugar level
- Box plot of medical cost

## Key insights
- [Top disease and how many patients have it]
- [Disease with the highest average medical cost]
- [Recovery status result, e.g. the percentage recovered]
- [One pattern you noticed, e.g. age vs cost or BMI vs sugar level]

## How to run
1. Open `Health care data analysis.ipynb` in Google Colab
2. Click **Runtime → Run all**

The notebook loads `healthcare.xlsx` from this repository automatically.

## Author
Bhimanathi Devi
[LinkedIn](https://www.linkedin.com/in/devi-bhimanathi-484341382/) | [GitHub](https://github.com/devibhimanathi)

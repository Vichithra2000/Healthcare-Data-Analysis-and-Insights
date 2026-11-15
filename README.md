# Healthcare-Data-Analysis-and-Insights
## 1. Problem Statement
- The healthcare industry generates vast amounts of data daily, providing valuable insights for healthcare providers and policymakers to improve patient care, allocate resources effectively,and manage healthcare costs.This project aims to analyze a comprehensive healthcare dataset comprising medical examinations, hospitalization details, and customer profiles to extract insights into patient health profiles, medical histories, and healthcare costs. By exploring relationships between various health metrics, identifying trends, and visualizing key patterns, we aim to deliver actionable insights to healthcare stakeholders for informed decision-making
through rigorous data cleaning, transformation, exploration, and analysis.
## 2. Dataset Description
- The project utilizes three primary data tables, which are combined into a single master sheet named "Healthcare" using Customer ID as the common key:

    Medical Examinations Table: Contains patient medical examination metrics (such as BMI, HbA1C, heart issues, transplant history, cancer history, number of major       surgeries, and smoker status).

    Hospitalization Details Table: Contains hospital admission details, dates, hospital tiers, city tiers, and related metrics.

    Customer Names Table: Contains customer name details, which are split into components.
## 3. Data preprocessing
- Data Cleaning: Handled missing values (marked with '?'), filling missing months/years, and resolving missing categorical values like smoker status, hospital           tier, and city tier.
    Data Transformation & New Columns:

     Name Splitting: Split the 'names' column into Title, First Name, and Last Name.

     Numeric Conversions: Converted the "NumberOfMajorSurgeries" column into numerical data.

     Weight Status: Categorized BMI into Underweight, Normal Weight, Overweight, and Obesity.

     Diabetes Status: Categorized HbA1C levels into Normal, Prediabetes, and Diabetes.

     Date & Age Calculation: Merged date components into a standardized Date of Birth column and calculated patient ages as of June 8, 2023.

     Currency Formatting: Formatted healthcare charges as currency ($).
## 4.Exploratory Data Analysis
- Pie/Donut Charts:

  Analyzed the distribution of cancer history among smokers and non-smokers.

  Examined how the total number of major surgeries and average HbA1C differ between patients with and without a history of transplants.

  - Column/Bar Charts:

    Explored how healthcare charges vary across different weight statuses and diabetes statuses.

   Compared average charges for each hospital tier across different states.

  - Line/Scatter Plots:
    Investigated correlations between age, BMI, HbA1C, and healthcare charges.

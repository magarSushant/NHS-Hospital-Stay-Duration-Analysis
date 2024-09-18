### **NHS-Hospital-Stay-Duration-Analysis**
Predictive modeling project for analyzing hospital stay durations using Alteryx.
Hospital Stay Duration Analysis (Fictitious Case Study)

# **_**Project Overview**_**

This project is a fictitious case study created as part of the MSc Business Analytics curriculum at Royal Holloway, University of London. The objective was to predict hospital stay durations for back surgery patients using data analysis and predictive modeling techniques. While the scenario is fictional, the techniques and approaches employed are applicable to real-world healthcare analytics.

# _**Context and Objectives**_

The project simulates a consultancy assignment for the NHS Trust, aiming to:

Optimize resource allocation (beds, staff, medical supplies) through accurate forecasting.

Reduce costs by identifying factors contributing to prolonged hospital stays.

Enhance patient care by improving recovery protocols and reducing unnecessary hospitalization.

Support strategic decision-making by providing data-driven insights for service expansion and staffing.

# _**Data Processing**_

The following steps were taken to prepare the dataset:

_Time Interval Calculation_: Key metrics such as hours until ambulation and total recovery time were computed.

_Patient Grouping_: Patients were grouped by age and gender for more insightful analysis.

_Surgery Type Analysis_: Data on surgery types and approaches was parsed and merged for model development.

_Temporal Analysis_: Patterns in admission and discharge times were explored to optimize hospital operations.


# _**Predictive Modeling**_

Several machine learning models were applied to forecast hospital stay durations:

_Linear Regression_: The best-performing model with the highest accuracy.

_Decision Tree & Random Forest_: Provided additional insights, though with slightly higher error margins compared to Linear Regression.


# _**Key Findings**_

_Early Ambulation_: Strong correlation with shorter hospital stays.

_Surgery Type & Approach_: Invasive procedures were linked to longer recovery times.

_Admission & Discharge Patterns_: Weekends and certain weekdays were associated with prolonged stays.


# _**Technologies Used**_

_Alteryx_: For data preparation and modeling.

_Excel_: For data management.

_GitHub_: Version control and repository for project materials.


# _**How to Use This Repository**_

_Download the Alteryx Workflow_: Replicate the data processing and predictive modeling steps.

_Explore the Data_: Place data files in the relevant folders (note that datasets used here are purely fictional).

_View the Report_: Access the consultancy report for detailed analysis and insights.

# _**Project Resources**_

For detailed analysis and methodology, please refer to the [Alteryx Workflow](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/NHS-Consultancy%20Atleryx%20Workflow.yxmd), where all assumptions, data preparation steps, and methodologies are thoroughly documented with comments. 

Below are links to the project files:

- [Consultancy Report (PDF)](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/NHS-Consultancy%20Report.pdf)  
  The full consultancy report, detailing the findings, recommendations, and predictive model evaluation for the NHS Trust hospital stay duration case study.

- [Alteryx Workflow](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/NHS-Consultancy%20Atleryx%20Workflow.yxmd)  
  The Alteryx workflow used for data preparation, blending, analysis, and predictive modeling. All steps are annotated with comments explaining the process and assumptions.

- [Patient Information Dataset](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/Datasets/Patient%20Information.xlsx)  
  This dataset contains demographic and medical information for patients.

- [Surgical Information Dataset](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/Datasets/Surgical%20Information.xlsx)  
  This dataset contains detailed information about the surgical procedures performed.

- [ICD-10 Codes Dataset](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/Datasets/ICD-10%20Codes.xlsx)  
  The dataset contains ICD-10 codes for categorizing the surgical procedures.

- [Current Patients Dataset](https://github.com/magarSushant/NHS-Hospital-Stay-Duration-Analysis/blob/main/Datasets/Current%20Patients.xlsx)  
  This dataset is used for forecasting the length of stay for current patients undergoing surgery.



# **_Disclaimer_**

This project is entirely fictitious and was created for academic purposes. The NHS Trust mentioned in this case study is not real, and the data used does not reflect actual patient information.


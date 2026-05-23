 Emergency Department Data Analysis (MIMIC-IV)

# Project Overview
This project provides a comprehensive data analysis of emergency department (ED) patient stays, focusing on clinical outcomes, duration of stay, and vital signs correlations using the MIMIC-IV dataset.

# Methodology
- Data Preprocessing: Merging administrative and clinical datasets using stay_id as a primary key.
- Statistical Analysis: Assessing patient stay duration relative to diagnosis and heart rate.
- Data Quality Audit: A rigorous assessment was conducted to identify missing data. Findings (e.g., rhythm 96.8% missing) were documented to ensure statistical integrity, opting for a transparent approach rather than synthetic imputation to preserve genuine clinical observations.

# Key Findings
- Admission Correlation: Patients admitted to the hospital exhibit a higher average heart rate (88.11 bpm) compared to those discharged home (82.4 bpm).
- Temporal Patterns: Identified peak hours of congestion impacting patient stay duration.
- Clinical Insight: Analysis of the top 10 diagnoses by duration provides insights into clinical workload management.

# Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook / Google Colab

# Data Acknowledgement
The data used in this project is sourced from the MIMIC-IV database (PhysioNet). I acknowledge the creators of the MIMIC database and adhere to their Data Usage Agreement. This project utilizes the data for academic analysis purposes only.
## Project Visualizations

### Average Stay Duration by Diagnosis
![Top 10 Diagnoses](download(3).png)
This chart illustrates the top 10 diagnoses impacting patient stay duration.

### Patient Load vs. Time of Day
![Patient Load Analysis](download(4).png)
This chart illustrates the variation in average patient stay duration across different hours of the day. The fluctuations highlight specific peak congestion times, which are critical for optimizing emergency department staffing and patient throughput.
### Distribution of Heart Rate by Patient Disposition
![Heart Rate Analysis](download(5).png)
This box plot displays the distribution of heart rates categorized by patient disposition (e.g., Admitted, Home, Transferred). It highlights differences in physiological baseline measurements among various patient outcomes, providing insight into the clinical status of patients at the time of their disposition from the ED

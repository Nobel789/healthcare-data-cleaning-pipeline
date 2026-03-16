# healthcare-data-cleaning-pipeline
"End-to-end healthcare data cleaning pipeline focusing on PII removal (HIPAA compliance), handling missing values, and data standardization."


Project Objective

This project demonstrates a robust pipeline for preparing raw medical records for analysis. The focus is on maintaining data integrity while ensuring compliance with privacy standards like HIPAA and GDPR.
🛠️ Key Features

    PII Removal: Successfully identified and dropped sensitive columns (Patient_Name, EmailID).

    Data Standardization: Unified inconsistent entries in Ethnicity and Diagnosis_Code.

    Handling Anomalies: Detected and managed outliers in physiological data (e.g., Age, Height).

    Validation: Ensured all records follow a consistent format for downstream Machine Learning.

🧪 How to Run

    Install dependencies: pip install -r requirements.txt

    Open the notebook: Cleaning_and_Validating_Healthcare_Data_Using_Python.ipynb

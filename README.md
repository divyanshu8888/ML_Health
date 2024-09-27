**Name**: Divyanshu Mishra  
**Student ID**: 1281413  
**Assignment**: Assignment 2 - Machine Learning Applications for Health (COMP90089_2024_SM2)  

---

## Profound Hypotension Analysis - ICU Patients

## Assignment Details:
This repository contains the code, datasets, and outputs for the "Profound Hypotension Analysis - ICU Patients" assignment. The primary objective of this project is to analyze clinical data of ICU patients experiencing profound hypotension and derive insights regarding patient outcomes, demographics, and associated comorbidities.

## Problem Description:
Profound hypotension is a critical condition for patients in the ICU. In this project, I aim to:

1. Conduct a detailed exploratory data analysis (EDA) of the given cohort.
2. Implement and evaluate **K-Means clustering** to identify patient subgroups and predict outcomes.
3. Visualize and interpret the results to provide actionable clinical insights.

Understanding these patterns can help improve patient management, develop tailored intervention strategies, and potentially enhance patient outcomes.

## Setting Up the Environment:
To ensure the smooth execution of the code, please follow the steps below:

1. **Clone the Repository:**
   ```bash
   git clone <repository-link>
   cd assignments
   ```

2. **Install Dependencies:**
   Use the packages listed in `requirements.txt` to set up your environment:
   ```bash
   pip install -r requirements.txt
   ```

   Note: The assignment was initially done on Google Colab, where most libraries are pre-installed. You may need to install additional libraries like `lifelines` if running locally:
   ```bash
   !pip install lifelines
   ```

3. **Use the Correct Dataset Name:**
   Ensure the dataset containing hypotension patient information is named **`hypotension_patients`** when you run the code locally. The dataset should be in the same directory as the notebook.

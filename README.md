**Assignment 2 - Machine Learning Applications for Health (COMP90089_2024_SM2)**

---

## Profound Hypotension Analysis - ICU Patients

### Author: Divyanshu Mishra  
### Student ID: 1281413

## Assignment Details:
This repository contains the code, datasets, and outputs for the "Profound Hypotension Analysis - ICU Patients" assignment. The main goal of this project is to analyze data from ICU patients with profound hypotension and understand their outcomes, demographics, and related health issues.

In this assignment, I focused on:

- Doing a thorough exploratory data analysis (EDA) to look at patient characteristics like age, gender, length of stay, comorbidity index, and APSIII scores.
- Using **K-Means clustering** to group patients based on their clinical profiles.
- Finding the best number of clusters using the **elbow method** to make sure the analysis is meaningful.
- Creating visualizations to show differences in patient characteristics across clusters and how these relate to patient outcomes.
- Drawing insights that can help healthcare providers manage patients with profound hypotension better.

These findings can lead to improved care and treatment strategies for critically ill patients.

## Problem Description:
Profound hypotension is a critical condition for patients in the ICU. In this project, I aim to:

1. Conduct a detailed exploratory data analysis (EDA) of the given cohort.
2. Implement and evaluate **K-Means clustering** to identify patient subgroups and predict outcomes.
3. Visualize and interpret the results to provide actionable clinical insights.

Understanding these patterns can help improve patient management, develop tailored intervention strategies, and potentially enhance patient outcomes.

## Resources Used:
- [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
- [NumPy](https://numpy.org/) for numerical computations.
- [Scikit-Learn](https://scikit-learn.org/stable/) for implementing machine learning algorithms, specifically K-Means clustering.
- [Seaborn](https://seaborn.pydata.org/) and [Matplotlib](https://matplotlib.org/) for data visualization.
- [Lifelines](https://lifelines.readthedocs.io/en/latest/) for survival analysis.

## Setting Up the Environment:
To ensure the smooth execution of the code, please follow the steps below:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/divyanshu8888/ML_Health
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

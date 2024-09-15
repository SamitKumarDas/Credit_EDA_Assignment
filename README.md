# Credit EDA Assignment

This repository contains an exploratory data analysis (EDA) assignment for credit risk assessment using loan application data. The goal of this analysis is to understand the distribution of different variables, identify patterns in loan applicants' characteristics, and explore factors associated with loan payment difficulties.

## Contents

- **Credit_EDA_Assignment.ipynb**: The Jupyter notebook containing the complete exploratory data analysis of the loan application dataset. This includes data cleaning, visualizations, and insights derived from the data.
- **Credit_EDA_Assignment_Presentation.pdf**: A PDF document summarizing the findings and visualizations from the EDA, providing a concise overview of the analysis.

## Key Analysis

1. **Income Distribution**: Analysis of the total income distribution among loan applicants, identifying income levels that are more common in the applicant pool.
2. **Occupation Distribution**: Examination of the types of occupations most applicants belong to, highlighting the prevalence of labor-intensive jobs.
3. **Educational Attainment**: Insights into the educational background of applicants and its correlation with loan payment difficulties.
4. **Income Type**: Distribution of loan applicants based on their income type, such as 'Working', 'Pensioner', and 'Commercial associate'.
5. **Real Estate Ownership**: Analysis of how owning real estate impacts loan payment difficulties.
6. **Goods Price**: Distribution of loan amounts based on the price of goods, identifying trends in the financial needs of applicants.
7. **Correlation Matrix**: Identification of key correlations between variables in the loan application dataset.
8. **Bivariate Analysis**: Exploration of relationships between pairs of variables to understand factors influencing loan payment difficulties.

## How to Use

- **Notebook**: The `.ipynb` file can be opened using Jupyter Notebook or any other compatible environment (e.g., JupyterLab, Google Colab). This file contains code, visualizations, and comments explaining the analysis process.
- **PDF**: The PDF document provides a summary of the findings for quick reference. It includes key visualizations and insights.

### Dataset Information

The dataset used in this analysis consists of three files that are included in this repository:

Link for the files -> https://drive.google.com/drive/folders/18Uv14-xsL-IGJ8ay3BebCfPsZVe4ePIH?usp=drive_link

1. **`application_data.csv`**: Contains detailed information about clients at the time of their loan application. It includes various attributes that help in understanding the client's financial situation and whether they have experienced payment difficulties.

2. **`previous_application.csv`**: Provides information about clients' previous loan applications, indicating whether they were Approved, Cancelled, Refused, or marked as an Unused offer.

3. **`columns_description.csv`**: A data dictionary that describes the variables present in the other datasets, providing explanations for each column to facilitate data analysis.

## Requirements

To run the notebook, the following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn

Install the libraries using:
```bash
pip install pandas numpy matplotlib seaborn



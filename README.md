# Road Accident Severity Analysis

This repository contains a Jupyter notebook for analyzing road accident severity using Python. The analysis explores various factors contributing to accident severity and suggests insights for mitigating risks and improving safety measures.

## Dataset

The dataset used in this analysis contains information about road accidents, including factors such as casualty severity, gender, age, location, and time of the accident. The dataset can be found in the `data/` directory.

## Analysis Overview

- The notebook begins with data exploration, including descriptive statistics and visualization of key variables.
- Imputation techniques such as KNN, Simple, and Iterative imputers are applied to handle missing values.
- Casualty severity is analyzed with respect to gender, age, pedestrian location, and urban vs. rural areas.
- Contrary findings, such as the unexpected relationship between driver age and accident severity, are discussed.
- Recommendations are provided for gathering additional data and enhancing the analysis.

## Requirements

To run the notebook locally, ensure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

Install the dependencies using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn

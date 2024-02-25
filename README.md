# COMPAS Recidivism Bias Analysis

## Overview
This repository contains a machine learning project focused on analyzing biases in the COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) dataset. The goal is to identify and assess potential biases in recidivism predictions across different racial groups using a decision tree classifier.

## Project Description
The COMPAS dataset is widely used to assess the likelihood of a convict's recidivism. However, it has been subject to scrutiny and debate due to potential biases against certain demographic groups, particularly in terms of race. This project aims to explore these potential biases by applying a decision tree model and evaluating its performance across different racial subgroups.

## Repository Structure
```
- data/                        # Folder containing the COMPAS dataset and any other data files
- notebooks/                   # Jupyter notebooks with detailed analysis
- src/                         # Source code for analysis, including data preprocessing and modeling
- results/                     # Generated output files, figures, and confusion matrices
- README.md                    # Description and summary of the project
- requirements.txt             # List of dependencies for reproducing the analysis
```

## Key Findings
- The decision tree model showed varying degrees of performance across different racial groups.
- Significant False Positives and False Negatives were observed, particularly between classes `1` and `-1`.
- The model’s predictions indicated potential biases, necessitating further investigation and refinement.

## Methodology
1. **Data Preprocessing**: The dataset was cleaned and prepared, involving handling missing values, encoding categorical variables, and feature engineering.
2. **Model Training and Evaluation**: A decision tree classifier was trained and evaluated, with performance metrics calculated for the overall model and for each racial subgroup.
3. **Bias Analysis**: Confusion matrices were generated for each racial subgroup to assess the model's fairness and accuracy.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## Running the Project
To replicate this analysis, clone the repository, install the dependencies listed in `requirements.txt`, and run the Jupyter notebooks in the `notebooks/` directory.

```
git clone https://github.com/elshadaik/COMPAS-Recidivism-Bias-Analysis.git
pip install -r requirements.txt
```

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is open-sourced under the [MIT License](LICENSE).

## Acknowledgements
Special thanks to all contributors and researchers who have worked on analyzing and highlighting issues in the COMPAS dataset.


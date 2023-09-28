# Patient Flow - Insights and Prediction
## Overview
Hospitals face a common challenge: managing the influx of patients in the emergency room and optimizing their waiting times. This project aims to address this issue by leveraging data to provide valuable insights and predictive capabilities. Our goal is to help hospitals enhance their ability to manage and reduce patient waiting times in the Emergency Department (ED).

Through data analysis and modeling, we seek to:

- Understand patterns in patient arrival and departure times.
- Identify factors that impact waiting hours.
- Develop models to forecast patient waiting times.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Content](#content)
- [Contact](#contact)

## Installation

1. **Clone the Repository:**
   ```
   git clone [repository_url]
   cd [repository_directory]
   ```

2. **Install Dependencies:**
   ```
   pip install -r {libraries listed below}
   ```

3. **Launch Jupyter Notebook:**
   ```
   jupyter notebook
   ```

4. **Open and Run Jupyter Notebooks:**
   - Navigate to the `notebooks/` directory.
   - Open the relevant Jupyter notebooks.

### Required Libraries (Python 3.9.3):

- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn


## Content

This repository includes three Jupyter notebooks, each serving a distinct purpose in the analysis of this project:

### 1. `processing.ipynb`

- **Purpose:** This notebook is dedicated to data preprocessing and cleaning tasks.
- **Usage:** Use it to clean, transform, and prepare your dataset for analysis and modeling.
- **Instructions:** Follow the step-by-step instructions and code cells to perform data preprocessing tasks such as :
    - handling missing values
    - imputation of missing data
    - removing redundant features

### 2. `exploration_and_analysis.ipynb` ★ HIGHLIGHT OF THE PROJECT

- **Purpose:** Explore and analyze your data using this notebook.
- **Usage:** Utilize this notebook to gain insights, visualize trends, and uncover patterns in your dataset.
- **Instructions:** Follow the notebook's instructions and code cells to create exploratory data visualizations, intepretation of trends in training variables, how they impact the waiting time of ER patients. A few examples of the features analysed are:
    - Patient waiting times
    - Age of patients
    - Triage Priority
    - Diagnosis by season
    - Admissions by season
    - Day of the week

### 3. `modelling_and_evaluation.ipynb`

- **Purpose:** Develop and evaluate machine learning models for your project.
- **Usage:** Use this notebook for tasks related to model building, training, and evaluation.
- **Instructions:** Follow the provided instructions and code cells to select, train, and evaluate models. Explore hyperparameter tuning and model evaluation metrics.

Each notebook is designed to guide you through specific stages of your data analysis project.


## Contact

For inquiries or feedback, reach out through the following channels:

- Email: heonjae.shin00@mail.com
- Linkedin: https://www.linkedin.com/in/heonjae-shin-933a4a208/
- GitHub: [Your GitHub Profile](https://github.com/heonjaes)
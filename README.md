
# Loan Approval Prediction

This repository contains the code and analysis for predicting loan approval based on various applicant features. The project utilizes a variety of machine learning models, including Logistic Regression and K-Nearest Neighbors (KNN), to classify whether a loan will be approved or denied.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Model Performance](#model-performance)
- [Fine-Tuning](#fine-tuning)
- [Conclusions](#conclusions)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The objective of this project is to build a model that predicts whether a loan will be approved or not based on a set of applicant-related features. The project explores the application of various machine learning techniques and evaluates their performance.

## Dataset
The dataset used for this project includes various features of loan applicants such as:
- Applicant Income
- Co-Applicant Income
- Loan Amount
- Credit History
- Gender, Marital Status, etc.

The dataset is stored in a CSV file named `Week-1.csv`, which is read into the project using pandas.

## Libraries Used
The following libraries are used in this project:
- `numpy`
- `pandas`
- `matplotlib`
- `missingno`
- `seaborn`
- `scipy`
- `sklearn`
- `imblearn`

## Data Preprocessing
1. **Handling Missing Values:** Missing values are filled using the mode or mean of the columns.
2. **Encoding Categorical Data:** Categorical data is encoded using one-hot encoding.
3. **Scaling:** Features are scaled using `MinMaxScaler` to normalize the data.
4. **Balancing the Dataset:** The dataset is balanced using SMOTE (Synthetic Minority Over-sampling Technique).

## Exploratory Data Analysis (EDA)
The EDA section includes:
- Analysis of the target variable distribution.
- Examination of applicant demographics, income distributions, loan amounts, and other features.
- Investigation of correlations between different variables.
- Visualization of data distributions and outliers.

## Modeling
Two machine learning models are implemented:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

The models are trained on the preprocessed data, and their performance is evaluated on the test set.

## Model Performance
The performance of the models is evaluated using:
- Accuracy
- Classification Report
- Confusion Matrix

The accuracy of each model is compared, and the best-performing model is identified.

## Fine-Tuning
Further model tuning can be performed to optimize performance. This may include adjusting hyperparameters, trying different feature selection methods, or exploring other machine learning algorithms.

## Conclusions
Key insights and observations from the analysis include:
- Distribution of loan approvals across different demographic groups.
- Impact of applicant and co-applicant income on loan approval.
- Influence of credit history and loan amount on approval chances.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loan-approval.git
   ```
2. Navigate to the project directory:
   ```bash
   cd loan-approval
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis:
   ```bash
   python loan_approval_analysis.py
   ```

## Contributing
Contributions are welcome! If you have any ideas for improvements or find any issues, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

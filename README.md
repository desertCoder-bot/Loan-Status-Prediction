# Loan Prediction Project

## Overview

This project aims to predict the loan eligibility of applicants based on various features like gender, marital status, education, number of dependents, income, loan amount, credit history, and property area. The project uses machine learning techniques to build a predictive model.

## Dataset

The dataset used in this project contains information about past loan applicants and their loan status (approved or not). The dataset includes the following columns:

- **Loan_ID**: Unique Loan ID
- **Gender**: Male/Female
- **Married**: Applicant married (Y/N)
- **Dependents**: Number of dependents
- **Education**: Applicant Education (Graduate/Undergraduate)
- **Self_Employed**: Self-employed (Y/N)
- **ApplicantIncome**: Applicant income
- **CoapplicantIncome**: Coapplicant income
- **LoanAmount**: Loan amount in thousands
- **Loan_Amount_Term**: Term of loan in months
- **Credit_History**: Credit history meets guidelines
- **Property_Area**: Urban/Semi-Urban/Rural
- **Loan_Status**: Loan approved (Y/N)

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- scikit-learn

## Installation

1. Clone the repository:

```bash
git clone https://github.com/desertCoder-bot/Loan-Status-Prediction.git
```

2. Navigate to the project directory:

```bash
cd Loan-Predection
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook
```

2. Open `Loan_Predection.ipynb` and run the cells to execute the code.

## Project Steps

1. **Data Loading**: Load the dataset into a pandas DataFrame.
2. **Data Exploration**: Explore the dataset to understand its structure and contents.
3. **Data Cleaning**: Handle missing values by dropping rows with missing data.
4. **Data Preprocessing**: Encode categorical variables and split the data into features and labels.
5. **Model Training**: Train a Support Vector Machine (SVM) model on the training data.
6. **Model Evaluation**: Evaluate the model's performance using accuracy score.

## Results

The model's performance is evaluated using the accuracy score, which measures the proportion of correctly predicted loan statuses.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. Any contributions, whether it's fixing bugs, improving documentation, or adding new features, are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact the repository owner at [desertCoder-bot](https://github.com/desertCoder-bot).

## Acknowledgements

- Dataset: [Kaggle Loan Prediction Dataset](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)
- Libraries: pandas, numpy, seaborn, scikit-learn

Happy coding! 😎

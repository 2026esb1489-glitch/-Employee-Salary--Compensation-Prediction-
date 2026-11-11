# Employee Salary and Compensation Prediction
AI101 Project - Employee Salary and Compensation Prediction Using Multiple Linear Regression

# Project Description

This AI101 project aims to predict employee salaries using Multiple Linear Regression, a supervised machine learning algorithm.

The model uses employee-related attributes to estimate annual salary.

# Objectives

- Understand Multiple Linear Regression.
- Collect and clean employee salary data.
- Perform data preprocessing.
- Train and test a machine learning model.
- Predict employee salaries.
- Evaluate model performance.

# Dataset

Dataset Source: [Kaggle – Latest Data Science Job Salaries 2024](https://www.kaggle.com/datasets/saurabhbadole/latest-data-science-job-salaries-2024)

Number of Rows: 93,597

Number of Columns: 11

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

# Team Members

| Member Name | Entry Number | Role |
|---|---|---|
|Puthineedi Vyshnavi|2026ESB1489| Documentation Lead|
|Amogh Chavan|2026AIB1008| Execution Lead|
|Livteshwar Singh Sandhu|2026MCB1538| PPT Lead|
|Kshitiz Kumar|2026EEB1369| Video Lead|
## Setup and Execution

### Prerequisites
- Python installed
- Git installed
- Jupyter Notebook

### 1. Clone the Repository

```bash
git clone https://github.com/2026esb1489-glitch/Employee-Salary--Compensation-Prediction-.git
cd Employee-Salary--Compensation-Prediction-
```

### 2. Create a Virtual Environment

For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

For macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Required Libraries

```bash
python -m pip install -r requirements.txt
```
### 4. Install ipykernel
python -m pip install ipykernel

### 5. Register Jupyter kernel
python -m ipykernel install --user --name my_test --display-name "TEST”


and add this



Open `AI Project Commit-1.ipynb` and execute the notebook cells sequentially.

### Expected Output

- Dataset loading and exploration
- Data preprocessing
- Multiple Linear Regression model training
- Salary predictions
- Model evaluation metrics
- Actual vs Predicted Salary visualization
  
# Project Structure

The project is organized into different files to make the work easier to understand and manage.

- `README.md` – Contains the project introduction, objectives, dataset details, and team information.
- `DataScience_salaries_2025.csv` – Contains the employee salary dataset used for the project.
- `AI Project Commit-1.ipynb` – Jupyter Notebook used for data analysis and model development.
- `requirements.txt` – Lists the Python libraries required to run the project.

# Results

The project focuses on predicting employee salaries using Multiple Linear Regression. The dataset was explored and preprocessed to prepare it for model training.

After training and testing the model, we evaluated its performance using R² Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

We also created an Actual vs Predicted Salary graph using Matplotlib to compare the predicted salaries with the actual salary values.

The results show how Multiple Linear Regression can be used for salary prediction. The model's performance can be improved further with better data preprocessing and feature selection.


# Presentation and Video

PPT Link: To be added

Video Link: To be added

   
## AI-use disclosure
    
    ChatGPT was used to assist with understanding the project and preparing initial practice code
    Claude: helped write the train/test split, evaluation and plot cells; we ran and checked the output.

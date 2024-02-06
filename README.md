# Credit Risk Model for SME Lending

## Project Overview
This project aims to develop a predictive model to assess the creditworthiness of Small and Medium Enterprises (SMEs) applying for loans. By analyzing historical loan data, including repayment history, default rates, and borrower information, we seek to identify patterns and variables that significantly influence credit risk. The outcome will support lenders in making informed decisions, thereby optimizing the credit lifecycle and enhancing the lending process.

## Getting Started

### Prerequisites
- Python 3.x
- pip or conda

### Installation
1. Clone the repository to your local machine:

`git clone https://github.com/yourusername/sme-credit-risk-model.git`

2. Navigate to the project directory:

`cd sme-credit-risk-model`

3. Creata a virtual environment:

- For conda:
    ```
    conda create --name creditrisk python=3.8
    conda activate creditrisk
    ```
- For venv:
    ```
    python -m venv creditrisk
    source creditrisk/bin/activate # On Windows use `creditrisk\Scripts\activate`
    ```

4. Install the required dependencies:

`pip install -r requirements.txt`

### Running the Project
1. Start by running the data preprocessing script:

`python scripts/data_processing.py`

2. Proceed with the exploratory data analysis:

`python scripts/eda.py`

3. Train the model using:

`python scripts/train_model.py`

4. Evaluate model performance with:

`python scripts/evaluate_model.py`

### Project Structure

- **data/**: Directory for storing datasets.
- **scripts/**: Python scripts for data preprocessing, EDA, model training, and evaluation.
- **models/**: Trained model artifacts.
- **notebooks/**: Jupyter notebooks for exploratory data analysis and prototype modeling.
- **requrirements.txt**: List of packages required to run the project.

### Methodology
- Data Preprocessing: Cleaning data, handling missing values, and feature engineering.
- Exploratory Data Analysis (EDA): Analyzing the data to find patterns, trends, and correlations.
- Feature Selection: Identifying the most important variables that affect credit risk.
- Model Development: Training and tuning different machine learning models to predict creditworthiness.
- Model Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, and AUC-ROC.

### Tools and Libraries Used
- Data Manipulation: pandas, NumPy
- Machine Learning: scikit-learn
- Data Visualization: matplotlib, seaborn
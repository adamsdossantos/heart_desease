# Heart Desease Prediction with Logistic Regression


## 1. Project Overview

This project implements a Logistic Regression model for [predicting heart disease. Logistic Regression is a statistical model used for binary classification tasks, estimating the probability that an instance belongs to a particular class.


## 2. Features
- **Data Preprocessing**: Data cleaning, feature engineering, handling missing values, and splitting into training and testing sets.
- **Model Training**: Training a Logistic Regression model using scikit-learn.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC curve.
- **Visualization**: Visualization of the decision boundary and the ROC curve.



## 3. Project Structure
    ├── heart_desease_data.csv      # Dataset file 
    ├── heart_desease.ipynb         # Jupyter notebook with end-to-end implementation
    ├── README.md                   # Project documentation
    ├── requirements.txt            # Python dependencies
    └── .gitignore                  # Files to be ignored in version control

## 4. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/heart_desease.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook heart_desease.ipynb
```
## 5. Usage

Open the heart_desease.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from the 'heart_desease_data.csv' and perform necessary preprocessing like handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Train a Logistic Regression model with adjustable hyperparameters such as regularization strength.
- **Model Evaluation**:  Evaluate the model using metrics like accuracy, precision, recall, F1-score, and plot the ROC curve.
- **Visualization**:  Visualize the decision boundary and the ROC curve


## 6. Results in Test

| Metric    | Value |
|-----------|-------|
| Accuracy  | 80%   |
| Precision | 80%   |
| Recall    | 80%   |
| F1-Score  | 80%   |
| ROC-AUC   | 80%    |


## 7. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 8. License

This project is licensed under the MIT License - see the LICENSE file for details.








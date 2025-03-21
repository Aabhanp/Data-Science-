# Iris Flower Classification

## Project Overview

This project aims to classify Iris flowers into three species (**Setosa, Versicolor, and Virginica**) using machine learning models. The dataset consists of sepal and petal length/width measurements.

## Dataset

- Source: [Iris Dataset](https://raw.githubusercontent.com/uiuc-cse/data-fa14/gh-pages/data/iris.csv)
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target: Species (Setosa, Versicolor, Virginica)

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iris-classification.git
   cd iris-classification
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python iris_classification.py
   ```

## Models Used

- **Random Forest Classifier**
- **Logistic Regression**
- **Decision Tree Classifier**
- **Support Vector Machine (SVM)**

## Model Evaluation

| Model                  | Accuracy |
| ---------------------- | -------- |
| Random Forest          | X.XX%    |
| Logistic Regression    | X.XX%    |
| Decision Tree          | X.XX%    |
| Support Vector Machine | X.XX%    |

## Feature Importance Analysis

Feature importance is determined using the Random Forest model to identify which features contribute most to classification.

## Hyperparameter Tuning

Hyperparameter tuning is applied to the **SVM model** using GridSearchCV to optimize performance.

## Repository Structure

```
├── iris_classification.py  # Main script
├── README.md               # Project documentation
├── requirements.txt        # Dependencies
```

## Future Enhancements

- Add deep learning models
- Improve feature engineering
- Deploy as a web app

## Author

Aabha Puranik


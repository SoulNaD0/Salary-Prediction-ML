# Salary Prediction Analysis

## Overview
This project predicts salaries based on demographic and employment features using various regression models. The dataset includes information such as age, education level, years of experience, country, race, and job title.

## Models Used
- Linear Regression
- Polynomial Regression
- K-Nearest Neighbors Regression
- Random Forest Regression
- Support Vector Regression

## Results
The **Random Forest Regression** model performed the best for salary prediction, with the lowest RMSE (**12157.69**) and highest R² score (**0.946**). This model is recommended for future predictions.

### Model Comparison
| **Model**                  | **Test RMSE** | **Test R²** |
|----------------------------|---------------|-------------|
| Linear Regression          | 22647.75      | 0.813       |
| Polynomial Regression      | 19210.03      | 0.866       |
| KNN Regression             | 15689.04      | 0.910       |
| Random Forest Regression   | 12157.69      | 0.946       |
| Support Vector Regression  | 30956.66      | 0.651       |

## How to Run
1. Clone the repository.
2. Open the Jupyter Notebook `Salary_Prediction_Analysis.ipynb` and run the cells.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

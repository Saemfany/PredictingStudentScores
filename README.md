# Predicting Student Scores Based on Study Hours

## Overview
This project aims to predict student scores based on the number of hours studied using machine learning models. The models explored in this project are Linear Regression, Decision Tree, and Random Forest. The dataset contains the number of hours students studied and their corresponding scores. We evaluate and compare the performance of these models to determine which provides the best predictions.

## Dataset
The dataset contains the following features:
- `Hours (x)`: The number of hours students studied.
- `Scores (y)`: The scores achieved by the students.

Example data:
| Hours | Scores |
|-------|--------|
| 2.5   | 21     |
| 5.1   | 47     |
| 3.2   | 27     |

## Models Used
1. **Linear Regression**: A statistical method for modeling the relationship between a dependent variable and one or more independent variables.
2. **Decision Tree**: A non-parametric supervised learning method used for classification and regression.
3. **Random Forest**: An ensemble learning method that operates by constructing multiple decision trees and outputting the average prediction of the individual trees.

## Project Structure
- [PredictingStudentScores.ipynb](https://github.com/Saemfany/PredictingStudentScores/blob/fdc593e5685941e8d29d609fa24f98c8cf49a7ac/PredictingStudentScores.ipynb): Contains Jupyter notebooks with the code for training and evaluating the models.
- [student_scores.csv](https://github.com/Saemfany/PredictingStudentScores/blob/fdc593e5685941e8d29d609fa24f98c8cf49a7ac/student_scores.csv): Contains the dataset used for the project.
- [README.md](https://github.com/Saemfany/PredictingStudentScores/blob/7a50e49c6efdff14b5d0c4d84565be668ce09b0c/README.md): Project documentation.
- report.pdf: Detailed report with model explanations and performance metrics.

## Evaluation Metrics
The models were evaluated based on the following metrics:
- Mean Squared Error (MSE)
- R² Score

## Results
- **Linear Regression**:
  - Mean Squared Error (MSE): 18.94
  - R-squared (R²): 0.9678
  
- **Decision Tree**:
  - Mean Squared Error (MSE): 31.70
  - R-squared (R²): 0.9461
  
- **Random Forest**:
  - Mean Squared Error (MSE): 13.05
  - R-squared (R²): 0.9778
  
The Random Forest model performed best in terms of accuracy and prediction stability, followed by Decision Tree and Linear Regression.

## Conclusion
This project demonstrates how different machine learning models can be applied to predict student scores based on study hours. Random Forest outperformed the other models, making it a suitable choice for this dataset.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the [MIT License](https://github.com/Saemfany/PredictingStudentScores/blob/6b6461718ab48e3a84ef896c541e37fd876e0cf0/LICENSE).

## Contact Me
E-mail: saemfany@gmail.com

LinkedIn: [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/syamsul-rizal-fany-410bb6325/)

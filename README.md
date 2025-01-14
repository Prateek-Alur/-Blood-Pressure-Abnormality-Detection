# -Blood-Pressure-Abnormality-Detection

## Project Overview
This project focuses on detecting blood pressure abnormalities using machine learning techniques. The dataset includes various features related to patients' health, and the goal is to predict whether a patient has normal or abnormal blood pressure.

## Key Steps
1. **Data Preprocessing**: Cleaned and prepared the dataset for modeling, handling missing values and ensuring data consistency.
2. **Feature Selection**: Selected relevant features to improve model performance and reduce complexity.
3. **Data Scaling**: Applied scaling techniques to ensure that all features contribute equally to the model.
4. **Modeling**: Implemented and compared multiple machine learning algorithms, including:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
5. **Hyperparameter Tuning**: Optimized model performance using hyperparameter tuning to enhance accuracy.
6. **Ensemble Method**: Applied **AdaBoost** on the **Random Forest** model, achieving the highest accuracy of **87.6%**.

## Results
- The model achieved an accuracy of **87.6%** using AdaBoost on the Random Forest algorithm.
- The results indicate effective classification of blood pressure abnormalities, with good predictive performance after model optimization.

## Technologies Used
- **Python**: For data processing, modeling, and evaluation.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib/Seaborn**: For data visualization.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blood-pressure-abnormality-detection.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook/script for data preprocessing, model training, and evaluation.

## Conclusion
The project successfully demonstrated the use of machine learning algorithms to predict blood pressure abnormalities. AdaBoost with Random Forest was the most effective approach, achieving the highest accuracy.


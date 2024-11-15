### README for Student Dropout Prediction Project

---

# **Student Dropout Prediction Using Machine Learning**

This project aims to predict student dropout rates using machine learning techniques based on various datasets containing academic, financial, and demographic factors. By leveraging predictive analytics, this project seeks to provide insights that can assist educational institutions in identifying at-risk students and improving retention rates.

## All sources of data for the project:

A. Dataset: Predict students' dropout and academic success

Description: This dataset provides a comprehensive view of students enrolled in various undergraduate degrees offered at a higher education institution.

Source: `Kaggle.`

Link: (https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention)

B. Dataset: Predict Students' Dropout and Academic Success

Description: Provides a dataset containing information about students' academic performance and dropout indicators.

Source: `UCI Machine Learning Repository.`

Link: (https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)

C. Research Paper - Machine Learning Model for Predicting Student Dropout

Description: Focuses on dropout prediction in Tanzania, Kenya, and Uganda using machine learning.

Source: `IEEE Xplore.`

Link: https://ieeexplore.ieee.org/document/9570956

---

## **Project Features**

1. **Data Preprocessing**:
   - Normalized all numerical features to bring them to a consistent scale.
   - Encoded the target variable (`Dropout`, `Enrolled`, `Graduate`) for machine learning compatibility.
   - Addressed missing values and outliers to ensure data integrity.

2. **Feature Engineering**:
   - Identified key predictors such as financial status, marital status, and academic performance.
   - Ranked features based on their importance using correlation and feature importance metrics.

3. **Model Development**:
   - Implemented machine learning models like Logistic Regression, Random Forest, and XGBoost.
   - Evaluated models using metrics like accuracy, precision, recall, and F1 score.
   - Used hyperparameter tuning to optimize model performance.

4. **Bias Mitigation**:
   - Ensured fair representation of demographic groups in the dataset.
   - Applied techniques like re-weighting and fairness constraints to reduce bias in predictions.

5. **Visualization**:
   - Created visualizations to analyze trends and relationships between key features and dropout rates.
   - Generated comparative plots for model performance evaluation.

Check [THE NOTEBOOK]() for more details

---

## **Installation and Setup**

1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedAYasin/ML-Pipeline_Data-Preprocessing.git
   cd ML-Pipeline_Data-Preprocessing
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Notebook:
   ```bash
   Jupyter Notebook
   ```

---

## **How to Use**

1. **Preprocess the data**: Prepare the dataset by normalizing features and encoding the target.
2. **Train models**: Use the provided scripts to train and test machine learning models.
3. **Analyze results**: Explore generated plots and evaluation metrics to understand model performance.
4. **Predict new data**: Extend the project by deploying the model to predict dropout probabilities for new student data.

---

## **Future Improvements**

- Incorporate additional features like prior academic history.
- Explore advanced algorithms like Neural Networks.
- Implement a user-friendly interface for real-time predictions.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

 -----------------         `©2024 The African Leadership University (ALU)`      ---------------------------------

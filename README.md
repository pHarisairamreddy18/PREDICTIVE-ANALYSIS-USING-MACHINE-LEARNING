# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY* :CODTECH IT SOLUTIONS

*NAME* :PULLA HARI SAIRAM REDDY

*INTERN ID* :CT06DF1059

*DOMAIN* :DATA ANALYTICS

*DURATION* :6 WEEKS

*MENTOR* :NEELA SANTHOSH KUMAR

# Heart Disease Classification using Random Forest Classifier

This project focuses on developing a machine learning model that predicts the presence of heart disease in patients by analyzing clinical features. Using the Random Forest Classifier, the model learns from historical patient data to classify individuals as either having heart disease or not.

*Data Preparation and Preprocessing*

The dataset was first loaded and examined for quality and completeness. Visual exploratory analysis included plotting a correlation heatmap to detect relationships between variables and violin plots to identify potential outliers. No significant features were removed, and outliers were considered not impactful enough to exclude. The dataset was then split into training and testing subsets in a 70:30 ratio for model development and evaluation.

*Feature Selection*

To improve model performance and reduce complexity, correlation analysis was used to identify and confirm relevant features. Since no highly correlated or redundant features were found, all existing features were retained. This ensures the model considers all available clinical indicators during training.

*Model Training and Evaluation*

A Random Forest Classifier with a specified maximum tree depth was trained on the scaled training data. This ensemble method aggregates decisions from multiple trees to enhance prediction accuracy and prevent overfitting. Model performance was evaluated using accuracy score and confusion matrix on the test dataset. The classifier achieved an accuracy of 83.5%, indicating strong predictive ability. Additionally, ROC curve analysis provided insights into the model’s discriminative power between classes.

*Tools Used*

* *Programming Language:* Python
* *Libraries:*

  * Pandas for data manipulation
  * NumPy for numerical operations
  * Seaborn and Matplotlib for data visualization
  * Scikit-learn for machine learning model implementation and evaluation
* *Development Environment:* Google Colab, which offers cloud-based Jupyter notebooks with free GPU support
* *Version Control:* Git and GitHub for source code management and collaboration

*Dataset Description*

The dataset used in this project is the *Cleveland Heart Disease dataset*, publicly available on Kaggle. It contains patient records with 14 clinical features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, and more. The target variable indicates the presence (1) or absence (0) of heart disease. This dataset is widely used for benchmarking classification algorithms in medical diagnostics.

*Real World Applications*

* *Medical Diagnosis Support:* Assists healthcare professionals in early detection of heart disease, enabling timely intervention.
* *Risk Assessment Tools:* Can be integrated into clinical software for personalized risk evaluation based on patient data.
* *Public Health Analytics:* Helps in identifying patterns and risk factors at the population level to inform policy and preventive programs.
* *Educational Purposes:* Serves as a practical example for students and researchers learning machine learning in healthcare.
* *AI-powered Healthcare Solutions:* Forms the basis for developing intelligent systems that support decision-making in hospitals and clinics.

*Conclusion*

The Random Forest model provides a strong baseline for heart disease prediction using clinical features. While results are promising, there is scope for enhancing accuracy through further feature engineering, parameter tuning, and exploring more advanced algorithms. This project showcases how machine learning techniques can be applied effectively to healthcare data for diagnostic support.

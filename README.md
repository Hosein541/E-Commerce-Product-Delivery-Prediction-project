## Project Overview
The aim of this project is to predict whether products from an international e-commerce company will reach customers on time or not. Additionally, the project analyzes various factors influencing product delivery and studies customer behavior. The company primarily sells electronic products.

## Summary and Conclusion 

1. Initial Data Exploration: Conducted a comprehensive review of the dataset to understand its structure and characteristics.
2. Data Visualization: Performed exploratory data analysis to gain deeper insights into the data patterns and distributions.
3. Data Preprocessing:
   - Standardization: Normalized numerical features to ensure consistent scale across variables.
   - Categorical Encoding: Implemented label encoding for categorical variables to prepare them for machine learning algorithms.
4. Model Evaluation: Initial assessment revealed suboptimal model accuracy.

### Model Performance Enhancement

To address the accuracy issues, we implemented the SMOTE (Synthetic Minority Over-sampling Technique) method.

### SMOTE Implementation

By employing the SMOTE method, we significantly increased the number of samples for minority classes. This resampling technique led to a substantial enhancement in the model's predictive accuracy. The rebalanced dataset resulted in improved performance in predicting fraudulent warranty claims.

### Key Findings

1. SMOTE effectively addressed the class imbalance problem in our dataset.
2. The balanced data led to a more robust and accurate prediction model.
3. The model's ability to identify fraudulent warranty claims improved considerably.

### Conclusion

These findings demonstrate that utilizing class balancing techniques like SMOTE can significantly enhance the performance of fraud prediction models. We recommend employing SMOTE and machine learning models trained using this method for analyzing and predicting warranty claims fraud, as it can lead to improved accuracy and predictive capability of the models.

### Developer Information

*Developed by Hosein Mohammadi*

GitHub : https://github.com/Hosein541

LinkedIn : https://www.linkedin.com/in/hosein-mohammadi-979b8a2b2/

Gmail : Huseinmohammadi83@gmail.com

1. Contextualization: Within the healthcare domain, the accurate assessment of fetal health is of paramount importance. This involves navigating through substantial datasets, and the optimization of these datasets plays a crucial role in enhancing the performance of predictive models. In this project, the primary focus is on utilizing Dimensionality Reduction (DR) techniques to streamline datasets, with the ultimate goal of improving the accuracy of predictive models for fetal health assessment.

2. Problem: Predictive modeling in fetal health encounters challenges due to the intricate nature of the datasets. Issues like high dimensionality, non-normal distribution, and the presence of outliers can impede the efficacy of machine learning models. A systematic approach is essential to address these challenges and elevate the accuracy of models critical for assessing fetal health.
3. Proposed approach: The project initiates with a meticulous analysis of the dataset, followed by rigorous data preprocessing. The confirmation of the absence of missing and duplicate values is coupled with addressing non-normal distribution through normalization via Min-Max scaling. Mitigating outliers using the Interquartile Range (IQR) capping method ensures the robustness of the dataset. Subsequent application of feature selection techniques, such as f_regression, L1 regularization, and Recursive Feature Elimination (RFE), aids in identifying the most relevant features. To further refine the dataset, feature extraction techniques like Linear Correlation Analysis (LCA) and Principal Component Analysis (PCA) are employed. The chosen models for assessment—Logistic Regression, Support Vector Machine (SVM), and Quadratic Discriminant Analysis—account for the reduced and optimized dataset.

4. Impact: Anticipated impacts of this approach include a marked improvement in the accuracy and efficiency of fetal health assessment models. Systematically addressing data quality, distribution, and dimensionality issues is expected to yield more reliable predictions. This has the potential to profoundly impact clinical decision-making, empowering healthcare practitioners with more informed choices and possibly leading to better outcomes for fetal health.


**Objective:**
The overarching objective of this project is to enhance the predictive capabilities of models assessing fetal health by leveraging advanced data preprocessing and dimensionality reduction techniques. The focal point is on optimizing information within the dataset, thereby improving the accuracy of models crucial for fetal health evaluation.


**Dataset:**
The dataset comprises 2126 records of fetal health data, each containing 29 features encompassing fetal heart rate (FHR), uterine contractions, and fetal movements. The target variable categorizes fetal health as normal, suspect, or pathological. After confirming no missing or duplicate values, the dataset's non-normal distribution is addressed through normalization, and outliers are handled via IQR capping. The dataset is then refined using feature selection and extraction techniques to create a more streamlined and informative dataset for modeling.



**Approach:**
The project employs a systematic approach, commencing with dataset analysis and preprocessing, followed by addressing non-normal distribution and outliers. Feature selection techniques, including f_regression, L1 regularization, and RFE, are employed. Feature extraction techniques, such as LCA and PCA, further refine the dataset. The final dataset is utilized with Logistic Regression, SVM, and Quadratic Discriminant Analysis models to assess fetal health.

**Conclusions:**
In conclusion, the proposed approach outlines a comprehensive methodology for optimizing fetal health datasets and enhancing the accuracy of predictive models. By systematically addressing issues related to data quality and dimensionality, the project aims to contribute to the development of more robust tools for fetal health assessment. The integration of advanced techniques in data preprocessing and dimensionality reduction establishes a foundation for enhanced predictive modeling in the healthcare domain.


**Machine Learnnig Projects**

**1. Creditcard:**
   - Machine Learning Classification Algorithms: Models such as RandomForest, Logistic Regression, SVM, etc., are trained on historical transaction data to learn patterns of fraud.

   - Data Imbalance Handling: Fraud cases are rare compared to normal ones, so techniques like SMOTE, undersampling, or class weighting are often applied.
     
     
**2. Food Delivery (Customer Sagmantation):**
   
   -  K-Means → Segments customers into K predefined clusters (good for clear, well-separated groups).

   - DBSCAN → Finds clusters based on density, detects niche groups & outliers, no need to predefine K.

   - PCA → Reduces high-dimensional data into fewer components for better clustering & visualization.
     

**3. Diebities Risk:**
   - Data Preprocessing → Handled missing/invalid values (0s → NaN → median imputation), scaled features using StandardScaler.

   - Class Imbalance → Balanced data using SMOTE to avoid bias toward majority class.

   - Exploratory Analysis → Used histograms, scatter plots, pairplots, and heatmaps to detect patterns, correlations, and outliers.

   - Model Training (KNN) →

        Tested k=1 to 14.

        Found best k=8 with ~78% accuracy.

        Showed bias-variance tradeoff.

  - Curse of Dimensionality (Implied) → Scaling & PCA (if applied) help mitigate performance issues in high-dimensional data.

  - Evaluation Metrics → Used accuracy, precision, recall, F1, ROC-AUC for a complete model assessment.

  - Final model: Accuracy ~0.78, Precision ~0.67, Recall ~0.73, F1 ~0.70.
    
    
**4. Predicting Online Purchase Intent:**
   - Preprocessing → Encode categorical variables, handle booleans, standardize features.

   - Data Split → Stratified sampling for balanced train/test sets.

   - Baseline Model → Train & tune KNN (bias-variance tradeoff).

   - PCA → Reduce dimensions, improve efficiency.

   - Model Comparison → KNN vs Logistic Regression, Decision Tree, Random Forest.

   - Evaluation → Use accuracy curves, confusion matrix, ROC curves, precision, recall, F1, ROC-AUC.

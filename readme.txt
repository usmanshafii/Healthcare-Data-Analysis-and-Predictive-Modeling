Conducted data preprocessing on a healthcare dataset to prepare it for machine learning analysis.
Removed irrelevant features (RecordID, hospital_id, icu_id) and handled multicollinearity.
Performed exploratory data analysis (EDA) using pandas_profiling to gain insights into the dataset's characteristics.
Employed one-hot encoding to transform categorical variables into a numerical format.
Applied Min-Max scaling to normalize numerical features for consistent model training.
Utilized SimpleImputer to impute missing values separately for numerical and categorical columns.
Built a predictive model for hospital mortality using the Random Forest Classifier.
Evaluated the model's performance using Receiver Operating Characteristic (ROC) analysis and Area Under the Curve (AUC).
Conducted k-fold cross-validation to assess the model's generalization performance with .92 accuracy.
Established baseline predictions using random guessing and measured the model's superiority.
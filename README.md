</h1>Voter Turnout Prediction Report</h1>

This project aimed to predict voter turnout for the November 2014 General Election using machine learning techniques. The dataset included approximately 50,000 voter records with 39 features, encompassing demographic, socioeconomic, and historical voting behavior data. After preprocessing, feature engineering, and model selection, the LightGBM classifier emerged as the best-performing model, achieving an accuracy of 0.9392, an AUC-ROC score of 0.9475, and an F1-Score of 0.5902. Hyperparameter tuning further optimized the model, and feature importance analysis revealed the top 20 key predictors, including age, socioeconomic index, g_pca (precinct turnout PCA component), and past voting behavior features like vh12p and vh10p. The final predictions, exported to a CSV file, can be used for targeted voter engagement strategies.

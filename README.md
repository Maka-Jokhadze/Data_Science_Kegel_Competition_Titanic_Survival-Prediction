# Kegel-Competition-Titanic-Survival-
The Titanic Survival competition involves predicting passenger survival based on a training dataset with known outcomes. The goal is to determine survival for a test dataset. 
Introduction


The Titanic sank on April 15, 1912, with a survival rate of 32%. Insufficient lifeboats were a major factor in the high death toll. Survival likelihood varied, with women, children, and the upper-class having better chances.
![image](https://github.com/user-attachments/assets/600ef335-8707-439c-8276-e170632d0f81)

Data Exploration:

My project begins with loading data from CSV files using the pandas library, segregating the data into train and test datasets. These datasets contain crucial information about the Titanic passengers, forming the foundation of my analysis.

 Visualize distributions of key features like age, sex, passenger class , embarking destination  and fare, also siblings and parent/children (merged into family size),  revealed who had higher chance to survive ( Pic .1). This helped me uncover trends and identify outliers.

 Explore relationships between different variables, potentially revealing correlations that could impact survival predictions.
![image](https://github.com/user-attachments/assets/d8ca6661-a622-4fda-b419-94a8bd530cb5)

My project involves rigorous model testing to determine the best approach for predicting passenger survival on the Titanic. I evaluated with machine learning models XGBoost and Logistic Regression. The culmination of my efforts is a model (Logistic Regression) , showcasing its ability to make accurate predictions, with an impressive : 
Accuracy: 83.72%,  Precision: 83.48%,   Recall: 68.09% , F1 Score: 75% .

XGBoost is ideal for capturing non-linear relationships and handling complex, large datasets efficiently. Logistic Regression is simpler, interpretable, and great for binary classification and as a baseline model. Using both allows comparison of performance and insight into data patterns . The XGBoost appeared better for my model, I selected ML model with higher accuracy percentage, Logistic Regression had lower accuracy percentage. 
![image](https://github.com/user-attachments/assets/9cacbf63-7bc8-42c2-bb48-086977a9f621)

Results

At a predictive ‘Kegel’ Accuracy of  85.78 %, my model demonstrates its potential to forecast Titanic passenger survival effectively. 
This project not only illustrates the practical application of machine learning techniques on historical data but also provides insights into the influential factors behind survival rates during the Titanic disaster.
![image](https://github.com/user-attachments/assets/c7f15f5e-7695-4f80-9da4-642bf22f6b5b)


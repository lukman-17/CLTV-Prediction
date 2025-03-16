# CLTV-Prediction
This CLTV Prediction App is a web-based tool built with Streamlit that predicts customer lifetime value based on demographics and policy details. The model is trained using Random Forest and preprocessed with StandardScaler for accuracy. Users can enter details, and the app provides instant predictions using the trained model.

In this project, I focused on predicting Customer Lifetime Value (CLTV) using machine learning. The first step involved collecting and understanding the dataset, followed by performing **Exploratory Data Analysis (EDA)** to gain insights and identify key variables that influence CLTV. Through EDA, I examined data distributions, handled missing values, and identified outliers to ensure a clean dataset for model training.  

One major challenge was that the CLTV variable had a **skewed distribution**, which could impact model performance. To address this, I applied **log transformation** to normalize the distribution, making it more suitable for machine learning models. This transformation helped improve prediction accuracy and model stability.  

I implemented and tested multiple regression models, including **Random Forest, Decision Tree Regressor, Random Forest Regressor, XGBoost, AdaBoost, and Linear Regression**. Each model was evaluated based on key performance metrics, such as Mean Squared Error (MSE) and R-squared values. While most models performed well, **Random Forest emerged as the best-performing model**, delivering the highest accuracy and the most reliable predictions.  

By carefully preprocessing the data, selecting the right features, and optimizing hyperparameters, I ensured that the final model provided precise CLTV predictions. This project highlights the importance of data transformation and model selection in building an effective machine learning solution.
![image](https://github.com/user-attachments/assets/5f162a23-6c35-45e2-a8ba-853c560c5455)
![image](https://github.com/user-attachments/assets/ed10176c-291b-44ea-9140-aef9be929f84)

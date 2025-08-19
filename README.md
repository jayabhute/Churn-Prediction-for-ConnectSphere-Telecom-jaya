**Churn Prediction for ConnectSphere Telecom**

** Project Overview**
This project predicts whether a telecom customer will churn (leave the company) or not using Artificial Neural Networks (ANN).  
Dataset is taken from live class session and slightly modified for experimentation.

**  Business Context**
ConnectSphere Telecom, a regional telecom provider, aims to reduce customer churn.  
This project builds an ANN binary classification model to identify potential churners based on usage patterns and account details.  

- Develop a binary classification model to identify potential churners.  
- Use features like call duration, data usage, and contract length from Pandas.  
- Evaluate model accuracy using metrics like Accuracy and F1-Score.  
- Generate a list of at-risk customers for retention strategies.  

** Dataset**
- Source: Provided during live class  
- Features: Call duration, Data usage, Contract length, Monthly charges etc.  
- Target: Churn (Yes/No)  

** Technologies Used**
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib, Seaborn  
- Google Colab  
- GitHub  

** Methodology**
1.Data Loading & Cleaning** – Handle missing values, encode categories, scale features  
2. **Model Building** – ANN with dense layers (ReLU + Sigmoid)  
3. **Training & Evaluation** – Binary cross-entropy loss, Adam optimizer  
4. **Output** – Predictions with churn probability, flagged high-risk customers  

 **Results**
- Accuracy achieved: 79.13%
- F1-Score: ~0.79 (balanced performance)  
- Confusion Matrix showed good churn detection  
- Generated list of high-risk customers  

** Conclusion & Future Work**
The ANN model helps identify at-risk customers, enabling targeted retention.  
Future improvements may include:  
- Hyperparameter tuning  
- Adding more features (billing, support logs)  
- Deploying as a dashboard/API for real-time use  

 
Jaya Bhagwant Bhute  
(Completed as part of YBI Foundation Internship Project)

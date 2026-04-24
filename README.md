Life Expectancy Prediction Project

ntroduction
In this project, I tried to predict life expectancy using machine learning.  
The idea was to understand how factors like healthcare spending and country-level differences affect how long people live.

I used a Multiple Linear Regression model and worked through the full process — from cleaning the data to evaluating the model.

---

What I tried to achieve
- Understand the relationship between health spending and life expectancy  
- Build a simple but effective prediction model  
- Practice a full machine learning workflow on real data  

---

about the dataset
The dataset includes:

- Year  
- Healthcare spending per person (USD)  
- Country (encoded)  
- Life Expectancy (what we are trying to predict)

---

What I did in this project

1. Data preparation
- Cleaned and prepared the dataset  
- Converted categorical data into numbers (encoding)  
- Split the data into training and testing sets  

2. Model building
- Used Multiple Linear Regression from Scikit-learn  
- Trained the model on historical data  

3. Model evaluation
To check how well the model performs, I used:

- R² Score  
- Mean Absolute Error  
- Mean Squared Error  
- Root Mean Squared Error  

---

📈 How the model performed

- Train R² Score: 0.903 
- Test R² Score: 0.890

The difference between train and test scores is very small, which means the model is not overfitting and is performing well on new data.

---

Visualizations
I also explored the data visually:

- Actual vs Predicted values  
- Error (residual) distribution  
- Correlation between features  

These helped me understand how the model is behaving.

---

Tools I used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

What I learned
- How regression models actually predict real-world values  
- Importance of proper encoding  
- How to evaluate a model properly (not just relying on accuracy/R²)  
- How small preprocessing decisions can affect results  

---

What I want to improve next
- Try more advanced models like Random Forest and XGBoost  
- Improve feature engineering  
- Build a small web app for predictions  
- Work on better data visualization  

---

About me
I'm currently learning machine learning and building projects to improve my skills step by step.

---

If you like this project
Feel free to star the repo or connect with me on LinkedIn.  
Any feedback is always welcome 👍

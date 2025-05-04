# 📞 Telecom Customer Satisfaction Analysis with Bayesian & Linear Regression

This project investigates customer satisfaction using both probabilistic (Bayesian) and traditional (Linear Regression) methods to identify key drivers of dissatisfaction among telecom users.

## 🧪 Models Developed
- **Model 1**: Bayesian Logistic Regression (50 MCMC Samples)
- **Model 2**: Bayesian Logistic Regression (1000 MCMC Samples)
- **Model 3**: Multiple Linear Regression (Traditional Machine Learning Approach)

## 🧰 Libraries Used
- `pandas`, `numpy`: Data wrangling & numerical operations  
- `matplotlib`, `seaborn`: Data visualization  
- `scikit-learn`: Regression, ROC curve, evaluation metrics  
- `pymc`: Bayesian model definition & sampling  
- `arviz`: Posterior checks and diagnostics  

## 📊 Features Analyzed
- **Age**
- **Income**
- **Loyalty Years**
- **Satisfaction** (converted to binary: High [1,2,3] vs Low [4,5])

## 📈 Key Results
- **Income** is the strongest and most consistent predictor of high satisfaction
- **Loyalty Years** shows a moderate or uncertain effect
- **Age** has negligible influence across all models
- **Bayesian Logistic Regression (Model 1)** provided better interpretability
- **Model 3** (Linear Regression) performed poorly (AUC = 0.39, R² < 0)

## 📌 Conclusion
Bayesian models proved more insightful and statistically robust for classifying customer satisfaction. The study suggests combining Bayesian modeling with enhanced customer data for better prediction and business strategy.

## 🧭 Recommendations
- Personalised offers for high-income, loyal customers
- Infrastructure investment to improve service quality
- Launch customer engagement campaigns based on feedback
- Implement AI-powered chatbots for efficient customer support

## 📁 Project Structure

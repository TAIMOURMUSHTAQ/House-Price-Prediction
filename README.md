# 🏡 House Price Prediction
## 📌 Project Overview
This project predicts **house prices** using property features such as size, bedrooms, bathrooms, and location.  
We apply **regression models** (Linear Regression & Gradient Boosting) and evaluate their performance.  

## 📂 Dataset
**Source**: [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  

**Features Used**:
1.	sqft_living (size of the house)
2.	bedrooms 
3.	bathrooms
4.	floors
5.	zipcode (location)

## 🛠️ Steps Performed
1. **Data Preprocessing**
•	Handled missing values
•	Scaled numeric features
•	Encoded categorical variables (`zipcode`)
2. **Model Training**
1.	Linear Regression
2.	Gradient Boosting Regressor
3. **Evaluation**
1.	Mean Absolute Error (MAE)
2.	Root Mean Squared Error (RMSE)
4. **Visualization**
•	Scatter plots of features vs price
•	Predicted vs Actual Prices

## 📊 Results
Model           	  |MAE	  |RMSE
Linear Regression  	|113,722	|40,533,040,847
Gradient Boosting	  |123,250	|46,601,912,940

## 📸 Sample Visualization
**Predicted vs Actual Prices (Gradient Boosting):**
<img width="705" height="618" alt="image" src="https://github.com/user-attachments/assets/104bf5c6-854a-4897-a971-c90139efedcf" />
 

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

# Install dependencies
pip install -r requirements.txt
# Run notebook
jupyter notebook house_price_prediction.ipynb

📌 Skills Practiced
•	Regression (Linear & Gradient Boosting)
•	Feature Engineering (Scaling, Encoding)
•	Model Evaluation (MAE, RMSE)
•	Data Visualization

📈 Next Steps
•	Add more advanced models (XGBoost, Random Forest)
•	Perform hyperparameter tuning
•	Deploy model with Streamlit for interactive predictions

📧 **Author**
Taimour Mushtaq
🎓 BSCS Student at Federal Urdu University of Arts,Science and Technology, Islamabad Pakistan
🔗 https://www.linkedin.com/in/taimourmushtaq/ |https://github.com/TAIMOURMUSHTAQ

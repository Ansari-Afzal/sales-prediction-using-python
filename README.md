# Sales Prediction Using Python

## 📌 Project Overview
This project demonstrates a complete workflow for predicting product sales using advertising data.  
It covers **data preprocessing**, **exploratory data analysis (EDA)**, **outlier detection**, **correlation analysis**, and **machine learning model training** for sales forecasting.

The notebook uses the **Advertising dataset**, which contains information on advertising budgets across TV, Radio, and Newspaper channels, along with corresponding sales figures.

---

## 📊 Dataset
The dataset (`Advertising.csv`) contains:
| Column     | Description |
|------------|-------------|
| TV         | Advertising spend on TV |
| Radio      | Advertising spend on Radio |
| Newspaper  | Advertising spend on Newspaper |
| Sales      | Sales revenue (target variable) |

---

## ⚙️ Features Implemented
1. **Data Loading & Inspection**  
   - Load CSV into Pandas DataFrame  
   - View data shape, column info, missing values

2. **Data Cleaning**  
   - Dropped unnecessary columns (`Unnamed: 0`)  
   - Checked for and handled missing values

3. **Outlier Detection**  
   - Used **IQR method** to detect outliers for each feature  
   - Found 2 outliers in `Newspaper` column

4. **Exploratory Data Analysis (EDA)**  
   - Boxplots to visualize data distribution and detect outliers  
   - Heatmap to understand feature correlations  
   - Observed strong correlation between **TV advertising** and **Sales**

5. **Model Building**  
   - Feature selection: `TV`, `Radio`, `Newspaper` as predictors  
   - Target: `Sales`  
   - Data split into training and testing sets (80/20)  
   - Applied **Linear Regression** model from `scikit-learn`

6. **Model Evaluation**  
   - Evaluated using **R² Score** and **Mean Squared Error (MSE)**  
   - Plotted **Predicted vs Actual** sales for visual comparison

 🛠️ Technologies Used

Python 3

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

scikit-learn – Machine learning model & evaluation

Jupyter Notebook – Interactive coding environment

📌 Conclusion

This project effectively shows how advertising budget allocation impacts sales.
By using linear regression, we achieved high accuracy in sales predictions.
The results suggest businesses should prioritize TV and Radio advertising for maximum impact, while Newspaper ads contribute less to sales growth.

---

## 📈 Results
- **R² Score**: ~0.90 (indicating strong predictive power)  
- **MSE**: Low error, meaning predictions are close to actual sales values  
- **Key Insight**: TV advertising spend is the most influential factor in predicting sales, followed by Radio; Newspaper has minimal effect.

---

## 🚀 How to Use
1. **Clone the repository**  
```bash
git clone https://github.com/Ansari-Afzal/sales-prediction-using-python.git
cd sales-prediction-using-python

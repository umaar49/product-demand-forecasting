# product-demand-forecasting

This project predicts the demand level (High, Medium, Low) of products using real retail data. It includes data preprocessing, feature engineering, exploratory data analysis, and machine learning model training using XGBoost.

---

## 📂 Project Structure

- `main_notebook.ipynb` – Full Jupyter Notebook with code, EDA, and model
- `Product_Demand_Forcasting.pdf` – Final report of the project
- `dataset.csv` – Dataset used for training the model *(source credited below)*
- `README.md` – Project overview and guide

---

## 📊 Dataset Overview

The dataset contains retail transaction data including:

- Invoice No, Product Description, Quantity,StockCode
- Invoice Date, Unit Price, Customer ID, Country

After cleaning:
- Removed null and duplicate entries
- Filtered canceled transactions and invalid unit prices
- Feature Engineering like `TotalPrice`, `Month`, `DayOfWeek`

> 📌 **Dataset Source:**  
> [https://www.kaggle.com/datasets/jazidesigns/online-retail-uk]  
> *(I do not own this dataset — used for educational purposes only)*

---

## 🔍 Exploratory Data Analysis

- Top products by sales and revenue
- Monthly trends using line plots
- Country-wise revenue breakdown

---

## 🧠 Model Used

- **Model:** XGBoost Classifier
- **Target:** Product Demand (High, Medium, Low)
- **Accuracy:** ~99% on test set

### 📉 Evaluation:
- Classification report
- Confusion matrix
- Actual vs Predicted Demand plot

---

## 🛠️ Tools & Technologies

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Scikit-learn
- XGBoost

---

## 📌 Key Takeaways

- Demonstrated the complete pipeline from data cleaning to model evaluation
- Learned to visualize sales data in various dimensions
- Applied classification techniques to demand prediction

---

## 📫 Contact

**Muhammad Umar Saleem**  
Electrical Engineering Graduate (June 2025)  
Aspiring Data Scientist | ML Enthusiast  


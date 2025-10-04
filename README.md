# House Price Prediction using Linear Regression  

## Introduction  
This project predicts house prices based on **land area** using **Linear Regression**.  
It demonstrates how simple regression models can be applied to real-world problems like real estate price prediction.  

---

## Dataset Overview  
- **File used:** `dataset.csv`  
- **Features:**  
  - `area` → land area in square feet  
- **Target:**  
  - `price` → house price (currency not specified, assumed as ₹ or $)  

Sample data:  

| area (sq.ft) | price   |  
|--------------|---------|  
| 2600         | 550000  |  
| 3000         | 565000  |  
| 3200         | 610000  |  
| ...          | ...     |  

---

## ⚙️ Model Training  
- Algorithm: **Linear Regression** (`scikit-learn`)  
- Steps performed:  
  1. Load dataset using **pandas**.  
  2. Visualize `area` vs `price` using **matplotlib**.  
  3. Split dataset:  
     - `X` → `area`  
     - `y` → `price`  
  4. Train the Linear Regression model.  
  5. Extract model parameters:  
     - **Slope (m)** → coefficient of area  
     - **Intercept (b)**  

Formula learned by model:  

\[
\text{Price} = m \times \text{Area} + b
\]  

---

## 🔮 Model Prediction  
Example Prediction:  
- Input: `6660 sq.ft`  
- Output: Predicted Price ≈ *[model output]*  

---

## ✅ Conclusion  
- Linear Regression can effectively capture the relationship between land area and price.  
- Even though this project uses only **1 feature (area)**, it clearly shows how regression can help in property price estimation.  

---

## 🚀 Possible Extensions  
- Use **multiple features** like number of rooms, location, age of the house, etc.  
- Try **Polynomial Regression** for nonlinear data.  
- Implement advanced models like **Random Forests** or **XGBoost**.  
- Deploy the model as a **web app** using Flask/Streamlit.  

---

## 🛠️ Prerequisites  
Make sure you have the following installed:  

- Python 3.x  
- Google Colab / Jupyter Notebook  
- Required libraries:  
  ```bash
  pip install numpy pandas matplotlib scikit-learn
  

 References  
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)  
- [Pandas Documentation](https://pandas.pydata.org/)  
- [Matplotlib Documentation](https://matplotlib.org/)  
- [Kaggle Datasets](https://www.kaggle.com/datasets)  <!-- add if dataset is from Kaggle -->

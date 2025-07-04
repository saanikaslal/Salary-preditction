
---

## 📈 Linear Regression: Salary Prediction Based on Experience

This project demonstrates a simple yet effective **Linear Regression** model to predict salary based on **years of experience**. It includes:

* Data preprocessing
* Model training and evaluation
* Visualization using **Plotly**
* Residual analysis and uncertainty estimation

---

### 🛠️ Tools & Libraries Used

* Python
* pandas
* numpy
* scikit-learn
* plotly

---

### 📂 Project Structure

```
├── data/
│   └── salary_data.csv        # Optional: your dataset
├── notebook.ipynb             # Main Jupyter notebook
├── README.md                  # Project documentation (this file)
```

---

### 📌 Key Features

* **Train/Test Split** using `train_test_split`
* **LinearRegression** model from `sklearn`
* **Evaluation Metrics**:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)
  * R² Score
* **Interactive Visualizations** with `plotly`:

  * Regression line + actual data
  * Residuals plot
  * Confidence band (±1 std deviation)

---

### 📊 Model Performance

| Dataset   | MAE      | RMSE     | R² Score |
| --------- | -------- | -------- | -------- |
| **Train** | \~₹4,221 | \~₹5,206 | 0.9645   |
| **Test**  | \~₹6,286 | \~₹7,059 | 0.9024   |

➡️ High R² on both sets indicates strong generalization.

---

### 📉 Visualizations

* **Scatter plot** of actual vs predicted salary
* **Regression line** fit over training data
* **Residual plot** to verify randomness of error
* **Prediction band** to represent uncertainty

---

### 🔧 How to Run

1. Clone this repo or copy the notebook
2. Install requirements:

   ```bash
   pip install pandas numpy scikit-learn plotly
   ```
3. Run the notebook in Jupyter or VSCode.

---



### 📜 License

MIT License. Free to use, modify, and share.

---


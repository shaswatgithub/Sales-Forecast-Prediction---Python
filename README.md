# 🛒 Sales Forecast Prediction Project

A Python project to predict future sales using **historical sales data**! This project uses machine learning and time series features to forecast sales trends. 📈✨

---

## 🐍 Language
- **Python**: The main programming language used for data manipulation, visualization, and ML.

## 📚 Libraries
- **pandas** 🗂️ : Data analysis and handling CSVs.
- **numpy** 🔢 : Numerical operations and calculations.
- **matplotlib** 📊 : Plotting sales trends and charts.
- **seaborn** 🎨 : Beautiful and easy visualizations.
- **xgboost** ⚡ : Gradient boosting model for regression.
- **scikit-learn** 🛠️ : Train-test split, evaluation metrics, and ML utilities.

---

## 🛠️ Steps in the Project
1. **Load Data** 📂
   - Read CSV file with `pandas`.
2. **Preprocess Data** 🧹
   - Convert "Order Date" to datetime.
   - Group sales by date.
3. **Visualize Sales Trend** 👀
   - Plot sales over time using `matplotlib`.
4. **Feature Engineering** ✨
   - Create lagged features to capture previous sales patterns.
5. **Prepare Training & Test Sets** 🏋️
   - Split data using `train_test_split`.
6. **Train XGBoost Model** ⚡
   - Predict sales using gradient boosting.
7. **Evaluate Model** ✅
   - Compute RMSE to measure prediction accuracy.
8. **Visualize Predictions** 🎨
   - Compare predicted vs actual sales on a graph.

---

## 📈 Output
- **RMSE Score**: ~734.63
- **Plots**: Actual vs Predicted sales trends

---

## 🔮 Applications
- Inventory management 🏪
- Demand forecasting 📊
- Marketing strategy planning 📣
- Business resource optimization 🏭

---

## 🤗 Fun Fact
Time series models like this help companies **plan ahead** and avoid stockouts or oversupply! ⏳💰

---

## ⚡ Quick Commands
```bash
# Install all required libraries
pip install pandas numpy matplotlib seaborn scikit-learn xgboost


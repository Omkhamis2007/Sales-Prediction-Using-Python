# 📈 Sales Prediction using Python

🚀 This project was completed as part of the CodeAlpha Data Science Internship.

The aim of this project is to predict future sales based on advertising expenditure across different platforms such as TV, Radio, and Newspaper using Machine Learning techniques. The project also analyzes how advertising strategies influence sales outcomes and provides insights for business decision-making.

---

## 🎯 Project Objective

Businesses invest heavily in advertising, but not every platform contributes equally to sales growth.

This project helps answer:

- How does advertising impact sales?
- Which advertising platform contributes the most?
- Can future sales be predicted using previous advertising data?

Using Machine Learning, we analyze historical data and build a predictive model to forecast sales.

---

## 📂 Dataset Information

The dataset contains advertising spending across multiple platforms and corresponding sales values.

### Dataset Columns

| Column | Description |
|----------|-------------|
| TV | Budget spent on TV advertisements |
| Radio | Budget spent on Radio advertisements |
| Newspaper | Budget spent on Newspaper advertisements |
| Sales | Product sales |

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Collection
- Loaded dataset using Pandas

### 2. Data Cleaning
- Checked missing values
- Removed unnecessary columns

### 3. Exploratory Data Analysis (EDA)
- Statistical summary
- Correlation analysis
- Pairplots
- Scatter plots

### 4. Feature Selection

Input Features:

- TV
- Radio
- Newspaper

Target Variable:

- Sales

### 5. Data Splitting

- 80% Training Data
- 20% Testing Data

### 6. Model Building

Used:

**Linear Regression**

The model learns the relationship between advertising spending and sales values.

### 7. Prediction

Predicted future sales using unseen advertising data.

### 8. Model Evaluation

Performance metrics used:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Square Error)
- R² Score

---

## 📊 Visualizations Included

✅ Correlation Heatmap
<img width="625" height="528" alt="o1" src="https://github.com/user-attachments/assets/ea3e08e5-4f47-4b8c-8ea8-46180574a87e" />

✅ TV vs Sales Analysis
<img width="531" height="393" alt="o2" src="https://github.com/user-attachments/assets/8b38044d-face-4215-b79c-12abaf6ee9f3" />

✅ Radio vs Sales Analysis
<img width="531" height="393" alt="o3" src="https://github.com/user-attachments/assets/659620c2-b545-4572-a09f-0e37a43782a4" />

✅ Newspaper vs Sales Analysis
<img width="531" height="393" alt="o4" src="https://github.com/user-attachments/assets/94b9c8e6-ec0d-4d15-823e-e56b60f74adc" />

✅ Actual vs Predicted Sales Graph
<img width="700" height="547" alt="o5" src="https://github.com/user-attachments/assets/94a356ee-058a-4d71-9968-733f3c151dc0" />

---

## 💡 Key Insights

📌 TV advertising showed the strongest impact on sales.

📌 Radio advertising also contributed positively.

📌 Newspaper advertising had comparatively lower impact.

📌 Proper advertising allocation can improve business growth.

📌 Machine Learning can help forecast future sales trends effectively.

---

## 🔮 Future Improvements

- Implement advanced regression algorithms
- Hyperparameter tuning
- Deploy using Streamlit
- Create interactive dashboards

---

## 👨‍💻 Author

**Om Khamis**   

Passionate about Data Science, Machine Learning, and building real-world projects with Python.
⭐ If you found this project useful, consider giving it a star.

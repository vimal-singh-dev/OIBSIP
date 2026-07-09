<div align="center">

# 🚗 Car Price Prediction using Machine Learning

### Predicting Used Car Selling Prices with Regression Models

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-blue?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

### 📈 Machine Learning Regression Project for Predicting Used Car Prices

*A complete machine learning project that predicts the selling price of used cars using regression algorithms, feature engineering, exploratory data analysis, and model evaluation.*

</div>

---

# 📖 Project Overview

Pricing a used car accurately depends on multiple factors such as:

- 🚗 Brand
- 📅 Manufacturing Year
- ⛽ Fuel Type
- ⚙️ Transmission
- 👤 Seller Type
- 📍 Kilometers Driven
- 💰 Present Market Price
- 👥 Number of Previous Owners

This project uses **Machine Learning Regression** techniques to estimate the selling price of a used car based on these features.

The project demonstrates the complete workflow of a real-world data science project including:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Feature Encoding
- Model Training
- Model Evaluation
- Feature Importance Analysis

---

# 🎯 Objectives

- Clean and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Engineer meaningful features such as Car Age and Brand
- Encode categorical variables
- Train multiple regression models
- Compare model performance
- Identify the most influential features affecting car prices

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---

# 📂 Dataset

**Dataset:** Car Price Prediction Dataset

The dataset contains information about used cars including:

- Car Name
- Manufacturing Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Number of Owners

---

# 📊 Dataset Features

| Feature | Description |
|----------|-------------|
| Car_Name | Name of the Car |
| Year | Manufacturing Year |
| Selling_Price | Selling Price (Target Variable) |
| Present_Price | Current Ex-showroom Price |
| Kms_Driven | Total Distance Driven |
| Fuel_Type | Petrol / Diesel / CNG |
| Seller_Type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of Previous Owners |

---

# ⚙️ Feature Engineering

The following new features were created:

### 🚘 Car Age

```
Car Age = Current Year − Manufacturing Year
```

### 🏷 Brand Extraction

Extracted the vehicle brand from the **Car_Name** column.

Example:

| Car Name | Brand |
|-----------|-------|
| Maruti Swift | Maruti |
| Hyundai i20 | Hyundai |
| Honda City | Honda |

---

# 🔍 Exploratory Data Analysis

The notebook includes:

- ✅ Dataset Overview
- ✅ Missing Value Analysis
- ✅ Duplicate Removal
- ✅ Selling Price Distribution
- ✅ Price vs Fuel Type
- ✅ Price vs Car Age
- ✅ Feature Correlation Heatmap

---

# 📈 Visualizations

The project contains several visualizations including:

- 📊 Selling Price Distribution
- 📦 Price vs Fuel Type Box Plot
- 📉 Price vs Car Age Scatter Plot
- 🔥 Correlation Heatmap
- ⭐ Feature Importance Chart

---

# 🤖 Machine Learning Models

The following regression algorithms were implemented:

- 📈 Linear Regression
- 🌲 Random Forest Regressor

---

# 📏 Evaluation Metrics

Each model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📊 Model Comparison

| Model | MAE | RMSE | R² Score |
|--------|----:|------:|---------:|
| Linear Regression | *Calculated* | *Calculated* | *Calculated* |
| Random Forest Regressor | *Calculated* | *Calculated* | *Calculated* |

> The Random Forest Regressor achieved better predictive performance due to its ability to model complex, non-linear relationships.

---

# 📌 Key Insights

- Older cars generally have lower selling prices.
- Present market price is one of the strongest predictors of selling price.
- Automatic transmission vehicles often command higher prices.
- Fuel type influences resale value.
- Dealer-listed cars typically have different pricing patterns compared to individual sellers.

---

# 📂 Project Structure

```
Car-Price-Prediction/
│
├── Car_Price_Prediction.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── dataset/
│   └── car_data.csv
│
└── images/
    ├── selling_price_distribution.png
    ├── fuel_type_boxplot.png
    ├── car_age_scatter.png
    ├── heatmap.png
    └── feature_importance.png
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Car-Price-Prediction.git
```

Navigate to the project directory:

```bash
cd Car-Price-Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Install manually if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

# 📸 Project Outputs

The notebook generates:

- 📊 Selling Price Distribution
- 📦 Fuel Type Box Plot
- 📉 Car Age Scatter Plot
- 🔥 Correlation Heatmap
- 🌲 Feature Importance Chart
- 📈 Regression Model Performance

---

# 🚀 Future Improvements

- Hyperparameter Tuning with GridSearchCV
- XGBoost Regressor
- Gradient Boosting Regressor
- LightGBM Integration
- Streamlit Web Application
- Flask REST API
- Model Deployment on Render or Hugging Face Spaces

---

# 📚 Learning Outcomes

This project demonstrates practical understanding of:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Regression Algorithms
- One-Hot Encoding
- Feature Importance Analysis
- Machine Learning Model Evaluation
- Python for Data Science

---

# 👨‍💻 Author

## **Vimal Singh**

**B.Tech Information Technology Student**

### Interests

- 🤖 Machine Learning
- 📊 Data Science
- 🧠 Artificial Intelligence
- 🐍 Python Development

### GitHub

```
https://github.com/yourusername
```

### LinkedIn

```
https://linkedin.com/in/yourprofile
```

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

If you have suggestions for improving the project, feel free to fork the repository and submit a pull request.

---

# ⭐ Show Your Support

If you found this project useful:

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

### 🚗 "Data drives decisions, Machine Learning predicts the future."

**Made with ❤️ using Python, Scikit-Learn, and Jupyter Notebook**

</div>
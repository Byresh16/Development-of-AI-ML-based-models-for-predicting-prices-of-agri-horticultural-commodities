## 📌 Development of AI/ML-Based Models for Predicting Price of Agri-Horticulture Commodities

### 📖 Overview

This project focuses on building AI/ML-based models to predict the prices of agricultural and horticultural commodities.
Fluctuating prices cause challenges for farmers and traders, and this solution aims to provide reliable forecasts to support decision-making and reduce losses.

### ⚙️ Features

* Collection of historical commodity price data and related external factors (weather, season, demand-supply).
* Data preprocessing with handling of missing values, outliers, and normalization.
* Feature engineering (lag features, moving averages, seasonal indicators, rainfall).
* Multiple model implementation:

  * Linear Regression (baseline)
  * Random Forest and XGBoost (ML models)
  * LSTM (Deep learning for time-series)
* Model evaluation using RMSE, MAE, and R² score.
* Comparative analysis of classical ML and deep learning approaches.
* 
### 🧠 Tech Stack

* **Languages:** Python
* **Libraries/Frameworks:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib/Seaborn
* **Tools:** Jupyter Notebook / Google Colab
* 
### 📊 Results

* Random Forest achieved better accuracy for short-term prediction.
* LSTM captured seasonal trends more effectively, resulting in lower RMSE and higher R² for long-term predictions.

### 👩‍💻 Author

**Byresh Soradi**

* 📧 [byreshsoradi1234@gmail.com](mailto:byreshsoradi1234@gmail.com)
* 💼 [LinkedIn](https://www.linkedin.com/in/byresh-soradi-087a232a1)

### 🚀 Future Enhancements

* Integration of real-time data from weather and market APIs.
* Deployment as a web-based decision support system for farmers and traders.
* Incorporating hybrid ML + econometric models for better accuracy.

### 📁 Repository Structure
├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter notebooks for exploration and modeling
├── models/               # Saved trained model files
├── src/                  # Source code for preprocessing and training
├── results/               # Evaluation metrics and visualizations
└── README.md


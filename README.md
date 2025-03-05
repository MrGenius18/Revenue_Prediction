<h1 align="center">⚡Restaurant Revenue Prediction Model ⚡</h1>

---

<h2 align="left">➡️ Visit the Application</h2>

[![Click Me](https://img.shields.io/badge/Click-Me-blue?style=for-the-badge)](https://revenue-prediction-vtbe.onrender.com)

---

<h2 align="left">➡️ Description</h2>

This's a machine learning model for predicting revenue based on historical data. The model is designed to forecast future revenue based on various input features such as sales data, marketing spend, seasonality, and other relevant business parameters. It utilizes a regression-based approach to **predict continuous revenue values**, and is optimized for scalability, allowing businesses to forecast future earnings effectively.

The repository includes the full pipeline for data preprocessing, model training, evaluation, and deployment.

---

<h2 align="left">➡️ Features</h2>

- **Data Preprocessing**: Clean, normalize, and transform raw data for model consumption.
- **Model Training**: Train the model using machine learning algorithms such as Linear Regression, Random Forest, or XGBoost.
- **Revenue Prediction**: Use the trained model to predict future revenue based on input data.
- **Model Evaluation**: Evaluate model performance using common metrics like RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R² score.
- **Deployment Ready**: The model is ready to be deployed as a REST API using Flask.
- **Version Control**: The project is version-controlled using Git and hosted on Render for easy collaboration and tracking of changes.

---

<h2 align="left">➡️ Technologies Used</h2>

- **Python**: Programming language used for developing the model.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: Machine learning algorithms and model evaluation.
- **XGBoost**: Optimized gradient boosting for better performance.
- **Flask**: A lightweight web framework for deploying the model as an API.
- **Render**: Containerization for easy deployment across different environments.
- **GitHub Actions**: CI/CD for automating testing and deployment.

---

<h2 align="left">➡️ Installation & Setup</h2>

## Prerequisites
- Python 3.x
- Pip (Python package manager)
- Git

## Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/MrGenius18/Revenue_Prediction.git
   
2. Navigate to the project directory:
   ```bash
   cd Revenue_Prediction
   
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Train the model (optional, if data is available):
   ```bash
   python train_model.py

5. Run the model as a REST API:
   ```bash
   python app.py
   
6. Access the API at http://127.0.0.1:5000 to make predictions.

---

<h2 align="left">➡️ Model Performance</h2>

- **RMSE**: 432167.2974
- **MAE**: 318430.6327
- **R² Score**: 87.24%

## Train-Test Prediction Model Visualizations

![revenue_train_test_result.png](https://github.com/MrGenius18/Revenue_Prediction/blob/bc1d7898b2995e650618b8c4499eaaf6fa902714/extra%20materials/revenue_train_test_result.png)

<h2 align="left">✨ Demo</h2>

![Demo Screenshot](https://github.com/MrGenius18/Revenue_Prediction/blob/bc1d7898b2995e650618b8c4499eaaf6fa902714/extra%20materials/Demo.png)

---

<h2 align="left">➡️ Acknowledgements</h2>

Thanks to **Intellipaat** for the inspiration and datasets used in this project.

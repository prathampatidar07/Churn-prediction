# Churn-prediction
## Project Overview
This project focuses on predicting customer churn for a subscription-based service using SQL, Python (Machine Learning), and Power BI. The goal is to build a robust predictive model, analyze customer behavior, and provide actionable insights to reduce churn.

## Features
- **Data Extraction & Processing**: Data is extracted using SQL, cleaned, and preprocessed for analysis.
- **Exploratory Data Analysis (EDA)**: Key patterns and trends in customer churn behavior are analyzed using Python.
- **Machine Learning Model**: A predictive model is built using Python (Scikit-learn) for churn classification.
- **Model Deployment**: The trained model is deployed locally using Flask or FastAPI.
- **Dashboard & Visualization**: Power BI is used to create interactive reports for stakeholders.
- **Model Monitoring**: Performance metrics are tracked, and alerts are set up for data drift and periodic retraining.

## Tech Stack
- **SQL**: Data extraction and preprocessing
- **Python**: Pandas, NumPy, Scikit-learn, Flask/FastAPI, Matplotlib, Seaborn
- **Power BI**: Data visualization and dashboard creation
- **Model Deployment**: Flask/FastAPI, Pickle/Joblib for model persistence

## Project Workflow
1. **Data Collection**: Gather customer data from the subscription service database.
2. **Data Cleaning & Preprocessing**: Handle missing values, outliers, and feature engineering.
3. **Exploratory Data Analysis (EDA)**: Identify key factors influencing churn.
4. **Model Training & Evaluation**: Train a machine learning model and evaluate its performance.
5. **Deployment**: Serve the model locally using Flask/FastAPI.
6. **Monitoring & Maintenance**: Track model performance and set up alerts for retraining.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/prathampatidar07/Churn-prediction.git
   cd Churn-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask/FastAPI server:
   ```bash
   python app.py
   ```
4. Open Power BI and connect to the processed data for visualization.

## Model Monitoring
- Track accuracy, precision, and recall over time.
- Set up alerts for data drift.
- Perform periodic retraining with new data.

## Contributing
Feel free to fork this repository and contribute improvements! Submit a pull request with your updates.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out to **Pratham Patidar** at prathampatidarrr@gmail.com

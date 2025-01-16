# Student Performance Prediction Model

This project provides a robust solution for predicting student performance based on demographic, educational, and test score data. Using a carefully designed machine learning pipeline, the model predicts outcomes with high accuracy. The project integrates data preprocessing, model training, evaluation, and deployment seamlessly. The Flask-based frontend offers a user-friendly interface to interact with the model. Additionally, the application has been deployed using **AWS Elastic Beanstalk**, ensuring scalability and reliability.

---

## Features

### **End-to-End Machine Learning Pipeline**
- **Data Preparation**:
  - Loads raw data and cleans it for better quality and consistency.
  - Handles missing values, data type conversions, and feature engineering.

- **Model Training**:
  - Trains multiple algorithms, including:
    - **Random Forest**
    - **Decision Tree**
    - **Gradient Boosting**
  - Selects the best-performing model based on validation accuracy and stores it for deployment.

- **Preprocessing**:
  - Includes a standardized data preprocessing pipeline for scaling and encoding input features.
  - Ensures consistent input data handling for predictions.

- **Deployment**:
  - Exports the trained model and preprocessor as `.pkl` files for reuse.
  - Provides a robust prediction pipeline that integrates seamlessly with the frontend.

### **Production-Ready Features**
- **AWS Elastic Beanstalk Deployment**:
  - The application is hosted on AWS Elastic Beanstalk, enabling smooth scaling and reliable uptime.
  - The deployment process ensures high availability and fault tolerance for the Flask-based application.

- **Custom Exception Handling**:
  - Centralized `CustomException` class ensures robust error tracking and debugging.

- **Extensive Logging**:
  - Logs key steps in the pipeline for better monitoring and troubleshooting.

### **Interactive Flask Frontend**
- A clean and intuitive interface for users to:
  - Input student-related parameters like gender, race/ethnicity, test scores, etc.
  - View predictions for student performance in real-time.


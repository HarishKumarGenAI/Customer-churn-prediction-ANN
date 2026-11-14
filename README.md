Customer Churn Prediction using ANN
📌 Project Overview
This project implements a Customer Churn Prediction system using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

The model predicts whether a customer is likely to churn based on:

✦Customer Tenure
✦Monthly Charges
✦Data Usage
✦Number of Support Tickets

A synthetic dataset is generated and used to train the ANN model. The project also visualizes training and validation loss to evaluate model performance.

🚀 Features

✅ Synthetic customer dataset generation

✅ Data preprocessing and standardization

✅ Artificial Neural Network (ANN) implementation

✅ Model training and validation

✅ Customer churn prediction

✅ Training loss visualization

✅ TensorFlow/Keras based deep learning model

🛠 Technologies Used

✦Python
✦Pandas
✦NumPy
✦TensorFlow
✦Keras
✦Scikit-learn
✦Matplotlib

📂 Dataset Features

➤Feature	Description
Tenure	Customer subscription duration (months)
Monthly Charges	Monthly bill amount
Data Usage	Monthly data consumption
Support Ticket	Number of support tickets raised
Churn	Target variable (0 = No Churn, 1 = Churn)

➤Churn Logic
A customer is considered likely to churn if:

Tenure is less than 12 months and
Support tickets are greater than 3
OR
Monthly charges are greater than 100

⚙️ Model Architecture

➤Input Layer: 4 Features

➤Hidden Layer 1:
16 Neurons
ReLU Activation

➤Hidden Layer 2:
8 Neurons
ReLU Activation

➤Output Layer:
1 Neuron
Sigmoid Activation

➤Loss Function:
Binary Crossentropy

➤Optimizer:
Adam

➤Evaluation Metric:
Accuracy

📊 Workflow

✦Generate synthetic customer data
✦Create churn labels
✦Split data into training and testing sets
✦Standardize features
✦Build ANN model
✦Train model
✦Evaluate performance
✦Predict new customer churn probability
✦Visualize training loss

📈 Training Visualization

The model generates a loss curve showing:

✦Training Loss
✦Validation Loss

This helps monitor model learning and detect overfitting.

🎯 Future Improvements
✦Use real telecom customer datasets
✦Hyperparameter tuning
✦Add dropout layers
✦Build a Streamlit web application
✦Deploy using Docker and Cloud platforms
✦Compare ANN with Random Forest and XGBoost

👨‍💻 Author
Harish
Deep Learning Project using Artificial Neural Networks (ANN) for Customer Churn Prediction.

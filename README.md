Credit Card Fraud Detection Using Random Forest
📌 Project Overview

This project uses Machine Learning to detect fraudulent credit card transactions. A Random Forest Classifier is trained on transaction data to classify transactions as genuine or fraudulent.

The project includes data preprocessing, model training, performance evaluation, feature importance analysis, and ROC curve visualization.
🎯 Objectives

    Detect fraudulent credit card transactions.
    Preprocess and prepare transaction data for machine learning.
    Train a Random Forest classification model.
    Evaluate the model using classification metrics.
    Identify important features that influence fraud detection.

🛠️ Technologies Used

    Python
    Pandas – Data manipulation
    NumPy – Numerical operations
    Scikit-learn – Machine learning and model evaluation
    Matplotlib – Data visualization
    Seaborn – Statistical visualization
    Jupyter Notebook / Google Colab – Development environment

📂 Dataset

The project uses a credit card transaction dataset containing anonymized transaction features and a target column indicating whether a transaction is genuine or fraudulent.

    Class 0: Genuine transaction
    Class 1: Fraudulent transaction

The dataset is loaded, inspected, and prepared before training the model.

    Note: Update this section with the exact dataset name and source used in your notebook.

⚙️ Project Workflow

    Import the required Python libraries.
    Load and inspect the dataset.
    Check the dataset structure and missing values.
    Separate input features and the target variable.
    Split the data into training and testing sets.
    Train a Random Forest Classifier.
    Generate predictions on test data.
    Evaluate model performance.
    Visualize the confusion matrix.
    Analyze feature importance.
    Plot the ROC curve and calculate the AUC score.

🤖 Machine Learning Algorithm
Random Forest Classifier

Random Forest is a supervised machine learning algorithm that combines multiple decision trees to make predictions.

It is used in this project to classify credit card transactions as genuine or fraudulent based on transaction features.
📊 Model Evaluation

The model is evaluated using the following metrics:

    Accuracy: Overall proportion of correct predictions.
    Precision: Proportion of predicted fraudulent transactions that are actually fraudulent.
    Recall: Proportion of actual fraudulent transactions correctly identified.
    F1-Score: Harmonic mean of precision and recall.
    Confusion Matrix: Shows correct and incorrect classifications.
    ROC Curve: Illustrates the model's ability to distinguish between classes.
    AUC Score: Measures the model's overall discrimination ability.

For fraud detection, precision and recall are particularly important because accuracy alone may be misleading when fraudulent transactions are rare.
📈 Visualizations

The notebook includes:

    Random Forest confusion matrix
    Classification report
    Top 10 important features
    ROC curve for fraud prediction

These visualizations help explain the model's performance and the features that contribute to its predictions.
🚀 How to Run the Project

    Clone or download this repository.

    Open the Jupyter Notebook or upload it to Google Colab.

    Install the required libraries if necessary:

    pip install pandas numpy scikit-learn matplotlib seaborn jupyter

    Make sure the dataset is available at the file path specified in the notebook.

    Run the notebook cells in order.

    Review the evaluation metrics and visualizations.

📁 Project Structure

Credit-Card-Fraud-Detection/
│
├── credit_card_fraud_detection.ipynb
├── creditcard.csv
└── README.md

Replace the filenames above with the actual filenames in your repository.
🔮 Future Improvements

    Handle class imbalance using suitable sampling techniques or class weights.
    Compare Random Forest with Logistic Regression and other classification algorithms.
    Tune model hyperparameters for improved performance.
    Evaluate the model using precision-recall curves and additional fraud-specific metrics.
    Develop a simple web application for real-time transaction prediction.

👩‍💻 Author

Arockiya Jeniliya J

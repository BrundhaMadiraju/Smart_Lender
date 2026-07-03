# SmartLender – Loan Prediction System

## Project Overview

SmartLender is a Machine Learning-based web application that predicts whether a loan application will be approved or rejected based on applicant details. The system uses a trained Random Forest Classifier to analyze applicant information and provide fast and accurate loan approval predictions through a Flask web application.

---

## Features

- Loan approval prediction using Machine Learning
- User-friendly Flask web application
- Data preprocessing and feature scaling
- Comparison of multiple machine learning models
- Random Forest selected as the best-performing model
- Real-time loan prediction
- Responsive user interface

---

## Technologies Used

- Python
- Flask
- HTML
- CSS
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Joblib
- Matplotlib

---

## Project Structure

```
smart-lender/
│
├── app.py
├── preprocess.py
├── train_models.py
├── requirements.txt
├── README.md
│
├── dataset/
│   └── loan_data.csv
│
├── model/
│   ├── best_model.pkl
│   └── scaler.pkl
│
├── notebooks/
│   └── analysis.ipynb
│
├── static/
│   ├── css/
│   ├── images/
│   ├── cm_Decision_Tree.png
│   ├── cm_KNN.png
│   ├── cm_Random_Forest.png
│   ├── cm_XGBoost.png
│   └── model_comparison.png
│
└── templates/
    ├── home.html
    ├── index.html
    └── result.html
```

---

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd smart-lender
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

### 4. Train the Model (Optional)

```bash
python train_models.py
```

### 5. Run the Flask Application

```bash
python app.py
```

### 6. Open the Browser

Visit:

```
http://127.0.0.1:5000
```

---

## Machine Learning Models Used

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

The performance of all models was evaluated using:
- Training Accuracy
- Testing Accuracy
- Classification Report
- Confusion Matrix

The **Random Forest Classifier** achieved the highest testing accuracy and was selected as the final model.

---

## Dataset

The project uses the **Loan Prediction Dataset** containing applicant information such as:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status

---

## Future Enhancements

- User authentication
- Database integration
- Cloud deployment
- Credit score API integration
- Email notifications
- Mobile-friendly interface

---

## Team Members

- Brundha Madiraju
- Reddamma Katadasari
- Venkata Poojitha Peddi Boina
- Potturi Naga Vydehi
- Jala Rahul Kumar

---

## License

This project is developed for academic and educational purposes.
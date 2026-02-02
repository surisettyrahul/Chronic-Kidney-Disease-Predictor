# Chronic-Kidney-Disease-Predictor

Chronic Kidney Disease (CKD) is a long-term condition in which the kidneys gradually lose their ability to filter waste products and excess fluids from the blood. Since CKD often shows minimal or no symptoms in its early stages, early detection is critical to prevent severe complications such as kidney failure, cardiovascular disease, and anemia.

This project presents a Machine Learning–based Chronic Kidney Disease Predictor that analyzes patient clinical and laboratory data to predict whether an individual is likely to have CKD. The system uses a trained Gradient Boosting Classifier model and provides predictions through a Flask-based web application, making it easy to use and accessible.

The goal of this project is to demonstrate how data-driven techniques can support early diagnosis and assist healthcare professionals in decision-making.

# About Chronic Kidney Disease (CKD)

Chronic Kidney Disease is a progressive medical condition characterized by a gradual decline in kidney function over time. The kidneys are responsible for filtering toxins, maintaining electrolyte balance, regulating blood pressure, and producing hormones for red blood cell formation.

In the early stages, CKD may not present noticeable symptoms, which often leads to delayed diagnosis. As the disease progresses, patients may experience fatigue, swelling, high blood pressure, and abnormal laboratory values. Major risk factors include diabetes, hypertension, obesity, smoking, genetic factors, and long-term medication use.

Early prediction and monitoring of CKD can significantly slow disease progression and improve patient outcomes. Machine learning models can help identify hidden patterns in medical data, enabling early detection and preventive care.

# Features
- Predicts Chronic Kidney Disease using patient data

- Machine Learning model trained for binary classification

- Streamlit-based web interface

- Data normalization using a trained scaler

- Jupyter Notebook for model training and analysis

# Technologies Used

- Python

- Streamlit

- Scikit-learn

- Pandas

- NumPy

- Jupyter Notebook

##  Installation and Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/surisettyrahul/Chronic-Kidney-Disease-Predictor.git
cd Chronic-Kidney-Disease-Predictor
```

2. **Create and activate a virtual environment**
```bash
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Running the Application**
```bash
streamlit run app.py
```

# How the System Works

User enters clinical and laboratory details.

Input data is preprocessed using a trained scaler.

The Gradient Boosting Classifier predicts CKD status.

The result is displayed on the web interface.

# Model Information

Algorithm: Gradient Boosting Classifier

Model File: model_gbc.pkl

Scaler: scaler.pkl

The model can be retrained or improved using the Jupyter notebook provided.

# 🩺 Diabetes Prediction AI

This project is an interactive web application built with Streamlit for predicting the likelihood of diabetes in a patient based on several diagnostic measures. It leverages a Support Vector Machine (SVM) model trained on the PIMA Indians Diabetes Database.

## ✨ Features

- **Interactive Predictions:** Users can input patient data through sliders to get a real-time diabetes risk assessment.
- **Data Visualization:** The application includes visualizations for feature importance and dataset distribution.
- **Model Performance Metrics:** Displays training and testing accuracy of the underlying machine learning model.
- **User-Friendly Interface:** A clean and professional UI for easy navigation and use.

## 🚀 Live Demo

[Link to your deployed Streamlit App](https://diabetes-predictor-3zyagtcsuxuhl6zkrvrgzk.streamlit.app/)

## 🛠️ Tech Stack

- **Python:** The core programming language.
- **Streamlit:** For creating the interactive web application.
- **Scikit-learn:** For building and training the machine learning model.
- **Pandas & NumPy:** For data manipulation and numerical operations.
- **Plotly:** For creating interactive charts and visualizations.

## ⚙️ Getting Started

To run this project locally, follow these steps:

### Prerequisites

- Python 3.7+
- Pip

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Himanshukumar56/Diabetes-Predictor.git
    cd Diabetes-Predictor
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### Usage

Run the Streamlit application with the following command:

```bash
streamlit run app.py
```

The application will open in your default web browser.

## 📊 Dataset

This project uses the **PIMA Indians Diabetes Database**.

- **Source:** [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- **Description:** This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

## 🖼️ Screenshot

![Application Screenshot](img.jpeg)

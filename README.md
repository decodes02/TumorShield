# TumorShield
# Breast Cancer Detection Using Random Forest Classifier

This repository contains a machine learning model that classifies breast cancer tumors as **malignant** or **benign** using a Random Forest Classifier. The model achieves better accuracy compared to linear regression and decision tree models.

## Project Overview

Breast cancer detection is crucial for effective treatment. This project uses machine learning to analyze patient data and predict whether a tumor is **malignant** (cancerous) or **benign** (non-cancerous). The Random Forest Classifier was chosen for its higher accuracy and reliability.

## Dataset

- **Size**: 569 rows and 31 columns.
- **Source**: The dataset consists of various features of cell nuclei obtained from breast cancer biopsies.
- **Features**: 30 numerical features (e.g., radius, texture, perimeter, area, smoothness).
- **Target**: Binary classification (Malignant or Benign).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/breast-cancer-detection.git
    cd breast-cancer-detection
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook or Python script to train the model.

## Project Link

To view the project in Google Colab, click [here](https://colab.research.google.com/drive/1NyuqHa1Mk0fadaPwu_dNXgbtC8yjG7Kh?usp=sharing).

## Usage

1. **Data Preprocessing**: Handle missing values, scale features.
2. **Model Training**: Train the Random Forest model on the dataset.
3. **Model Evaluation**: Test the model and evaluate its performance using accuracy, confusion matrix, and classification report.

## Results

The Random Forest Classifier achieved an accuracy of **X%** (replace with your results). It outperforms both linear regression and decision tree models.

## Code Structure

- `breast_cancer_detection.ipynb`: Contains all the code to preprocess data, train, and evaluate the model.
- `requirements.txt`: List of dependencies for the project.
- `README.md`: Documentation file.

## How to Run

1. Load the dataset.
2. Preprocess the data.
3. Train the model using Random Forest.
4. Evaluate model performance.
5. Optionally, test the model on new data.

## License

This project is licensed under the MIT License.

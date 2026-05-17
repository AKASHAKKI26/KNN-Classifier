# KNN-Classifier
# Iris Flower Prediction using KNN Classifier

This project is a Machine Learning web application built using Streamlit and K-Nearest Neighbors (KNN) Classifier.

The application predicts the species of an Iris flower based on flower measurements.

---

## Iris Flower Classes

| Class | Flower Name |
|---|---|
| 0 | Setosa |
| 1 | Versicolor |
| 2 | Virginica |

---

## Features Used

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Machine Learning Algorithm

- K-Nearest Neighbors Classifier (KNN Classifier)

---

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- NumPy
-Pickle

---

## Project Structure

```text
IrisFlowerPrediction/
│
├── KNNclas.py
├── knnclas.pkl
├── requirements.txt
└── README.md
```

---

## Installation

Install the required libraries using:

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run KNNclas.py
```

---

## Input Features

| Feature | Description |
|---|---|
| Sepal Length | Length of sepal in cm |
| Sepal Width | Width of sepal in cm |
| Petal Length | Length of petal in cm |
| Petal Width | Width of petal in cm |

---

## Output

The application predicts:

```text
Iris Flower Species
```

Example:

```text
Predicted Flower: Setosa
```

---

## Model Description

The model is trained using:

- Iris Dataset
- KNN Classifier
- Flower feature measurements

---

## Author

Machine Learning Mini Project

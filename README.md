# 🌍 Exoplanet Habitability Prediction Using Machine Learning

## Overview

Exoplanet Habitability Prediction is a machine learning project designed to identify whether an exoplanet has the potential to support life based on planetary and stellar characteristics.

The system analyzes key features such as planet radius, planet mass, orbital period, star temperature, and star luminosity to predict habitability using a Random Forest classifier.

## Features

* Predicts whether an exoplanet is habitable or non-habitable
* Uses machine learning for classification
* Feature engineering with Habitability Index
* Stellar Compatibility Index calculation
* Interactive Streamlit dashboard
* Real-time prediction and visualization
* Model persistence using Joblib

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Plotly
* Joblib

## Project Structure

```text
Exoplanet-Habitability-Prediction/
│
├── app.py
├── predict.py
├── train_model.py
├── preprocessing.py
├── requirements.txt
├── README.md
│
├── data/
│   └── exoplanet_dataset.csv
│
├── model/
│   └── exoplanet_model.pkl
│
└── assets/
    └── dashboard.png
```

## Dataset Features

| Feature          | Description                                        |
| ---------------- | -------------------------------------------------- |
| Planet_Radius    | Radius of planet relative to Earth                 |
| Planet_Mass      | Mass of planet relative to Earth                   |
| Orbital_Period   | Number of days to orbit host star                  |
| Star_Temperature | Surface temperature of host star                   |
| Star_Luminosity  | Luminosity of host star                            |
| Habitable        | Target variable (1 = Habitable, 0 = Non-Habitable) |

## Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Streamlit Deployment

## Feature Engineering

### Habitability Index

Measures how closely planetary characteristics resemble Earth-like conditions.

### Stellar Compatibility Index

Measures compatibility of the host star for supporting habitable conditions.

## Model Used

Random Forest Classifier

Advantages:

* High accuracy
* Handles nonlinear relationships
* Robust against overfitting
* Suitable for scientific classification problems

## Installation

Clone repository:

```bash
git clone https://github.com/your-username/Exoplanet-Habitability-Prediction.git
cd Exoplanet-Habitability-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Training Model

```bash
python train_model.py
```

This generates:

```text
model/exoplanet_model.pkl
```

## Run Application

```bash
streamlit run app.py
```

## Dashboard Features

* Planetary parameter inputs
* Habitability prediction
* Habitability score
* Prediction confidence
* Planet summary
* Interactive user interface

## Sample Prediction

Input:

* Planet Radius: 1.0
* Planet Mass: 1.0
* Orbital Period: 365
* Star Temperature: 5778 K
* Star Luminosity: 1.0

Output:

* Potentially Habitable Planet
* Habitability Score: 95%

## Future Enhancements

* NASA Exoplanet Archive integration
* Deep Learning models
* Advanced visualization dashboards
* Multi-class habitability prediction
* Real-time exoplanet data analysis

## Author

Lakshmanan A

Artificial Intelligence & Data Science

## License

This project is developed for educational and research purposes.

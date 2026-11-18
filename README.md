# Hotel Booking Cancellation Prediction

A Machine Learning project developed for the **IT3091 – Machine Learning** module at the Sri Lanka Institute of Information Technology (SLIIT).

## Project Overview

Hotel booking cancellations create challenges for hotel management, including revenue uncertainty and room allocation difficulties.

This project develops a Machine Learning classification system to predict whether a hotel booking will be cancelled or not, using booking-related information.

## Problem Statement

Predict hotel booking cancellations using historical booking data.

- **Problem Type:** Supervised Learning – Binary Classification
- **Target Variable:** `is_canceled`
- **0:** Booking not cancelled
- **1:** Booking cancelled

## Dataset

- **Dataset:** Hotel Booking Demand
- **Source:** (https://www.kaggle.com/code/abdomohamed782/hotel-booking-cancellation-prediction/input?select=hotel_bookings.csv)
- **Original Records:** 119,390 bookings
- **Original Features:** 32 columns

## Project Workflow

The project follows four main stages:

1. **Data Preparation & EDA**
   - Data cleaning
   - Duplicate removal
   - Exploratory Data Analysis
   - Initial feature preparation

2. **Preprocessing**
   - Feature engineering
   - Missing value imputation
   - StandardScaler
   - One-Hot Encoding
   - Class imbalance handling
   - Feature selection

3. **Model Training**
   - Logistic Regression
   - K-Nearest Neighbors
   - Decision Tree
   - Random Forest
   - Linear SVC
   - Hyperparameter tuning and cross-validation

4. **Model Evaluation**
   - Model comparison
   - Classification metrics
   - Confusion matrix
   - Threshold and error analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Final Model Performance

The tuned Random Forest was selected as the final model.

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 83.3% |
| Precision | 66.2% |
| Recall | 80.5% |
| F1-Score | 72.6% |
| ROC-AUC | 90.9% |
| PR-AUC | 0.794 |

*Results are from the held-out test set.*

## Repository Structure

```text
hotel-booking-cancellation-prediction/
│
├── notebooks/
│   └── hotel_booking_cancellation_prediction_1.ipynb
│
├── reports/
│   └── 2026_DS_46_Final_Report.docx
│
├── demo/
│   └── demo_video_link.txt
│
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone this repository.
2. Install the required dependencies
3. Download the Hotel Booking Demand dataset from its original Kaggle source.
4. Place the downloaded CSV file in the appropriate location.
5. Open the Jupyter Notebook.
6. Update the dataset file path if necessary.
7. Run the notebook cells.

## Academic Information

- **Module:** IT3091 – Machine Learning
- **Institution:** Sri Lanka Institute of Information Technology (SLIIT)
- **Group ID:** 2026-DS-46
- **Project:** Hotel Booking Cancellation Prediction

## Team Contributions

This project was completed collaboratively by four group members.

The responsibilities were divided into four main stages:

- **Data Preparation & EDA:** Data cleaning, duplicate removal, and exploratory data analysis.
- **Preprocessing:** Feature engineering, missing value imputation, feature encoding, feature scaling, class imbalance handling, and feature selection.
- **Model Training:** Training classification algorithms and performing hyperparameter tuning.
- **Model Evaluation:** Model comparison, performance evaluation, confusion matrix analysis, and error analysis.

My individual contribution was Preprocessing.

## Acknowledgements

- Kaggle – Hotel Booking Demand dataset
- SLIIT – Faculty of Computing
- IT3091 Machine Learning module
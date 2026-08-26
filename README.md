# Human Detection and Zone Classification

##  Project Overview

This project develops a machine learning-based system for detecting human presence and identifying the zone in which a person is located inside a room.

The room is divided into nine zones. Sensor data was collected for each zone by placing a human in one zone while keeping the other zones empty. Additional data was collected when the room was completely empty.

The problem is formulated as a 10-class classification problem.

##  Classes

| Class | Meaning |
|------:|---------|
| 0 | Empty Room |
| 1 | Human in Zone 1 |
| 2 | Human in Zone 2 |
| 3 | Human in Zone 3 |
| 4 | Human in Zone 4 |
| 5 | Human in Zone 5 |
| 6 | Human in Zone 6 |
| 7 | Human in Zone 7 |
| 8 | Human in Zone 8 |
| 9 | Human in Zone 9 |

##  Dataset

The dataset contains:

- 6,900 samples
- 256 sensor features
- 10 classes
- 690 samples per class
- No missing values

Class 0 represents an empty room, while classes 1–9 represent human presence in nine different zones.

##  Machine Learning Models

Several machine learning algorithms were evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- LightGBM

##  Methodology

The project follows these steps:

1. Dataset loading
2. Data inspection
3. Exploratory data analysis
4. Class distribution analysis
5. Train-test splitting
6. Feature scaling
7. Machine learning model training
8. Hyperparameter tuning
9. Model evaluation
10. Confusion matrix analysis
11. Best model selection
12. Human zone prediction

##  Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Macro F1-score
- Confusion Matrix

##  Best Model

The best-performing model was selected based on test accuracy and Macro F1-score.


Example:

**Best Model:** XGBoost  
**Test Accuracy:** 40.29%

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- TensorFlow/Keras
- Matplotlib
- Seaborn

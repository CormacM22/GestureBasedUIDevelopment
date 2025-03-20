# Classifiers Comparison Project

This project compares the performance of three machine learning models—Logistic Regression, Random Forest, and Support Vector Machine (SVM)—on a dataset. The goal is to evaluate and visualize the performance of these classifiers using metrics such as accuracy, precision, recall, and F1-score.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)

---

## Project Overview

The project involves:
1. Loading and preprocessing a dataset.
2. Training three classifiers: Logistic Regression, Random Forest, and SVM.
3. Evaluating the models using accuracy, precision, recall, and F1-score.
4. Visualizing the results for comparison.

The results show that SVM outperforms the other models, but all three classifiers achieve high performance on the dataset.

---

## Dataset

The dataset consists of:
- **Features**: Extracted from `features.txt`.
- **Labels**: Extracted from `targets.txt`.

The dataset is preprocessed by:
- Standardizing the features using `StandardScaler`.
- Splitting into training and testing sets (80-20 split).

---

## Models

Three classifiers are implemented and evaluated:
1. **Logistic Regression**:
   - A linear model for classification.
   - Trained with `max_iter=2000` to ensure convergence.

2. **Random Forest**:
   - An ensemble of decision trees.
   - Trained with `n_estimators=100`.

3. **Support Vector Machine (SVM)**:
   - A kernel-based model with a linear kernel.
   - Trained with default parameters.

---

## Results

The performance of the models is summarized below:

| Model               | Accuracy  | Precision  | Recall     | F1-Score  |
|---------------------|-----------|------------|------------|-----------|
| Logistic Regression | 0.984466  | 0.984492   | 0.984466   | 0.984468  |
| Random Forest       | 0.981553  | 0.981606   | 0.981553   | 0.981548  |
| SVM                 | 0.986408  | 0.986424   | 0.986408   | 0.986409  |

### Key Observations:
- **SVM** achieves the highest performance across all metrics.
- **Logistic Regression** performs slightly better than **Random Forest**.
- All models demonstrate strong performance, with metrics above 0.98.

---

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/CormacM22/GestureBasedUIDevelopment.git
   cd GestureBasedUIDevelopment

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
   - jupyter notebook Classifiers.ipynb

## Usage

1. Open the Classifiers.ipynb notebook.
2. Execute the cells to:
  - Load and preprocess the dataset.
  - Train and evaluate the models.
  - Visualize the results.

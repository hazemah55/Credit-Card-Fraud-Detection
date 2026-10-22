# Credit Card Fraud Detection Using Machine Learning

## Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. The goal is to develop a classification model capable of identifying potentially fraudulent transactions while addressing the challenge of highly imbalanced data.

The project uses a **Random Forest Classifier** and **SMOTE (Synthetic Minority Over-sampling Technique)** to improve fraud detection.

## Dataset

The dataset contains **284,807 credit card transactions**, including legitimate and fraudulent transactions.

Fraud detection is challenging because fraudulent transactions represent only a small percentage of the dataset.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Imbalanced Data Handling:** SMOTE
- **Algorithm:** Random Forest Classifier
- **Development Environment:** Jupyter Notebook / Google Colab

## Project Workflow

1. **Data Exploration:** Analyzed the dataset and investigated the distribution of fraudulent and legitimate transactions.
2. **Data Preprocessing:** Prepared the data for Machine Learning, including feature scaling.
3. **Class Imbalance Handling:** Applied SMOTE to address the imbalance between fraudulent and legitimate transactions.
4. **Model Training:** Trained a Random Forest classification model.
5. **Model Evaluation:** Evaluated performance using accuracy, precision, recall, and F1-score.

## Model Performance

The following results were reported during model evaluation:

| Evaluation Metric | Score |
|---|---|
| Accuracy | 99.94% |
| Fraud Precision | 84% |
| Fraud Recall | 83% |
| Fraud F1-score | 83% |

Although accuracy is high, **precision, recall, and F1-score are especially important** for fraud detection because the dataset is highly imbalanced.

## Key Learnings

Through this project, I gained practical experience in:

- Working with imbalanced classification datasets.
- Performing exploratory data analysis and preprocessing.
- Applying SMOTE to address class imbalance.
- Training and evaluating a Random Forest classifier.
- Interpreting classification metrics beyond accuracy.

## How to Run

1. Download or clone this repository.
2. Open `Credit_Card_Fraud_Detection.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required Python libraries.
4. Download the dataset and update its file path if necessary.
5. Run the notebook cells in order.

## Future Improvements

- Compare Random Forest with other classification algorithms.
- Explore additional techniques for handling class imbalance.
- Experiment with hyperparameter optimization.
- Develop a simple web application for transaction classification.

## Author

**Hazem Ahmed Wageh**

Computer Science Student | Aspiring Data Scientist

GitHub: [hazemah55](https://github.com/hazemah55)
